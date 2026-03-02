# Faelans Space

A set of web-based tools for Minecraft Bedrock Edition and general audio processing. Everything runs directly in your browser using plain JavaScript

## Minecraft Tools

*   **Schematic Converter**: Take your Java Edition schematics (.schematic, .schem, .litematic) and bring them into Bedrock Edition. Supports hollowing, block replacement, and various transformations.
*   **World Region Converter**: Extract and convert specific areas from Java world saves directly into Bedrock (non world)formats.
*   **Scoreboard Builder**: A visual editor for creating titleraw displays with support for color codes and formatting.
*   **Addons**: A collection of my Bedrock addons focused on server utilities and creative tools.

## Audio Tools

*   **Format Converter**: Convert between MP3 and WAV with full control over bitrate, sample rate, and channels.
*   **Metadata Editor**: Clean up or customize track info, including ID3 tags and album artwork.
*   **Volume & Cropping**: Normalize audio levels or trim tracks with fade-in/out controls.
*   **Music Player**: A built-in player to check out some of my original releases.

## Tech Stuff

*   **Frontend**: Vanilla HTML/JS with Tailwind CSS for styling.
*   **Libraries**: 
    *   `pako` for NBT decompression.
    *   `JSZip` for handling .mcpack and world files.
    *   `lamejs` for MP3 encoding.
    *   Web Audio API for all the sound processing.

## Running Locally

A simple Node.js server script is included if you prefer to run locally:
(uses port 5000)
node server.js

