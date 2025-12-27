# SuperTerminals

<div align="center">
  <h3>Multi-Terminal Manager</h3>
  <p>Modern graphical interface for managing multiple terminals, similar to Docker Desktop</p>
</div>

---

## About

**SuperTerminals** is a desktop application that allows you to manage multiple terminals/commands visually and intuitively. You can add, configure, and execute commands in different directories through a user-friendly interface.

### Features

- Modern and intuitive graphical interface
- Management of multiple terminals
- Play/Stop controls for each terminal
- Real-time execution time display
- Real-time logs
- Configuration persistence using JSON
- Standalone executable (cross-platform)
- Lightweight and performant

### Tech Stack

- **Frontend**: React 18 + TypeScript + Vite + TailwindCSS
- **Backend**: Tauri + Rust
- **Persistence**: Local JSON

---

## Quick Start

### Prerequisites

1. **Node.js** >= 18
2. **Rust** >= 1.70
3. **pnpm**

### Installation

bash
# Install dependencies
pnpm install

# Run in development mode
pnpm tauri dev

# Build for production
pnpm tauri build


For detailed installation instructions, see [SETUP.md](./SETUP.md)

---

## Documentation

- [README](./docs/README.md) - Full overview
- [ARCHITECTURE](./docs/ARCHITECTURE.md) - Detailed architecture
- [API](./docs/API.md) - API reference
- [DEVELOPMENT](./docs/DEVELOPMENT.md) - Development guide
- [SETUP](./SETUP.md) - Installation instructions

---

## Project Structure


superTerminals/
├── docs/              # Documentation
├── src/               # React Frontend
├── src-tauri/         # Rust Backend
└── package.json


---

## Project Status

- [x] Complete documentation
- [x] Initial project setup
- [x] Folder structure
- [x] Rust backend (complete commands)
- [x] React components (all implemented)
- [x] Frontend-backend integration (working)
- [x] Complete and functional interface
- [x] Grid/List view toggle
- [x] Real-time log system
- [x] Production build
- [ ] Automated tests

**Status**: ✅ **FULLY FUNCTIONAL APPLICATION!**

---

## Screenshots

### Main Interface - Card View
![Main Interface](./imagens/f1.jpeg)

### List View
![List View](./imagens/f2.jpeg)

### Add New Terminal
![Add Terminal](./imagens/f3.jpeg)

### Real-time Logs
![Real-time Logs](./imagens/f4.jpeg)

### Process Management
![Process Management](./imagens/f5.jpeg)

---

## License

MIT

## Author

Henrique
