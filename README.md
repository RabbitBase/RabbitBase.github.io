<div align="center">
  <img src="public/logo.png" alt="Rabbit Base Logo" width="120" />
  <h1>Rabbit Base</h1>
  <p><strong>A tactical dashboard for open-source bounty hunters.</strong></p>
  <p><a href="https://RabbitBase.github.io/"><strong>👉 View the Live Website 👈</strong></a></p>
</div>

---

## 🎯 About The Project

**Rabbit Base** is an open-source contribution tracking and planning tool built for developers looking to dive into the open-source "warren". It acts as your personal command center to track repositories, hunt down "Good First Issues", and get AI-powered tactical roadmaps for contributing.

### ✨ Core Features
*   **The Bounty Board**: Track target organizations and repositories locally or privately in your "Stealth Safehouse".
*   **AI Tactical Roadmaps**: Integrates with the **Google Gemini API** to generate punchy, 3-step action plans for contributing to specific repositories based on your goals (e.g., Bug Hunting, Architecture Setup).
*   **Supabase Authentication**: Secure user login and personalized dashboard data storage.
*   **Markdown Rendering**: AI mission briefings are parsed and rendered in clean markdown.

---

## 🗺️ How to Make Full Use of Rabbit Base

Rabbit Base is designed to streamline your open-source journey. Here is how you can use it to its full potential:

1. **Scout for Targets (The Bounty Board)** 
   Use the **Local Bounties** tab to track repositories you are interested in contributing to. Add the repository name and URL. This creates a centralized hit-list of projects you want to support.

2. **Generate Tactical Roadmaps**
   Once you've tracked a repository, select it from your list and choose a specific goal (like "First Good Issue" or "Bug Hunting"). Hit the **Generate AI Roadmap** button. Rabbit Base will use AI to decrypt the target and give you a punchy, 3-step mission briefing on exactly how to start contributing to that specific project.

3. **Utilize the Stealth Safehouse**
   Working on private repositories, unannounced features, or classified open-source zero-days? Use the **Safehouse** tab. Targets tracked here are strictly private to you, allowing you to generate AI roadmaps for sensitive projects without exposing them to the global dashboard.

4. **Level Up Your Agent**
   Use the roadmaps to actually make pull requests and contribute. As you conquer "Good First Issues", you'll gain the context needed to tackle larger architectural challenges in those same repositories!

---

## 🛠️ Built With

*   **[React](https://react.dev/)** - UI Framework
*   **[Vite](https://vitejs.dev/)** - Fast Frontend Tooling
*   **[Supabase](https://supabase.com/)** - Auth & Database
*   **[Google Gemini API](https://ai.google.dev/)** - Generative AI Roadmaps
*   **[React Router](https://reactrouter.com/)** - Client-side Routing
*   **[Lucide React](https://lucide.dev/)** - Iconography

---

## 🚀 Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

*   Node.js (v18 or higher recommended)
*   A Supabase Project
*   A Google Gemini API Key

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/RabbitBase/RabbitBase.github.io.git
    cd RabbitBase.github.io
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Environment Variables**
    Create a `.env.local` file in the root directory and add your API keys:
    ```env
    VITE_SUPABASE_URL=your_supabase_project_url
    VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
    VITE_GEMINI_API_KEY=your_gemini_api_key
    ```

4.  **Run the Development Server**
    ```bash
    npm run dev
    ```
    Your app should now be running on `http://localhost:5173`.

---

## 🤝 Contributing & Community

We love contributions! If you're looking to help out or get involved, please read through our community guidelines:

*   📖 **[Contributing Guidelines](CONTRIBUTING.md)**: Learn how to report bugs, suggest features, and submit pull requests.
*   🛡️ **[Security Policy](SECURITY.md)**: Find instructions on how to safely report security vulnerabilities.
*   🤝 **[Code of Conduct](CODE_OF_CONDUCT.md)**: Read our community standards and expectations.

---

<div align="center">
  <i>Built for the Burrow. Happy hunting! ⚔️</i>
</div>
