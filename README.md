# Let's Restore 🕒

A robust file versioning and restoration system that allows you to track changes in local directories and restore previous versions of files or entire folders with ease.

## 🚀 Features

- **Real-time Monitoring**: High-performance C++ watcher detects file changes instantly.
- **Version History**: Automatically creates snapshots of your files as they change.
- **Smart Restoration**: Restore individual files or entire directory structures to any previous point in time.
- **Cross-Platform Core**: Built with Electron, React, and Node.js for a seamless desktop experience.
- **Minimalist UI**: Clean, glassmorphic dashboard for managing your tracked folders and versions.

## 🛠️ Technology Stack

- **Frontend**: React + Vite
- **Backend**: Node.js + Express
- **Desktop Wrapper**: Electron
- **File Watcher**: Custom C++ implementation for low-latency monitoring

## 📂 Project Structure

- `frontend/`: React-based user interface.
- `backend/`: Node.js server handling file logic and versioning.
- `electron/`: Main process and bridge for the desktop application.
- `watcher/`: Native C++ watcher source code.

## 🏁 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- C++ compiler (for building the watcher if modified)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/arpitsehal/restore.git
   ```

2. Install dependencies:
   ```bash
   npm install
   cd frontend && npm install
   cd ../backend && npm install
   cd ../electron && npm install
   ```

### Running the App

To start the development environment (backend, frontend, and electron):

```bash
./start-dev.bat
```

## 📄 License

This project is licensed under the MIT License.
