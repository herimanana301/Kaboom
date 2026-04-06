# 💥 Kaboom

**Kaboom** is an open-source desktop application designed to radically simplify the local deployment of popular open-source software.

Powered by **Tauri** and **Rust**, it allows you to launch local instances of **Supabase**, **n8n**, **Appwrite**, and more with a single click—no manual YAML editing or complex Docker networking required.

---

## ✨ Key Features

* **One-Click Deployment:** Start complex stacks (like Supabase and its 10+ containers) in seconds.
* **Ultra-Lightweight:** Built with **Tauri & Rust**, the app uses minimal system resources (unlike Electron-based apps).
* **Port Conflict Management:** Automatically detects occupied ports (e.g., Postgres on 5432) and suggests alternatives.
* **Real-time Logs:** Stream container output directly within the app interface.
* **Native Persistence:** Your data stays on your machine, organized and ready for your next dev session.

---

## 🛠️ Supported Services (MVP)

| Service | Category | Description |
| :--- | :--- | :--- |
| **Supabase** | Backend-as-a-Service | The open-source Firebase alternative (Postgres, Auth, Realtime). |
| **n8n** | Automation | Self-hosted workflow automation tool. |
| **Appwrite** | Backend-as-a-Service | Unified platform for Web, Mobile, and Flutter developers. |
| **Strapi** | Headless CMS | The leading open-source Headless CMS. |

---

## 🏗️ Technical Stack

* **Framework:** [Tauri](https://tauri.app/) (React/Tailwind Frontend).
* **Backend:** [Rust](https://www.rust-lang.org/) for performance and system-level security.
* **Engine:** [Bollard](https://github.com/fussybeaver/bollard) (Asynchronous Docker API client for Rust).
* **Communication:** Tauri events for streaming logs and container health status.

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

> **Note:** This project is an independent community-led tool and is **not officially affiliated**, associated, authorized, endorsed by, or in any way officially connected with the projects listed above (**Supabase**, **n8n**, etc.). All product and company names are trademarks™ or registered® trademarks of their respective holders.
