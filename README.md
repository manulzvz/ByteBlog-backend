# ByteBlog Backend

ByteBlog Backend is a Strapi-based application designed to provide a robust and scalable backend for the ByteBlog platform. It leverages modern technologies to deliver a seamless blogging experience.

## Tech Stack

- **Backend**: [Strapi](https://strapi.io) (v5.23.0)
- **Database**: PostgreSQL
- **Cloud Storage**: Cloudinary
- **Frontend Dependencies**: React, React Router, Styled Components
- **Language**: TypeScript

## Setup Instructions

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/manulzvz/ByteBlog-backend.git
   cd ByteBlog-backend
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Configure Environment Variables**:

   - Copy the `.env` file and update the values as needed:
     ```bash
     cp .env.example .env
     ```

4. **Run Database Migrations** (if applicable):

   ```bash
   npm run migrate
   ```

5. **Start the Development Server**:

   ```bash
   npm run develop
   ```

   The server will be available at `http://localhost:1337`.

## Usage

- **Development**:
  ```bash
  npm run develop
  ```
- **Production**:
  ```bash
  npm run start
  ```
- **Build Admin Panel**:
  ```bash
  npm run build
  ```

## Deployment

ByteBlog Backend supports various deployment options, including [Strapi Cloud](https://cloud.strapi.io). Refer to the [deployment documentation](https://docs.strapi.io/dev-docs/deployment) for more details.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a clear description of your changes.

---

Built with ❤️ by [manulzvz](https://github.com/manulzvz).
