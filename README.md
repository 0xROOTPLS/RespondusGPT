# RespondusGPT
Screen capture + ChatGPT powered overylay while Respondus Lockdown Browser is active. 

## Status
Undetected as of 12/22/2025

## Usage

```
set OPENAI_API_KEY=sk-...
RespondusGPT.exe
```

## Hotkeys

| Key | Action |
|-----|--------|
| `Ctrl+Shift+Z` | Capture Respondus & analyze |
| `Ctrl+Shift+H` | Toggle overlay visibility |
| `Ctrl+Shift+R` | New overlay identity |
| `Ctrl+Shift+Q` | Quit |

## Evasion

- **Overlay**: DirectComposition renders at DWM compositor level, above normal z-order
- **Stealth**: Randomized window class names, decoy titles, no taskbar entry

## Screenshots

![Alt text](https://i.ibb.co/NgtPs4Dh/Respondus-GPT.png)
