#  FurryOS - Web-Based Operating System

![Version](https://img.shields.io/badge/version-1.0.0-orange)
![License](https://img.shields.io/badge/license-MIT-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![Supabase](https://img.shields.io/badge/Supabase-Backend-green)

**FurryOS** is a complete web-based operating system simulation that runs entirely in your browser. It features a fully functional desktop environment with windows, file management, applications, and cloud storage backend powered by Supabase.

## ✨ Features

### 🖥️ Desktop Environment
- Draggable desktop icons with position saving
- Right-click context menus (copy, cut, paste, rename, delete)
- Taskbar with window management
- Start menu with user info and storage display
- Real-time clock

### 📁 File System
- Virtual C: and D: drives
- File manager with address bar navigation
- Create, rename, delete, copy, cut, paste files/folders
- Recycle bin with 2-day auto-cleanup
- 50KB cloud storage per user

### 🌐 Multi-Tab Browser
- Multiple tabs support
- Link interception (opens within browser)
- Back/forward/refresh navigation
- Cross-origin proxy via Supabase Edge Function

### 🎮 Game Center
- Eaglercraft (Minecraft Web Edition)
- Full mouse and keyboard support
- Resizable window

### 📬 File Sharing Cabinet
- Upload .txt and .html files
- Generate 6-digit pickup codes
- Download with code
- Browse directory selection

### 💬 Forum System
- Post and reply functionality
- Categories: General, Help, Share, Announcement
- View counts and reply counts
- Delete own posts

### 🤖 AI Assistant (FurryAI)
- Floating widget (draggable, minimizable)
- 3 calls per minute rate limit
- Natural language command recognition
- Can open apps and help with system operations

### 💻 Terminal
- Black/green command-line interface
- Commands: help, dir, cd, type, start, cls, echo, time, whoami, exit
- Launch .frs applications

### 🔐 User System
- Register/Login with Supabase Auth
- Password change functionality
- 50KB personal cloud storage

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5/CSS3 | UI and styling |
| JavaScript ES6+ | Core logic |
| Supabase | Authentication, Database, Storage |
| Supabase Edge Functions | Proxy service, AI assistant |

## 🚀 Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/furrium/furryos

