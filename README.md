# TMUX Sessions Manager

![TMUX](./assets/extension_icon.png)

A Vicinae extension for managing TMUX sessions. This extension allows you to:

- **List** all existing TMUX sessions with detailed previews
- **View** session status, window count, pane count, and last attached time
- **Create** new TMUX sessions with custom working directories and path suggestions
- **Switch** to existing TMUX sessions
- **Rename** TMUX sessions
- **Delete** TMUX sessions
- **Manage Windows**: Create, rename, delete, and switch windows within sessions

## Installation

Install the required dependencies and run your extension in development mode:

```bash
npm install
npm run dev
```

To build the production bundle:

```bash
npm run build
```

## Requirements

- TMUX must be installed and available in your PATH
- Vicinae launcher must be running

## Usage

1. Launch the extension from Vicinae
2. View all existing TMUX sessions
3. Use the action panel to:
   - Switch to a session (Enter)
   - Manage windows (Shift+Return)
   - Rename a session (Ctrl+R)
   - Delete a session (Ctrl+D)
   - Create a new session (Ctrl+N)
4. In window management view:
   - Switch to specific windows
   - Rename windows (Ctrl+R)
   - Delete windows (Ctrl+D)
   - Create new windows (Ctrl+N)

## Features

- **Session Listing**: Automatically lists all active TMUX sessions with attachment status
- **Session Creation**: Create new detached sessions with custom working directories and intelligent path suggestions
- **Session Switching**: Quickly switch between existing sessions
- **Session Renaming**: Rename sessions with a simple form interface
- **Session Deletion**: Remove unwanted sessions with confirmation dialogs
- **Window Management**: Complete window lifecycle management within sessions
- **Real-time Updates**: Auto-refreshes sessions every 5 seconds, windows every 2 seconds
- **Visual Indicators**: Green/white dots show attachment and active status
- **Smart Path Suggestions**: Dropdown with recent and common directories for session creation
- **Error Handling**: Comprehensive user feedback for all operations
- **Keyboard Shortcuts**: Efficient workflow with customizable shortcuts

## Roadmap

### High Priority Features

#### ✅ 1. **Window Management** (Implemented)

- View window details (panes, layout, activity)
- Create new windows in existing sessions
- Rename/delete windows
- Switch to specific windows

#### 2. **Session Templates/Presets**

- Save common session configurations
- Quick-create with predefined window layouts
- Favorite directories for common projects

#### 3. **Advanced Search & Filtering**

- Filter by attachment status (attached/detached)
- Filter by window count or pane count
- Search within window names
- Sort by creation time, name, or activity

### Medium Priority Features

#### 4. **Session Groups/Workspaces**

```
Project Alpha
├── alpha-dev (3 windows)
├── alpha-test (1 window)
└── alpha-prod (2 windows)

Project Beta
├── beta-api (2 windows)
└── beta-web (4 windows)
```

#### 5. **Pane Management**

- View pane contents/layout in sessions
- Send commands to specific panes
- Split panes, resize panes
- Pane navigation shortcuts

#### 6. **Session Monitoring**

- Show active processes in sessions
- CPU/memory usage per session
- Session uptime and activity indicators
- Alert for crashed/disconnected sessions

### Advanced Features

#### 7. **Integration Features**

- **Project Detection**: Auto-suggest session names based on current directory
- **Git Integration**: Create sessions based on git branches
- **Docker Integration**: Sessions for containerized workflows
- **SSH Integration**: Remote TMUX session management

#### 8. **Session Backup/Restore**

- Export session configurations
- Import and recreate complex session layouts
- Backup running sessions before system updates

#### 9. **Multi-Session Operations**

- Bulk rename sessions with patterns
- Move windows between sessions
- Merge sessions
- Session templates with variables

#### 10. **Customization & Preferences**

- Custom keyboard shortcuts
- Default session creation options
- Theme preferences (colors for different session types)
- Notification preferences
