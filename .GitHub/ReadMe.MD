<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24,30&height=230&section=header&text=ShrutixMusic&fontSize=68&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Next-gen%20Telegram%20Voice%20Chat%20Music%20Engine&descAlignY=60&descSize=18" width="100%" alt="ShrutixMusic"/>

<a href="https://github.com/NoxxOP/ShrutixMusic">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=00E5FF&center=true&vCenter=true&width=700&lines=Rich+message+player+with+live+colored+controls;Autoplay+that+never+lets+the+vibe+die;Multi+assistant+voice+chat+streaming;Deploy+in+minutes+on+Heroku%2C+Render+or+VPS" alt="Typing SVG"/>
</a>

<br/>

<img src="https://raw.githubusercontent.com/NoxxOP/ShrutixMusic/main/ShrutixMusic/assets/ShrutixMusic.png" width="420" alt="ShrutixMusic Logo"/>

<br/><br/>

<a href="https://t.me/ShrutiBots"><img src="https://img.shields.io/badge/Channel-ShrutiBots-00E5FF?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0b0f1a" alt="Channel"/></a>
<a href="https://t.me/ShrutiSupportChat"><img src="https://img.shields.io/badge/Support-Chat-7C4DFF?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0b0f1a" alt="Support"/></a>
<a href="https://t.me/WTF_WhyMeeh"><img src="https://img.shields.io/badge/Owner-Nand-FF4081?style=for-the-badge&logo=telegram&logoColor=white&labelColor=0b0f1a" alt="Owner"/></a>

<br/>

<img src="https://img.shields.io/github/stars/NoxxOP/ShrutixMusic?style=flat-square&color=00E5FF&labelColor=0b0f1a" alt="Stars"/>
<img src="https://img.shields.io/github/forks/NoxxOP/ShrutixMusic?style=flat-square&color=7C4DFF&labelColor=0b0f1a" alt="Forks"/>
<img src="https://img.shields.io/github/issues/NoxxOP/ShrutixMusic?style=flat-square&color=FF4081&labelColor=0b0f1a" alt="Issues"/>
<img src="https://img.shields.io/github/last-commit/NoxxOP/ShrutixMusic?style=flat-square&color=00E676&labelColor=0b0f1a" alt="Last Commit"/>
<img src="https://img.shields.io/github/repo-size/NoxxOP/ShrutixMusic?style=flat-square&color=FFC400&labelColor=0b0f1a" alt="Repo Size"/>

</div>

<br/>

## ⚡ System Overview

```text
┌──────────────────────────────────────────────────────────────┐
│  ENGINE      Kurigram  +  PyTgCalls 0.9.7                    │
│  RUNTIME     Python 3.11  ·  uvloop  ·  FFmpeg               │
│  DATABASE    MongoDB (Motor, fully async)                    │
│  AUDIO       ShrutiBots API download chain + yt-dlp          │
│  ASSISTANTS  Up to 5 userbot accounts, auto balanced         │
│  LANGUAGES   English · Hindi · Punjabi · Arabic              │
│  DEPLOY      Heroku · Render · Docker · VPS                  │
└──────────────────────────────────────────────────────────────┘
```

<br/>

## 🧬 Core Features

<table>
<tr>
<td width="50%" valign="top">

### 🎛️ Rich Message Player
Now playing panel is a native rich message, not a plain caption with inline keys.

- Live progress bar that updates in place
- Replay, Pause/Resume, Skip and Queue controls
- Controls change color on every progress tick
- Queue count shown right on the button
- Queued songs get a Play Now / Skip / End panel

</td>
<td width="50%" valign="top">

### 🔁 Autoplay Engine
Queue ran out? The bot keeps the music going.

- Picks related tracks automatically
- Admin toggle with `/autoplay`
- Retry aware, survives slow API responses
- Works together with loop and shuffle

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎧 Playback Control
- Pause, resume, skip, end
- Seek forward and backward
- Speed from 0.5x to 2.0x
- Loop modes and queue shuffle
- Channel play for linked channels
- Audio and video streaming

</td>
<td width="50%" valign="top">

### 🌐 Sources
- YouTube search, links and playlists
- Spotify tracks, albums, playlists, artists
- Apple Music and Resso links
- SoundCloud links
- Telegram audio and video files
- Live streams and M3U8 or index links

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ✨ Polished Private Chat
- Random message effects on start, help and ping
- Two page paginated help menu
- Colored inline buttons on key panels
- Clean YouTube style thumbnails, no heavy edits

</td>
<td width="50%" valign="top">

### 🛡️ Control Room
- Sudo users, gban, block and chat blacklist
- Maintenance mode and auto end
- Broadcast, logger and live logs
- Active voice and video chat monitor
- Stats, speedtest, git update and restart

</td>
</tr>
</table>

<br/>

## 🎮 Command Deck

| Zone | Commands |
|:--|:--|
| **Play** | `/play` `/vplay` `/cplay` `/cvplay` `/playforce` `/vplayforce` |
| **Control** | `/pause` `/resume` `/skip` `/end` `/seek` `/seekback` `/speed` `/loop` `/shuffle` `/autoplay` |
| **Queue** | `/queue` `/player` `/playing` |
| **Setup** | `/playmode` `/channelplay` `/auth` `/unauth` `/authlist` `/settings` `/language` |
| **Tools** | `/song` `/ping` `/stats` `/speedtest` `/reload` `/reboot` |
| **Sudo** | `/broadcast` `/gban` `/block` `/blchat` `/maintenance` `/logger` `/autoend` `/addsudo` `/delsudo` `/update` `/restart` |

Add `c` in front of a command to run it for the linked channel, for example `/cplay` and `/cskip`.
Full explanation of every command lives inside the bot under `/help`.

<br/>

## 🚀 One Click Deploy

<div align="center">

<a href="https://dashboard.heroku.com/new?template=https://github.com/NoxxOP/ShrutixMusic"><img src="https://img.shields.io/badge/Deploy%20on-Heroku-7C4DFF?style=for-the-badge&logo=heroku&logoColor=white&labelColor=0b0f1a" alt="Heroku"/></a>
<a href="https://render.com/deploy?repo=https://github.com/NoxxOP/ShrutixMusic"><img src="https://img.shields.io/badge/Deploy%20on-Render-00E5FF?style=for-the-badge&logo=render&logoColor=white&labelColor=0b0f1a" alt="Render"/></a>

</div>

<br/>

## 🔐 Environment Variables

**Required**

| Variable | What it is |
|:--|:--|
| `API_ID` and `API_HASH` | From [my.telegram.org](https://my.telegram.org) |
| `BOT_TOKEN` | From [@BotFather](https://t.me/BotFather) |
| `MONGO_DB_URI` | MongoDB connection string |
| `OWNER_ID` | Your Telegram user id |
| `LOGGER_ID` | Log group id, bot must be admin there |
| `STRING_SESSION` | Pyrogram v2 session string of the assistant account |
| `SHRUTI_API_KEY` | Key from [@SHRUTIAPIBOT](https://t.me/SHRUTIAPIBOT) |
| `SHRUTI_API_URL` | Defaults to `https://api.shrutibots.site` |

**Optional**

| Variable | Default | What it does |
|:--|:--|:--|
| `STRING_SESSION2` to `STRING_SESSION5` | empty | Extra assistants for more groups |
| `DURATION_LIMIT` | `60` | Max track length in minutes |
| `PLAYLIST_FETCH_LIMIT` | `25` | Max tracks pulled from a playlist |
| `TG_AUDIO_FILESIZE_LIMIT` and `TG_VIDEO_FILESIZE_LIMIT` | built in | Telegram file size caps |
| `SPOTIFY_CLIENT_ID` and `SPOTIFY_CLIENT_SECRET` | empty | Enables Spotify links |
| `SUPPORT_CHANNEL` and `SUPPORT_CHAT` | ShrutiBots links | Buttons shown in the bot |
| `UPSTREAM_REPO` and `UPSTREAM_BRANCH` | this repo, `main` | Source for `/update` |
| `GIT_TOKEN` | empty | Needed for private upstream repos |
| `HEROKU_API_KEY` and `HEROKU_APP_NAME` | empty | Lets the bot restart and update on Heroku |

<br/>

## 🖥️ VPS Setup

```bash
sudo apt-get update && sudo apt-get install -y python3 python3-pip python3-venv git ffmpeg screen
git clone https://github.com/NoxxOP/ShrutixMusic
cd ShrutixMusic
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
nano .env
```

Run it in a detached session:

```bash
screen -S shruti
bash start
```

Or run it as a service:

```ini
[Unit]
Description=ShrutixMusic
After=network.target

[Service]
WorkingDirectory=/home/ubuntu/ShrutixMusic
ExecStart=/home/ubuntu/ShrutixMusic/venv/bin/python -m ShrutixMusic
Restart=always
RestartSec=5

[Install]
WantedBy=multi-user.target
```

```bash
sudo systemctl daemon-reload
sudo systemctl enable --now shrutixmusic
journalctl -u shrutixmusic -f
```

**Docker**

```bash
docker build -t shrutixmusic .
docker run -d --name shrutixmusic --env-file .env shrutixmusic
```

<br/>

## 🗂️ Project Map

```text
ShrutixMusic
├── ShrutixMusic
│   ├── core          bot, userbot, call engine, mongo, git
│   ├── platforms     YouTube, Spotify, Apple, Resso, SoundCloud, Telegram
│   ├── plugins
│   │   ├── admins    pause, resume, skip, seek, speed, loop, shuffle, autoplay
│   │   ├── bot       start, help, settings, inline, group logs
│   │   ├── play      play, channel play, live, play mode
│   │   ├── sudo      gban, block, blacklist, maintenance, logger, restart
│   │   ├── tools     ping, stats, queue, song, language, speedtest
│   │   └── misc      broadcast, autoleave, watcher, seeker
│   └── utils         rich stream, inline keyboards, thumbnails, stream engine
├── strings           helpers and language files
├── config.py
├── Dockerfile
└── start
```

<br/>

## 🛠️ Troubleshooting

| Problem | Fix |
|:--|:--|
| Assistant will not join | Start a voice chat in the group first and make sure the assistant is not banned there |
| Silence while playing | Run `ffmpeg -version` and install FFmpeg if it is missing |
| Songs fail to fetch | Check `SHRUTI_API_KEY` and `SHRUTI_API_URL` |
| Bot is online but silent | Verify `MONGO_DB_URI` and that your IP is whitelisted in Atlas |
| Stuck after a crash | Send `/reboot` in the group, then play again |

<br/>

## 🤝 Contributing

Bugs, ideas and pull requests are welcome. Open an issue first for big changes so we can talk it through.

<br/>

## 📜 License and Credits

This project follows the terms in [LICENSE](LICENSE). In short, it is free for personal and educational use, credits and the original repository link must stay in every fork, and reselling or rebranding is not allowed.

Built with Kurigram, PyTgCalls, yt-dlp, FFmpeg, Motor and aiohttp.

<div align="center">

**Created and maintained by [Nand Yaduwanshi](https://github.com/NoxxOP)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24,30&height=120&section=footer" width="100%" alt="footer"/>

</div>
