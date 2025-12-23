# RespondusGPT
Screen capture + ChatGPT powered overylay while Respondus Lockdown Browser is active. 

## Status
Undetected as of 12/22/2025  
https://www.virustotal.com/gui/file/f92b6c59bcc54ddccc98147ada21b51618b16d6983cf9ffa4e615850a3170629  
FILE HASH: f92b6c59bcc54ddccc98147ada21b51618b16d6983cf9ffa4e615850a3170629

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
