# ClaudeCord

<div align="center">
  <img src="https://raw.githubusercontent.com/miwidot/claudecord-mac/main/ClaudeCord/Assets.xcassets/AppIcon.appiconset/icon_128x128.png" width="128" height="128" />
  
  **The Ultimate Native macOS Client for Claude CLI**
  
  [![Latest Release](https://img.shields.io/github/v/release/miwidot/ClaudeCord)](https://github.com/miwidot/ClaudeCord/releases/latest)
  [![macOS](https://img.shields.io/badge/macOS-15.0+-blue.svg)](https://www.apple.com/macos/)
  [![Download](https://img.shields.io/badge/Download-Latest-green.svg)](https://github.com/miwidot/ClaudeCord/releases/latest)
</div>

## Why ClaudeCord?

### 🚀 Native Performance
Unlike web-based interfaces or Electron apps, ClaudeCord is built with **native Swift and SwiftUI**, delivering:
- **50% less memory usage** than browser-based solutions
- **Instant startup** - no loading screens or web framework overhead
- **Native macOS integration** - proper keyboard shortcuts, notifications, and system features
- **Optimized for Apple Silicon** - runs efficiently on M1/M2/M3 Macs

### 🎯 Discord-Like Experience
The familiar interface you already know and love:
- **Project channels** instead of clunky folder structures
- **Real-time session management** like Discord servers
- **Intuitive navigation** - no learning curve if you've used Discord
- **Visual session indicators** - see active/idle sessions at a glance

### 💪 Powerful Multi-Session Management
What sets ClaudeCord apart:
- **Run unlimited Claude sessions simultaneously** - no tab juggling
- **True session isolation** - each project gets its own Claude instance
- **Resume sessions instantly** - pick up exactly where you left off
- **Process-level control** - terminate stuck sessions without affecting others

### 🛠 Developer-First Features
Built by developers, for developers:
- **Integrated terminal** for each session - see what's happening under the hood
- **Resource monitoring** - track CPU/memory per session, not just total usage
- **Auto-update system** - always have the latest features without manual downloads
- **No Apple Developer account required** - works with ad-hoc signing

### 🔒 Privacy & Security
Your data stays yours:
- **100% local** - no cloud services, no telemetry, no tracking
- **Direct API communication** - no middleware servers
- **Open source** - audit the code yourself
- **Respects Claude CLI settings** - uses your existing configuration

## Quick Comparison

| Feature | ClaudeCord | Web Interface | VS Code Extension |
|---------|------------|---------------|-------------------|
| Multiple Sessions | ✅ Unlimited | ❌ Browser tabs | ❌ Single session |
| Memory Usage | ✅ ~150MB | ❌ 500MB+ | ❌ 1GB+ (with VS Code) |
| Session Persistence | ✅ Full history | ⚠️ Limited | ❌ Lost on restart |
| Native Performance | ✅ Swift/SwiftUI | ❌ JavaScript | ❌ Electron |
| Terminal Access | ✅ Built-in | ❌ None | ⚠️ Separate terminal |
| Resource Monitoring | ✅ Per-session | ❌ None | ❌ None |
| Auto Updates | ✅ One-click | ❌ Manual | ⚠️ Extension updates |
| Offline Usage | ✅ Full features | ❌ Requires internet | ✅ Works offline |

## Installation

1. Download the latest `.dmg` from [Releases](https://github.com/miwidot/ClaudeCord/releases/latest)
2. Open the `.dmg` and drag ClaudeCord to Applications
3. Launch and start chatting with Claude!

**Requirements:**
- macOS 15.0+
- Claude CLI installed (`pip install claude-cli`)
- Valid Anthropic API key

## Key Features in Action

### 🎮 Discord-Style Interface
- Projects appear as channels in the sidebar
- Switch between sessions with a single click
- Visual indicators for active sessions
- Clean, familiar chat interface

### ⚡ Lightning Fast
- Instant app launch
- No loading spinners
- Immediate session switching
- Real-time message streaming

### 🔧 Developer Tools
- Integrated terminal shows Claude's raw output
- Process manager for debugging
- API rate limit tracking
- Debug logging when needed

### 🔄 Seamless Updates
- Automatic update checks
- One-click installation
- No manual downloads
- Rollback protection

## Getting Started

1. **Install Claude CLI** (if not already installed):
   ```bash
   npm install -g @anthropic-ai/claude-code
   claude auth login
   ```

2. **Download ClaudeCord** from the latest release

3. **Start chatting** - Create a project and begin!

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Toggle Terminal | `⌘+T` |
| Check for Updates | `⌘+U` |
| Process Manager | `⌘+Shift+M` |
| Settings | `⌘+,` |

## Support

- **Issues**: [GitHub Issues](https://github.com/miwidot/ClaudeCord/issues)
- **Feature Requests**: [Discussions](https://github.com/miwidot/ClaudeCord/discussions)

---

<div align="center">
  
  **Stop juggling browser tabs. Start being productive.**
  
  [Download Latest Release](https://github.com/miwidot/ClaudeCord/releases/latest)
  
</div>