PAL Assembly Highlighter
========================
VS Code extension that adds syntax highlighting for the PDP-8's PAL Assesmbly
language. This includes both PAL-III and PAL-D.

Installation
------------
Manual installation is required for this extension:

1. Download the latest `.vsix` release from the Releases tab on github.
2. Install in VS Code: *Extensions* > *View More and Actions* > *Install from VSIX*

or

1. Download the latest .zip of the source from the Release tab.
2. Unzip to VS Code's extension folder (not a sub directory)
    - Windows:  `%USERPROFILE%\.vscode\extensions`
    - macOS:    `~/.vscode/extensions`
    - Linux:    `~/.vscode/extensions`

Usage
-----
This extension associates with `.pa`, `.PA`, `.pal`, `.s`, `.S`, and `.asm`
file extensions. Open a file with this extension or select **PAL Assembly** as
the language. The `.pa` or `.PA` was the extension that was orignally used on
OS/8, the PDP-8's operating system. However, this conflicts with PulseAudio
config files (and probably others). Luckily, I use Pipewire.

Copying
-------
Copyright &copy; 2024 Rex McKinnon \
This software is available for free under the permissive University of
Illinois/NCSA Open Source License. See the LICENSE file for full details.
