# Blogcast Audio Forge

**Blogcast Audio Forge** is a modern web application designed to transform written blog content into high-quality audio podcasts using advanced AI technology. Built with a focus on user experience and performance, it leverages the power of ElevenLabs for audio synthesis and Supabase for a robust backend.

## 🚀 Features

- **AI-Powered Audio Generation**: Convert text to lifelike speech using the ElevenLabs API.
- **Modern User Interface**: A clean, responsive, and accessible UI built with Shadcn UI and Tailwind CSS.
- **Secure Authentication**: User management and authentication handled by Supabase.
- **Real-time Updates**: Fast and reactive experience powered by React and Vite.

## 🛠️ Tech Stack

- **Frontend**: [React](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/), [Shadcn UI](https://ui.shadcn.com/)
- **Backend & Auth**: [Supabase](https://supabase.com/)
- **AI Audio**: [ElevenLabs](https://elevenlabs.io/)
- **State Management & Data Fetching**: [TanStack Query](https://tanstack.com/query/latest)

## 🏁 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/UDaygupta12512/Podcast-Generation.git
    cd Podcast-Generation
    ```

2.  **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Environment Configuration**
    Create a `.env` file in the root directory and add your Supabase credentials. You might also need ElevenLabs keys depending on the configuration.

    ```env
    VITE_SUPABASE_URL=your_supabase_url
    VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_anon_key
    ```

4.  **Run the development server**
    ```bash
    npm run dev
    ```

    Open [http://localhost:8080](http://localhost:8080) (or the port shown in your terminal) to view it in the browser.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.
