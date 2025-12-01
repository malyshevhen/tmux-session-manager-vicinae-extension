# TMUX Sessions Manager

A Vicinae extension for managing TMUX sessions. This extension allows you to:

- **List** all existing TMUX sessions with detailed previews
- **View** session status, current window, pane count, and creation time
- **Create** new TMUX sessions with custom working directories
- **Switch** to existing TMUX sessions
- **Rename** TMUX sessions
- **Delete** TMUX sessions

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
   - Rename a session (Cmd+R)
   - Delete a session (Cmd+Delete)
   - Create a new session (Cmd+N)

## Features

- **Session Listing**: Automatically lists all active TMUX sessions
- **Session Creation**: Create new detached sessions with custom working directories
- **Session Switching**: Quickly switch between existing sessions
- **Session Renaming**: Rename sessions with a simple form interface
- **Session Deletion**: Remove unwanted sessions with confirmation
- **Error Handling**: Provides user feedback for all operations
If you want to build the production bundle, simply run:

```bash
npm run build
```
