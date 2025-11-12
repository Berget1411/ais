# AI Society 🤖

A community dedicated to the exploration, research, and continuous learning of Artificial Intelligence across Swedish universities.

![Next.js](https://img.shields.io/badge/Next.js-16.0-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-19.2-61DAFB?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.x-38B2AC?style=flat-square&logo=tailwind-css)
![Bun](https://img.shields.io/badge/Bun-1.x-000000?style=flat-square&logo=bun)

## 🌟 About

This project showcases a unified platform for AI societies across multiple Swedish universities, including:

- **KTH AI Society** - Royal Institute of Technology, Stockholm
- **LIU AI Society** - Linköping University
- **UU AI Society** - Uppsala University  
- **SASSE AI Society** - Stockholm School of Economics

## 🚀 Tech Stack

- **Framework:** [Next.js 16](https://nextjs.org/)
- **UI Library:** [React 19](https://react.dev/)
- **Styling:** [Tailwind CSS 4](https://tailwindcss.com/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Package Manager:** [Bun](https://bun.sh/)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **UI Components:** [Radix UI](https://www.radix-ui.com/)
- **Icons:** [Lucide React](https://lucide.dev/) & [React Icons](https://react-icons.github.io/react-icons/)

## 📋 Prerequisites

Before you begin, ensure you have installed:

- [Bun](https://bun.sh/) (v1.0 or higher)
- [Node.js](https://nodejs.org/) (v18 or higher) - optional, as Bun can replace Node
- [Docker](https://www.docker.com/) (optional, for containerized deployment)

## 🛠️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/ais.git
cd ais
```

2. **Install dependencies:**

```bash
bun install
```

## 🏃 Running the Development Server

Start the development server with hot-reload:

```bash
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## 🏗️ Building for Production

Create an optimized production build:

```bash
bun run build
```

Start the production server:

```bash
bun start
```

## 🐳 Docker Deployment

The project includes a multi-stage Dockerfile optimized for production deployment and a Docker Compose configuration for easy orchestration.

### Using Docker Compose (Recommended):

Start the application with Docker Compose:

```bash
docker-compose up
```

Build and run in detached mode:

```bash
docker-compose up -d --build
```

Stop the application:

```bash
docker-compose down
```

The application will be available at [http://localhost:3000](http://localhost:3000).

### Manual Docker Build (Alternative):

If you prefer to use Docker directly without Compose:

```bash
docker build -t ais .
docker run -p 3000:3000 ais
```

## 📁 Project Structure

```
ais/
├── app/                    # Next.js app directory
│   ├── layout.tsx         # Root layout
│   ├── page.tsx           # Home page
│   └── globals.css        # Global styles
├── components/
│   ├── home/              # Home page components
│   │   ├── header.tsx
│   │   ├── main.tsx
│   │   ├── footer.tsx
│   │   ├── connect/       # Social connection components
│   │   └── constants.ts   # AI societies data
│   └── ui/                # Reusable UI components
│       ├── background.tsx
│       ├── button.tsx
│       ├── magnetic.tsx
│       └── text-scramble.tsx
├── lib/                   # Utility functions
├── public/                # Static assets
├── Dockerfile            # Docker configuration
├── next.config.ts        # Next.js configuration
├── tailwind.config.ts    # Tailwind CSS configuration
└── package.json          # Dependencies
```

## 🎨 Key Components

- **Background**: Dynamic color-changing background with smooth transitions
- **BackgroundRippleEffect**: Interactive ripple animation
- **Magnetic**: Magnetic hover effect for interactive elements
- **TextScramble**: Text scramble animation effect
- **Carousel**: Swipeable carousel for browsing AI societies

## 🧪 Linting

Run ESLint to check code quality:

```bash
bun run lint
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Connect with AI Societies

- **KTH AI Society**: [Website](https://kthais.com) | [LinkedIn](https://www.linkedin.com/company/kthaisociety/) | [Instagram](https://www.instagram.com/kthaisociety/)
- **LIU AI Society**: [Website](https://liuais.com) | [LinkedIn](https://www.linkedin.com/company/liu-ai-society/) | [Instagram](https://www.instagram.com/liuaisociety)
- **UU AI Society**: [Website](https://www.uuais.com) | [LinkedIn](https://www.linkedin.com/company/uu-ai-society/) | [Instagram](https://www.instagram.com/uuaisociety)
- **SASSE AI Society**: [LinkedIn](https://www.linkedin.com/company/sasse-ai-society)

## 💬 Support

For questions or support, please reach out to the respective AI society through their social media channels or contact@kthais.com.

---

Built with ❤️ by the Swedish AI Society Community
