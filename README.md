<div align="center">

<a href="https://github.com/SysikNagibator/AiPC">
  <img src="assets/aipc_3d.png" alt="AiPC by SYSIK" width="100%"/>
</a>

# SYSIK

**Give the agent "this" — and it gets a real PC.**

[![AiPC](https://img.shields.io/badge/project-AiPC-2250ff?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SysikNagibator/AiPC)
[![tools](https://img.shields.io/badge/tools-70-2250ff?style=for-the-badge)](https://github.com/SysikNagibator/AiPC)
[![platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-0a1a8a?style=for-the-badge)](https://github.com/SysikNagibator/AiPC)
[![Telegram](https://img.shields.io/badge/Telegram-@sysgood-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/sysgood)

</div>

---

## Contents

- [What I build](#what-i-build)
- [Featured: AiPC](#featured-aipc)
- [How it works](#how-it-works)
- [Quick start](#quick-start)
- [Stack](#stack)
- [Stats](#stats)
- [Contact](#contact)

---

## What I build

Tools that let AI agents do real work on a real computer. Local-first, open standards, no magic: the agent looks at the screen, acts, and verifies every step.

| Focus | What it means |
| ----- | ------------- |
| Agent tooling | MCP servers, native tool calls, structured errors |
| Automation | Screen, mouse, keyboard, browser, files, terminal, SSH |
| Safety | `ask` / `auto` / `read-only` modes enforced server-side |
| Open source | MIT, built in public |

---

## Featured: AiPC

[![AiPC](https://img.shields.io/github/stars/SysikNagibator/AiPC?style=for-the-badge&color=2250ff&logo=github&label=stars)](https://github.com/SysikNagibator/AiPC)
[![release](https://img.shields.io/github/v/release/SysikNagibator/AiPC?style=for-the-badge&color=2250ff&label=release)](https://github.com/SysikNagibator/AiPC/releases)
[![license](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)](https://github.com/SysikNagibator/AiPC/blob/main/LICENSE)

**AiPC** is a local service and console utility that gives any AI agent full access to your computer over the open **MCP** (Model Context Protocol) standard. The agent stops being "text in a chat" and starts working like a human at the PC.

| Usual agent limits | With AiPC |
| ------------------ | --------- |
| Blind: no screen | `screen_see` — screenshot as a native image block |
| Clicks by guessing | `ui_snapshot` / `ui_find` — ready-made coordinates |
| Typing into the void | `focus_type` — verified focus, refuses to type blind |
| Sleeps and hopes | `wait_for_window` / `wait_for_ui_element` / `wait_for_change` |
| "Did it work?" unknown | `screenshot_diff`, `assert_ui`, `audit.log` |
| No machine access | Files, terminal, processes, SSH/SFTP, browser, clipboard |

**[Read the full README](https://github.com/SysikNagibator/AiPC#readme)** · [Releases](https://github.com/SysikNagibator/AiPC/releases) · [Changelog](https://github.com/SysikNagibator/AiPC/blob/main/CHANGELOG.md)

---

## How it works

```
[ Agent in any IDE ] --MCP/stdio--> [ AiPC-Core: one local service ]
                                            |
        +------------------+----------------+------------------+
        |                  |                |                  |
      Vision            Control          Browser           System/Net
   screenshots,      mouse+keyboard,  your Chrome via    files, terminal,
   UI tree,           apps,            CDP + history,     processes, SSH,
   windows            clipboard        JS eval           search, sysinfo
```

Agent loop: **see (`screen_see`) → do → re-see to verify.**

---

## Quick start

| Step | What to do |
| ---- | ---------- |
| 1 | Download the latest build from [Releases](https://github.com/SysikNagibator/AiPC/releases) and run it |
| 2 | First run sets everything up itself: installs, adds the `aipc` command, registers MCP in your IDEs |
| 3 | Refresh MCP servers in your IDE and give the agent a plain-language task |

```
look at my screen, what is this error?
open YouTube and find a review of ...
connect via SSH to 192.168.1.10 and fetch yesterday's log
```

> AiPC is for personal automation and testing on your own machine. Do not use it for unauthorized access.

---

## Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,js,ts,react,nodejs,html,css,git,docker,linux,vscode,figma&theme=dark&perline=6" alt="Tech stack"/>
</div>

---

## Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SysikNagibator&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true&bg_color=050d33&title_color=5f8cff&icon_color=2250ff&text_color=c9d6ff" height="180" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SysikNagibator&layout=compact&theme=dark&hide_border=true&bg_color=050d33&title_color=5f8cff&text_color=c9d6ff&langs_count=8" height="180" alt="Top languages"/>
</div>

---

## Contact

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-@sysgood-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/sysgood)
[![GitHub](https://img.shields.io/badge/GitHub-SysikNagibator-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SysikNagibator)
[![Followers](https://img.shields.io/github/followers/SysikNagibator?label=followers&style=for-the-badge&color=2250ff&logo=github)](https://github.com/SysikNagibator)
[![Views](https://komarev.com/ghpvc/?username=SysikNagibator&label=profile+views&color=2250ff&style=for-the-badge)](https://github.com/SysikNagibator)

</div>

<div align="center">
  <sub>by SYSIK</sub>
</div>
