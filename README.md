<img src="assets/aipc_banner.svg" alt="AiPC" width="100%">

<br>

# SYSIK

Разработчик. Делаю инструменты, которые дают ИИ-агентам рабочий доступ к настоящему компьютеру.

<img src="assets/divider.svg" width="100%" alt="">

<table>
<tr>
<td width="64"><img src="assets/work.svg" width="48" alt=""></td>
<td><b>Работаю над</b><br>Новыми проектами</td>
<td width="64"><img src="assets/learning.svg" width="48" alt=""></td>
<td><b>Изучаю</b><br>Новые технологии</td>
<td width="64"><img src="assets/collab.svg" width="48" alt=""></td>
<td><b>Открыт к</b><br>Сотрудничеству</td>
</tr>
<tr>
<td><img src="assets/ask.svg" width="48" alt=""></td>
<td><b>Спроси меня</b><br>О чём угодно</td>
<td><img src="assets/fun.svg" width="48" alt=""></td>
<td><b>Фан-факт</b><br>Just me</td>
<td><img src="assets/contact.svg" width="48" alt=""></td>
<td><b>Связаться</b><br>Ссылки ниже</td>
</tr>
</table>

<img src="assets/divider.svg" width="100%" alt="">

## Стек

![JavaScript](https://img.shields.io/badge/JavaScript-222?style=flat-square&labelColor=222) ![TypeScript](https://img.shields.io/badge/TypeScript-222?style=flat-square&labelColor=222) ![Python](https://img.shields.io/badge/Python-222?style=flat-square&labelColor=222) ![React](https://img.shields.io/badge/React-222?style=flat-square&labelColor=222) ![Node.js](https://img.shields.io/badge/Node.js-222?style=flat-square&labelColor=222) ![Docker](https://img.shields.io/badge/Docker-222?style=flat-square&labelColor=222) ![Linux](https://img.shields.io/badge/Linux-222?style=flat-square&labelColor=222) ![Git](https://img.shields.io/badge/Git-222?style=flat-square&labelColor=222)

---

## Что я делаю

Инструменты, с которыми ИИ-агенты выполняют реальную работу на реальном компьютере. Локально, на открытых стандартах: агент смотрит на экран, действует и проверяет каждый шаг.

| Направление   | Что это                                                 |
| ------------- | ------------------------------------------------------- |
| Agent tooling | MCP-серверы, нативные вызовы инструментов, ошибки       |
| Automation    | Экран, мышь, клавиатура, браузер, файлы, терминал, SSH  |
| Safety        | Режимы `ask` / `auto` / `read-only` на стороне сервера  |
| Open source   | MIT, разработка в открытую                              |

---

## AiPC

[<img src="assets/aipc_banner.svg" alt="AiPC" width="100%">](https://github.com/SysikNagibator/AiPC)

![stars](https://img.shields.io/github/stars/SysikNagibator/AiPC?style=flat-square&labelColor=222&color=444) ![release](https://img.shields.io/github/v/release/SysikNagibator/AiPC?style=flat-square&labelColor=222&color=444) ![license](https://img.shields.io/badge/license-MIT-444?style=flat-square&labelColor=222)

**AiPC** — локальный сервис и консольная утилита, которая даёт любому ИИ-агенту полный доступ к компьютеру по открытому стандарту **MCP** (Model Context Protocol). Агент перестаёт быть «текстом в чате» и работает как человек за ПК.

| Обычные ограничения агента | С AiPC                                                        |
| -------------------------- | ------------------------------------------------------------- |
| Нет экрана                 | `screen_see` — скриншот как нативный image-блок               |
| Клики наугад               | `ui_snapshot` / `ui_find` — готовые координаты                |
| Печать в пустоту           | `focus_type` — проверенный фокус, не печатает вслепую         |
| Спит и надеется            | `wait_for_window` / `wait_for_ui_element` / `wait_for_change` |
| Сработало ли — неизвестно  | `screenshot_diff`, `assert_ui`, `audit.log`                   |
| Нет доступа к машине       | Файлы, терминал, процессы, SSH/SFTP, браузер, буфер обмена    |

[Полный README](https://github.com/SysikNagibator/AiPC#readme) · [Релизы](https://github.com/SysikNagibator/AiPC/releases) · [Changelog](https://github.com/SysikNagibator/AiPC/blob/main/CHANGELOG.md)

```
[ Агент в любой IDE ] --MCP/stdio--> [ AiPC-Core: один локальный сервис ]
                                              |
          +------------------+----------------+------------------+
          |                  |                |                  |
        Vision            Control          Browser           System/Net
     скриншоты,         мышь+клавиши,     ваш Chrome      файлы, терминал,
     дерево UI,         приложения,       через CDP,      процессы, SSH,
     окна               буфер обмена      JS eval         поиск, sysinfo
```

Цикл агента: **see (`screen_see`) → do → re-see для проверки.**

> AiPC предназначен для личной автоматизации и тестирования на вашей машине. Не используйте для несанкционированного доступа.

<img src="assets/divider.svg" width="100%" alt="">

## Статистика

![GitHub stats](https://github-readme-stats.vercel.app/api?username=SysikNagibator&show_icons=true&count_private=true&include_all_commits=true&bg_color=0A0A0A&title_color=E6E6E6&text_color=A8A8A8&icon_color=6B6B6B&border_color=2E2E2E&border_radius=6) ![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=SysikNagibator&layout=compact&langs_count=8&bg_color=0A0A0A&title_color=E6E6E6&text_color=A8A8A8&border_color=2E2E2E&border_radius=6)

![Streak](https://github-readme-streak-stats.herokuapp.com/?user=SysikNagibator&background=0A0A0A&border=2E2E2E&stroke=2E2E2E&ring=A8A8A8&fire=A8A8A8&currStreakNum=E6E6E6&sideNums=E6E6E6&currStreakLabel=A8A8A8&sideLabels=A8A8A8&dates=6B6B6B&borderRadius=6)

![Activity](https://github-readme-activity-graph.vercel.app/graph?username=SysikNagibator&bg_color=0A0A0A&color=A8A8A8&line=A8A8A8&point=E6E6E6&area=true&area_color=2E2E2E&hide_border=true)

<img src="assets/divider.svg" width="100%" alt="">

## Контакты

[![Telegram](https://img.shields.io/badge/Telegram-@sysgood-222?style=flat-square&logo=telegram&logoColor=white&labelColor=222)](https://t.me/sysgood) [![GitHub](https://img.shields.io/badge/GitHub-SysikNagibator-222?style=flat-square&logo=github&logoColor=white&labelColor=222)](https://github.com/SysikNagibator)

![Views](https://komarev.com/ghpvc/?username=SysikNagibator&label=views&color=444&style=flat-square)
