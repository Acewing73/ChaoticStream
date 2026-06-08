# ChaoticStream (Working Title) 🎮

ChaoticStream is a free, open-source cross-platform desktop application (Windows & macOS) designed to cure "gamer paralysis." It acts as an automated quest generator, smart game launcher, and automated content-creation bridge for PC gamers.

Users select a pool of games they want to play, and with a single click, the app pulls their next unearned achievement from Steam, launches the game, and handles background recording and video uploading automatically.

---

## ✨ Features (The Vision)
* **Steam Integration:** Instantly fetches your local library and tracks locked vs. unlocked achievements.
* **The "Play Next" Randomizer:** Filters your games to find active titles and picks a random unearned achievement as your next "quest."
* **Automated Launching:** Boots up the selected game automatically via Steam URI protocols.
* **Zero-Effort Recording:** Connects to OBS Studio in the background to automatically start recording when the game starts, and stops when you exit.
* **Smart Uploads:** Automatically pushes your gameplay clip to YouTube or Twitch, auto-generating video titles using the game name and achievement data.

---

## 🛠️ Proposed Tech Stack
We want to keep the application lightweight, secure, and fully cross-platform.
* **Frontend / Desktop Wrapper:** [Tauri](https://tauri.app) (Preferred for its small footprint and security) or [Electron](https://electronjs.org).
* **Backend Automation:** Node.js or Python (for process monitoring, Steam API handling, and OBS WebSockets integration).
* **Integrations:** Steam Web API, OBS WebSockets, Twitch API, YouTube Data API.

---

## 🤝 How to Contribute
This is a 100% community-driven, open-source project. We are actively looking for contributors of all skill levels! 

We currently need help with:
* **Architecture & Backend:** Setting up the core process-monitoring script and Steam API handlers.
* **UI/UX Design:** Crafting a clean, modern interface for managing game pools and tracking active quests.
* **Documentation:** Refining setup guides and onboarding instructions.

### To get started:
1. **Join the Conversation:** (https://discord.gg/72GghsKk) to chat with the team.
2. **Check the Issues Tab:** Look for tasks tagged with `good first issue` or `help wanted`.
3. **Fork & PR:** Fork the repo, create your feature branch, and submit a Pull Request!

---

## 💖 Funding & Donations
We believe this tool should always be completely free and open-source. To ensure sustainability, we intend to set up transparent funding via **GitHub Sponsors** and **Open Collective**. 

All donations will go strictly toward:
* Project infrastructure and server costs (if any).
* Compensating core code maintainers and major contributors.

*Financial transparency reports will be publicly viewable via our funding platform.*

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# ChaoticStream
An app that randomizes games for either brief or somewhat hourly objectives of the games you have achievements you want to complete with the option of uploading the gameplay to your ideal streaming platform.
