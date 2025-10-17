# cátte — VRC Processor

Automatically configures VRChat avatar models with optimal import settings.

## Features

- **Automatic Humanoid Detection**: Sets valid models to Humanoid rig type on import
- **Read/Write Enabled**: Ensures meshes are readable for VRChat features
- **BlendShape Normals**: Imports blend shape normals for better facial animations
- **One-Time Processing**: Only processes each model once (tracked via SessionState)
- **Non-Intrusive**: Runs automatically in the background

## Installation

Install via VRChat Creator Companion (VCC) or add to your Unity project's Packages folder.

## Usage

This tool works automatically! Simply import avatar FBX files and VRCProcessor will:
1. Detect if the model has a valid humanoid skeleton
2. Set the rig type to Humanoid if applicable
3. Enable Read/Write for mesh data
4. Import blend shape normals

No manual configuration needed.

## Requirements

- Unity 2019.4 or later
- VRChat SDK3 Avatars (optional, but tool is VRChat-focused)

## License

MIT License - see LICENSE file for details
