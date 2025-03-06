# Memoria

This is an open source PasteBin clone. I wanted to create a self-hosted
clone that can easily be deployed with docker. I often switch systems and find myself
losing my copy and paste history between systems.

## 🚀 Features

- Pastebin-like interface
- Markdown support
- Custom domain support
- Frontend built with SvelteKit running on Bun
- Backend API service written in GoLang
- Docker containerization for easy deployment

## Screenshots

<div align="center">
  <img src="docs/application_screenshot.png" alt="Home page" width="80%" />
  <p><em>Memoria home page with dark theme</em></p>
</div>

## 📋 Prerequisites

- Docker and Docker Compose
- Git (for submodule management)

## 🛠️ Installation

1. Clone the repository with submodules:

```bash
git clone --recursive https://github.com/unfaiyted/memoria.git
cd memoria
```

2. Initialize and update submodules:

```bash
git submodule update --init --recursive
```

## 🏗️ Development Setup

### Frontend

```bash
cd memoria-frontend
bun install
bun run dev
```

### Backend

```bash
cd memoria-backend
# Add backend setup instructions here
```

## 🐳 Docker Deployment

Build and run the entire stack:

```bash
docker compose up -d --build
```

Individual services can be built and run separately:

```bash
# Frontend only
docker compose up frontend

# Backend only
docker compose up backend
```

## 🏗️ Project Structure

```
memoria/
├── docker-compose.yml
├── frontend/    # Frontend submodule
└── backend/     # Backend submodule
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with Bun
- Docker containerization
- All contributors and maintainers
