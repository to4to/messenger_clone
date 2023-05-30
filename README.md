
# Messenger Clone
This repository contains a full-fledged messenger clone built using Next.js 13, React, Tailwind CSS, Prisma, MongoDB, NextAuth, and Pusher. The goal of this project is to provide a scalable and feature-rich messaging application that resembles popular messaging platforms.

## Features

- Real-time messaging: Users can send and receive messages instantly, thanks to the real-time capabilities provided by Pusher.
- User authentication: NextAuth is used for user authentication, allowing users to sign up, log in, and manage their accounts securely.
- Persistent storage: Messages and user data are stored in a MongoDB database using Prisma, ensuring data integrity and easy retrieval.
- Responsive design: The application is built with a mobile-first approach and is fully responsive across various screen sizes.
- Modern UI: The UI is designed using Tailwind CSS, providing a sleek and visually appealing user experience.

## Setup

To set up and run this project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/to4to/messenger_clone.git
```

2. Navigate to the project directory:

```bash
cd messenger_clone
```

3. Install the dependencies:

```bash
npm install
```

4. Set up environment variables:

   - Create a `.env.local` file in the root directory.
   - Add the following environment variables and provide their corresponding values:

     ```
     MONGODB_URI=your_mongodb_uri
     PUSHER_APP_ID=your_pusher_app_id
     PUSHER_KEY=your_pusher_key
     PUSHER_SECRET=your_pusher_secret
     NEXTAUTH_SECRET=your_nextauth_secret
     ```


     You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

     This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.   

5. Run the application:

```bash
npm run dev
```

6. Open your browser and navigate to `http://localhost:3000` to access the messenger clone.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

Before contributing, make sure to review the [contribution guidelines](CONTRIBUTING.md) for detailed instructions.

## License

This project is licensed under the [MIT License](LICENSE).

---

Start building your own messenger clone with Next.js, React, Tailwind, Prisma, MongoDB, NextAuth, and Pusher! Enjoy real-time messaging and a modern UI. Let's chat away! 🚀




