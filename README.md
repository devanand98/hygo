# Hygo

Hygo is a freelance web application built with Next.js, Tailwind CSS, and TypeScript. This project includes both frontend and backend components, providing a scalable foundation for modern web development. It is currently deployed on Vercel - https://hygoreact.vercel.app/

## Features
- Next.js framework for optimized performance and routing
- Tailwind CSS for responsive and efficient styling
- TypeScript for type-safe development
- Server-side functionality with `server.js`

## Installation
To set up the project locally, follow these steps:

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (Latest LTS version recommended)
- npm or yarn

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/hygo.git
   cd hygo-main
   ```

2. Install dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```sh
   npm run dev
   # or
   yarn dev
   ```

The application should now be running at `http://localhost:3000/`.

## Project Structure
```
├── app/                 # Frontend components
│   ├── layout.tsx       # Main layout file
│   ├── page.tsx         # Home page
│   ├── globals.css      # Global styles
├── server.js            # Backend server logic
├── package.json         # Project dependencies and scripts
├── tsconfig.json        # TypeScript configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── next.config.js       # Next.js configuration
```

## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Make your changes and commit (`git commit -m "Added a new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License
This project is licensed under the MIT License. See `LICENSE` for details.

## Contact
For any questions or suggestions, please open an issue on GitHub or reach out to the maintainers.
