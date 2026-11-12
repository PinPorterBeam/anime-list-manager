
<div align="center">

# Anime List Manager

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&size=22&duration=2800&pause=900&color=0077B6&center=true&vCenter=true&width=800&lines=Never+forget+what+episode+you%27re+on.;Rate%2C+review%2C+and+organize.;Your+ultimate+anime+database." alt="Typing SVG"/>

<br/><br/>

<a href="https://share.google/SGR1TXVGpTS9q4rQn">
  <img src="https://img.shields.io/badge/🚀_LIVE_APP-0077B6?style=for-the-badge&logo=vercel&logoColor=white&labelColor=023E8A" height="50"/>
</a>
&nbsp;
<a href="https://share.google/SGR1TXVGpTS9q4rQn">
  <img src="https://img.shields.io/badge/📥_SOURCE_CODE-00B4D8?style=for-the-badge&logo=github&logoColor=white&labelColor=0096C7" height="50"/>
</a>
&nbsp;
<a href="https://share.google/SGR1TXVGpTS9q4rQn">
  <img src="https://img.shields.io/badge/📚_DOCS-90E0EF?style=for-the-badge&logo=readthedocs&logoColor=black&labelColor=48CAE4" height="50"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/version-2.5.1-023E8A?style=flat-square&logo=semanticrelease&logoColor=white"/>
<img src="https://img.shields.io/badge/Next.js-14+-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/license-MIT-0077B6?style=flat-square&logo=opensourceinitiative&logoColor=white"/>
<img src="https://img.shields.io/badge/downloads-41K%2B-00B4D8?style=flat-square&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/status-stable-90E0EF?style=flat-square&logo=checkmarx&logoColor=black"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🌊 Your Personal Anime Database

**Anime List Manager** is a sleek, modern web application designed for anime enthusiasts who want total control over their watch history. Tired of forgetting which episode you paused on, or losing track of that hidden gem you meant to watch? This app solves it all with a beautiful, lightning-fast interface.

Built with a modern tech stack (Next.js + TypeScript), it allows you to seamlessly search for thousands of anime, categorize them into custom lists (Watching, Completed, Plan to Watch, Dropped), and log your episode progress down to the exact minute. It’s not just a tracker; it’s a complete dashboard for your anime lifestyle.

> 💡 **Why use Anime List Manager?** Because keeping a messy Notes app or an Excel spreadsheet is a thing of the past. Experience a stunning UI, detailed statistics, and instant synchronization across all your devices.

<br/>

<table align="center" width="100%">
<tr>
<td align="center" width="25%">

### 📺
**Episode Tracking**
Log your exact progress with a single click. Never lose your place again.

</td>
<td align="center" width="25%">

### 📊
**Deep Statistics**
View charts of your watch time, top genres, and completed series.

</td>
<td align="center" width="25%">

### 🎨
**Beautiful UI**
A fluid, responsive, and glassmorphic design that looks great on any device.

</td>
<td align="center" width="25%">

### 🔄
**Cloud Sync**
Your data is securely stored and synced instantly across all devices.

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚡ Why This App Stands Out

<div align="center">

| 🧩 **The Challenge** | 💡 **Our Solution** | 📈 **The Result** |
|:---|:---|:---|
| Spreadsheets are tedious and ugly | **Beautiful, intuitive UI** with drag-and-drop lists | Manage your anime with joy, not chores |
| Forgetting which episode you're on | **Smart progress tracking** with auto-increment | Never re-watch a filler episode by mistake |
| No idea how much time you've spent watching | **Advanced analytics dashboard** | Discover your true anime addiction level |
| Missing release dates for new episodes | **Automated airing schedule** integration | Get notified exactly when a new episode drops |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Core Features

<div align="center">

| 🔍 **Instant Search** | 📝 **Custom Lists** | ⭐ **Rating System** |
|:---:|:---:|:---:|
| Fuzzy search powered by the Jikan API | Create custom categories beyond the defaults | Rate anime from 1 to 10 with star half-points |

| 📅 **Airing Calendar** | 📈 **Stats Dashboard** | 🌙 **Dark Mode** |
|:---:|:---:|:---:|
| Track upcoming episodes for currently airing shows | See total hours watched, mean score, and more | A gorgeous, hand-crafted dark theme |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🖼️ App Dashboard Preview

<img width="1920" height="1199" alt="desktop" src="https://github.com/user-attachments/assets/99bde2cf-9ea2-4dc4-89fd-78293f7ad1b3" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🚀 Quick Start

> **Three commands. Under two minutes. No installers.**

### 1️⃣ Clone and install dependencies

```bash
git clone https://github.com/yourname/anime-list-manager.git
cd anime-list-manager
npm install
```

### 2️⃣ Set up environment variables

```bash
cp .env.example .env.local
# Add your database URL and Jikan API keys here
```

### 3️⃣ Run the development server

```bash
npm run dev
```

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⌨️ Tech Stack & Architecture

<div align="center">

| Layer | Responsibility | Tech |
|:---|:---|:---|
| 🎨 **Frontend** | Interactive UI, state management, routing | `Next.js 14 (App Router)` |
| 🗄️ **Database** | Storing user lists, ratings, and progress | `PostgreSQL` + `Prisma` |
| 🔌 **External API** | Fetching anime metadata, images, and schedules | `Jikan API (MyAnimeList)` |
| 🔐 **Auth** | Secure user login and session management | `NextAuth.js` |

</div>

The application is built with a component-driven architecture. It uses Server Components for fast initial loads and Client Components for interactive elements (like the episode counter and drag-and-drop lists), ensuring the best of both worlds.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧠 Pro Tips

<table align="center" width="100%">
<tr>
<td width="50%">

**For power users**
- ⌨️ Use keyboard shortcuts to quickly mark episodes as watched
- 📊 Export your list to JSON for backup or migration
- 🌙 Toggle dark mode with `Ctrl + D`
- 🔍 Search by studio or year for better filtering

</td>
<td width="50%">

**For self-hosters**
- 🐳 A Docker Compose file is included for easy deployment
- 🚀 Host on Vercel for free (requires a PostgreSQL database)
- 🛡️ Protect your instance with basic auth
- 🔄 Set up cron jobs to sync airing schedules daily

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ❓ Frequently Asked Questions

<details>
<summary><b>Does it support MyAnimeList or AniList imports?</b></summary>

Yes! We have a built-in importer that allows you to upload your XML/JSON export from MyAnimeList or AniList to seamlessly migrate your entire library in seconds.
</details>

<details>
<summary><b>Is there a mobile app?</b></summary>

The web app is a **Progressive Web App (PWA)**, meaning you can install it directly to your home screen on iOS and Android for a native-like experience.
</details>

<details>
<summary><b>Where does the anime data come from?</b></summary>

All anime metadata, images, and schedules are pulled directly from the official **Jikan API**, which is an unofficial, free API for MyAnimeList.
</details>

<details>
<summary><b>Can I share my list with friends?</b></summary>

Absolutely. Every user gets a public profile URL where friends can view their completed anime and ratings without needing to log in.
</details>

<details>
<summary><b>How do I report a bug?</b></summary>

Open an issue on the GitHub repository. Include your browser version, a screenshot of the bug, and the steps to reproduce it.
</details>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License & Credits

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

<br/>

<div align="center">

<a href="https://share.google/SGR1TXVGpTS9q4rQn">
  <img src="https://img.shields.io/badge/🚀_LAUNCH_ANIME_MANAGER-0077B6?style=for-the-badge&logo=vercel&logoColor=white&labelColor=023E8A" height="55"/>
</a>

<br/><br/>

**⭐ If this app organized your watchlist — star the repo!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=4,19,28&height=140&section=footer&text=Track.+Organize.+Discover.&fontSize=22&fontColor=00B4D8" width="100%"/>

</div>
