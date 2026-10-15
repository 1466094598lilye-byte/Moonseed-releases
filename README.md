# Moonseed

One thing a day for your long project. Sow it in the morning, wrap up at night, and the days grow into a forest.

## Install (macOS)

Paste the whole block below into your AI agent — Claude Code, Codex, Gemini CLI, or the Code tab of the Claude app. It does the rest; you only approve its prompts.

    Install Moonseed for me and connect it to you.
    1. Make sure node 22 or newer is available. If not, download the official macOS build
       from nodejs.org into ~/Library/Application Support/Moonseed/node/ (no sudo; leave any
       node I already have alone).
    2. Download https://github.com/1466094598lilye-byte/Moonseed-releases/releases/latest/download/Moonseed.zip
       with curl, unzip it, put Moonseed.app in /Applications, open it once.
    3. Read ~/Library/Application Support/Moonseed/last-boot.json: "mcp.shim" is the command,
       "dataDir" is its only argument.
    4. Register that as a stdio MCP server named exactly "moonseed", for me as a user
       (not just this project), using your own configuration mechanism.
    5. Tell me whether I need to restart you.

## Updates

Moonseed updates itself. On launch it checks this repository and quietly installs any newer version. After an update, macOS may ask once more whether Moonseed may access your iCloud Drive. Please allow it: that folder is where your records live, and iCloud is how they follow you between Macs.

You may also see a prompt about your Downloads, Desktop, or Documents folder. That is the Claude Code command line, which names the relics, checking once at startup whether it can reach those folders. Moonseed itself never reads them, so allow or deny as you like; nothing changes either way.

## Disclaimer

Moonseed is vibe-coded: one person and an AI agent built it in conversation, and the AI wrote the code. It is shared as is, for people who want to try it. There is no server and no account; your records are plain files in your own iCloud Drive. Still, know what it is before you lean on it.
