# Second Brain 🧠

A privacy-focused, local-first knowledge management workspace that runs entirely in your browser. Organise your projects, manage deeply nested folder hierarchies, and render sandboxed HTML documents on the fly.

## 🚀 Key Features

* **100% Privacy & Local-First:** Your data never leaves your machine. Everything saves automatically to your browser's local storage.
* **Dynamic Folder Hierarchy:** Build infinite trees of folders and files. Clicking a folder recursively renders a structured preview of all contents inside it.
* **Sandboxed HTML Rendering:** Write or paste custom HTML documents. Code executes safely within secure, isolated frames.
* **Document Status Workflows:** Track your productivity by cycling file states through *To Do*, *In Progress*, and *Done*.
* **AI-Ready Integration:** Includes a "Copy for AI" action that formats your entire workspace into a clean JSON payload for LLM prompts.
* **Fully Portable Workspaces:** Export individual projects or your entire multi-project workspace as standardized JSON files.
* **Customisable UI Themes:** Personalise individual projects with built-in color presets or bespoke hex configurations.

## 🛠️ Tech Stack

* **Frontend:** Vanilla HTML5, CSS3 (using modern CSS variables), and ECMAScript Next JavaScript.
* **Storage:** Client-side Web Storage API (`localStorage`).
* **Dependencies:** None. Zero frameworks, zero external libraries, and zero build steps required.

## 📦 Getting Started

Because this application is a self-contained Single Page Application (SPA), deployment takes seconds.

### Option A: just use the hosted page on Github (https://kovarsk.github.io/2ndBrain/)

### Option B: Local Execution
1. Clone the repository: `git clone https://github.com`
2. Open `index.html` directly in any modern desktop web browser.

### Option C: Cloud Hosting (GitHub Pages)
1. Go to your GitHub repository **Settings** tab.
2. Navigate to **Pages** in the left sidebar.
3. Under **Build and deployment**, set the source to **Deploy from a branch**.
4. Select your branch (e.g., `main` or `master`) and folder (`/root`), then click **Save**.
5. Your application will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`.

## 📖 How Data Management Works

* **Automatic Backups:** The app continuously synchronises changes to `localStorage`.
* **Browser Data Caveat:** Clearing your browser cache or switching devices will wipe your local workspace. **Always use the "Export All" button regularly to download JSON backups.**
* **Migration:** If you swap machines, simply use the **Import JSON** button to load your backup file and pick up right where you left off.

## 📝 License

This project is open-source. Feel free to modify, fork, and adapt it for your own personal productivity workflows.
