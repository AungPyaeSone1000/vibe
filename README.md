# Vibe

Vibe is a social media application built using [Next.js](https://nextjs.org/). The application is currently deployed and accessible at [vibe-phi.vercel.app](https://vibe-phi.vercel.app).

## Features

- User authentication and profile management
- Post creation, editing, and deletion
- Real-time updates and notifications
- Responsive design for various devices

## Technologies Used

- Next.js
- Typescript
- React
- Tailwind CSS
- PostgreSQL
- Prisma
- -Neon
- Clerk
- Uploadthing
  

## Getting Started

To get a local copy of the project up and running, follow these steps:

### Prerequisites

- Node.js (v14.x or later)
- npm (v6.x or later) or yarn

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/AungPyaeSone1000/vibe.git
   cd vibe
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up the database:**

   - Ensure you have a PostgreSQL database running.
   - Configure the database connection in the `.env` file.
   - Run the Prisma migrations:

     ```bash
     npx prisma migrate dev
     ```

4. **Start the development server:**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.

---

*Note: This README is based on the available information and may need adjustments to align with the current state of the project.* 
