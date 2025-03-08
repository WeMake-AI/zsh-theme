# 💙 WeMake ZSH Theme

![WeMake ZSH Theme Preview](https://raw.githubusercontent.com/WeMake-AI/zsh-theme/main/assets/terminal-preview.png)

> **Empowering Your Terminal Experience**: Aligning with WeMake's mission of making work easier, faster, and more meaningful.

## 🚀 Overview

The WeMake ZSH Theme transforms your terminal into a powerful, intuitive workspace that enhances productivity and reduces cognitive load. As part of WeMake's ecosystem of digital transformation tools, this theme embodies our core principles of **Digital-First**, **Innovation**, **Sustainability**, and **Impact**.

This minimalist yet informative theme prioritizes what matters most to developers and IT professionals: clear information hierarchy, intelligent version control integration, and a visually pleasing interface that reduces eye strain during long coding sessions.

## ✨ Key Features

### 🔹 Intelligent Information Architecture

- **Structured Multi-Line Prompt**: A thoughtfully designed three-line prompt that separates command history, contextual information, and input space for enhanced readability and reduced cognitive load.
- **Context-Aware Status Indicators**: Automatically displays SSH connection status and version control information when relevant, keeping you informed without cluttering your workspace.
- **Seamless Version Control Integration**: Full support for Git, SVN, and Mercurial with visual indicators for branch status, changes, and repository health.

### 🔹 Digital-First Design

- **True 24-bit Color Support**: Leverages the full spectrum of 16.7 million colors for a visually rich experience that enhances information hierarchy and reduces eye strain.
- **Optimized for Modern Terminals**: Fully compatible with cutting-edge terminal emulators while providing graceful fallbacks for legacy environments.
- **Intelligent Completion System**: Enhanced tab completion with intuitive color coding, caching, and semantic grouping that makes navigation faster and more efficient.

### 🔹 Focus-Enhancing Experience

- **Distraction-Free Interface**: Clean, minimal design that puts your work front and center while keeping essential information accessible.
- **Enhanced Terminal Utilities**: Optimized settings for common tools like `less` and `man` pages, creating a cohesive and efficient experience.
- **Visual Consistency**: Harmonious color scheme based on WeMake's brand colors for a pleasant, consistent experience that reduces context-switching fatigue.

## 📊 Detailed Features

### Multi-Line Prompt Architecture

Our prompt is structured to maximize productivity and information clarity:

**Top Line: Context Delimiter**
A visual separator that clearly delineates previous command output from your current context, reducing visual noise when reviewing complex command outputs.

**Middle Line: Information Hub**
Your command context center with three key information segments:

- **Connection Status**: Clear SSH indicator when working on remote systems
- **Location Context**: Your current directory path with intelligent abbreviation
- **Version Control Status**: Comprehensive Git/SVN/Mercurial information including:
  - Active branch name
  - Visual indicators for staged changes (A)
  - Visual indicators for modified files (M)
  - Visual indicators for untracked files (U)
  - Special status indicators for merge, rebase, or other operations

**Bottom Line: Command Input**
A clean, focused input area with a minimal prompt indicator, giving you maximum space for your commands.

### Terminal Enhancement Suite

Beyond the prompt, WeMake ZSH Theme provides a comprehensive environment optimization:

- **Intelligent Completion System**: Enhanced tab completion with semantic grouping, fuzzy matching, and visual differentiation between files, commands, and options.
- **Advanced Color Configuration**: Optimized `LS_COLORS` for both BSD and GNU systems, making directory listings more informative at a glance.
- **Documentation Enhancement**: Improved `less` and `man` page configurations for more readable documentation.

## 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/WeMake-AI/zsh-theme ~/.oh-my-zsh/themes/

# Add the theme to your .zshrc
echo 'source ~/.oh-my-zsh/themes/WeMake.zsh-theme' >> ~/.zshrc

# Set WeMake as your ZSH theme
sed -i '' 's/ZSH_THEME=".*"/ZSH_THEME="WeMake"/' ~/.zshrc

# Reload your terminal configuration
source ~/.zshrc
```

## 🎨 Optimization Recommendations

### Font Selection

For the best experience, we recommend using [WeMake Sans Terminal](https://github.com/WeMake-AI/WeMake-Sans-Terminal-Font), our custom-designed font that ensures perfect rendering of all special characters used in the theme.

Alternative compatible fonts include:

- **JetBrains Mono**
- **Fira Code**
- **Cascadia Code**
- **Menlo**
- **SF Mono**

### Color Scheme

For optimal visual harmony:

- **Terminal Background**: `#000c25` (WeMake Deep Blue)
- **Terminal Foreground**: `#FFFFFF`

## 🌐 About WeMake

WeMake is a pioneering digital transformation company that empowers organizations through advanced technologies and industry expertise. We operate as a fully digital, iterative, and sustainable company, ensuring long-term societal returns on every investment.

### Our Mission

We empower people through AI, making work easier, faster, and more meaningful.

### Our Vision

A world where AI helps everyone reach their full potential.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](./docs/LICENSE) file for details.

## 🔒 Security

For security concerns, please review our [Security Policy](./docs/SECURITY.md).
