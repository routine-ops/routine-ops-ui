# routine-ops-ui

**Next.js Frontend for Routine-Ops:** a user-friendly interface for daily checklists, cook instructions, and dietician dashboards.

## 🔧 Tech Stack
- **Framework:** Next.js 14
- **Language:** TypeScript
- **UI Library:** React + Tailwind CSS
- **State Management:** Zustand
- **Charts & Visuals:** Recharts
- **Authentication:** NextAuth.js
- **Icons:** lucide-react

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone git@github.com:routine-ops/routine-ops-ui.git
   cd routine-ops-ui
   ```
2. **Install dependencies**
   ```bash
   npm install
   ```
3. **Set up environment variables**
   - Copy `.env.local.example` to `.env.local` and fill in values:
     ```bash
     cp .env.local.example .env.local
     ```
4. **Run development server**
   ```bash
   npm run dev
   ```
5. **Build & Preview**
   ```bash
   npm run build
   npm start
   ```

## 📦 Deployment
- **Vercel:** Connect this repo to your Vercel account, set environment variables, and enable automatic deployments on push to `main`.

## 📁 Project Structure
```
├── public/             # Static assets (images, fonts)
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Next.js pages & API routes
│   ├── store/          # Zustand state management
│   ├── styles/         # Global and component styles
│   └── utils/          # Helper functions and hooks
├── .env.local.example  # Example environment variables
├── next.config.js      # Next.js configuration
└── tailwind.config.js  # Tailwind CSS configuration
```

## 🛠️ Features
- **Daily Checklist:** Interactive to-do list with real-time status updates.
- **Cook Instructions:** Step-by-step recipe guides formatted for cooks.
- **Dietician Dashboard:** Monthly overview, consistency reports, and user management tools.
- **Responsive Design:** Works on desktop, tablet, and mobile devices.

## 🤝 Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m "feat: add YourFeature"`.
4. Push to branch: `git push origin feature/YourFeature`.
5. Open a Pull Request against `main`.

For new tasks or feature requests, use our [Issue Form](.github/ISSUE_TEMPLATE/development.yml) to capture details.

## 📄 License
MIT © 2025 Routine-Ops Team
