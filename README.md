<div align="center">
  <img src="public/logo.png" alt="Rabbit Base Logo" width="120" />
  <h1>Rabbit Base 🐰</h1>
  <p><strong>A tactical dashboard for open-source bounty hunters.</strong></p>
</div>

---

## 🎯 About The Project

**Rabbit Base** is an open-source contribution tracking and planning tool built for developers looking to dive into the open-source "warren". With a distinct brutalist design aesthetic, it acts as your personal command center to track repositories, hunt down "Good First Issues", and get AI-powered tactical roadmaps for contributing.

### ✨ Core Features
*   **The Bounty Board**: Track target organizations and repositories locally or privately in your "Stealth Safehouse".
*   **AI Tactical Roadmaps**: Integrates with the **Google Gemini API** to generate punchy, 3-step action plans for contributing to specific repositories based on your goals (e.g., Bug Hunting, Architecture Setup).
*   **Supabase Authentication**: Secure user login and personalized dashboard data storage.
*   **Brutalist UI**: A striking, high-contrast, brutalist design language for a unique user experience.
*   **Markdown Rendering**: AI mission briefings are parsed and rendered in clean markdown.

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

## 🌐 Deployment

This project is configured to deploy automatically to **GitHub Pages** via GitHub Actions.

1.  Ensure your repository is named exactly `<username>.github.io` (or `<organization>.github.io`).
2.  Go to your repository **Settings > Pages**.
3.  Set the **Source** to **GitHub Actions**.
4.  Push your changes to the `main` branch. The `.github/workflows/deploy.yml` workflow will automatically build and publish the site.

*(Note: Don't forget to update your Supabase **Site URL** and **Redirect URLs** to match your live GitHub Pages domain!)*

---

<div align="center">
  <i>Built for the Burrow. Happy hunting! ⚔️</i>
</div>
