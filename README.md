# SolidProgramming – Unraid Templates

Community Applications templates for Unraid maintained by **SolidProgramming**.

## Available Templates

### FinTV

FinTV creates virtual 24/7 TV channels from your Jellyfin media library and provides them as HLS streams.

<img width="1400" height="506" alt="brave_6gfCIM9jaU" src="https://github.com/user-attachments/assets/8a1c8d6a-da8b-472c-9adb-dff7dca926f6" />

The FinTV container also provides the Jellyfin plugin repository, allowing you to install and manage the plugin directly through Jellyfin.

**Features:**
- Create virtual 24/7 TV channels from your Jellyfin library
- HLS streaming support
- Jellyfin plugin integration
- Configurable media path mappings
- CPU encoding with `libx264`
- Optional NVIDIA NVENC hardware acceleration
- Configurable API authentication
- Persistent configuration and database storage

## Installation

1. Open **Community Applications** in Unraid.
2. Search for **FinTV**.
3. Select the template and click Install.
4. Configure the required settings, including the API key and media paths.
5. Start the container.
6. Follow the setup instructions in the container template to install and configure the Jellyfin plugin.

## Requirements

- Unraid with Docker support
- A running Jellyfin server
- Access to the media directories used by Jellyfin
- NVIDIA GPU and the Unraid Nvidia Driver plugin (optional, for NVENC encoding)

## Support

For installation issues, questions, bug reports or suggestions, please open a GitHub Issue:

[Open an Issue](https://github.com/SolidProgramming/UnraidTemplates/issues)

## Project

FinTV is maintained by SolidProgramming.

The FinTV application source code is not publicly available.

## License

The templates in this repository are provided under the MIT License, unless otherwise specified.

---

Maintained by **SolidProgramming**.
