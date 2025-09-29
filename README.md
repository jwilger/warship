# Warship

A terminal-based implementation of the classic Battleship game with modern
features.

## Overview

This project implements the traditional Battleship game as a command-line
application with a text-based user interface (TUI). Players can engage in
strategic naval combat by placing ships on a grid and attempting to sink their
opponent's fleet.

## Game Modes

- **AI Opponent**: Play against a computer opponent with intelligent ship
  placement and targeting
- **Network Multiplayer**: Play against another human player over a network
  connection

## Features

- Interactive TUI for intuitive gameplay
- Classic Battleship rules and mechanics
- Real-time multiplayer support
- Cross-platform compatibility

## Development Environment

This project uses:

- **Rust** - Modern systems programming language for performance and safety
- **Nix** - Reproducible development environment setup
- **Pre-commit hooks** - Automated code quality checks

## Getting Started

### Prerequisites

- Nix package manager (recommended)
- Rust toolchain (if not using Nix)

### Setup

```bash
# Clone the repository
git clone <repository-url>
cd battleship

# Enter development environment (Nix)
nix develop

# Or install Rust toolchain manually if not using Nix
# Follow instructions at https://rustup.rs/
```

## Project Status

🚧 **In Development** - Core implementation in progress

---

_More detailed documentation including architecture, requirements, and API
specifications will be available as development progresses._
