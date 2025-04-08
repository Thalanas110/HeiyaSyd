# HeiyaSyd — Poem Selector 🌸

HeiyaSyd is a simple yet charming React-based poem selector that presents a collection of 12 heartfelt poems. Designed for personal or creative use, this project offers a soft, artistic touch with minimalistic functionality and an elegant user interface.

> "A poem is a whisper from the soul. This app is a place for twelve."

## ✨ Features

- 🎴 Displays 12 different poems, each with unique emotion and theme
- 🌀 Random poem selector mechanism
- 💅 Aesthetic and minimal UI
- ⚛️ Built with React and Vite
- 🛠️ TypeScript support

## 📁 Project Structure

```
HeiyaSyd/
├── client/             # React frontend
│   ├── src/
│   │   ├── components/ # Reusable components
│   │   ├── poems.ts    # Array of 12 poems
│   │   └── App.tsx     # Main UI logic
├── public/             # Static assets
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm or yarn

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Thalanas110/HeiyaSyd.git
   cd HeiyaSyd
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Run the development server**:

   ```bash
   npm run dev
   ```

4. Visit [http://localhost:5173](http://localhost:5173) in your browser.

## 📝 Customize Poems

All 12 poems are stored in the `poems.ts` file:

```ts
// src/poems.ts
const poems = [
  {
    title: "Poem 1",
    body: `Roses are red...\nViolets are blue...`,
  },
  // ...more poems
];
```

You can freely modify or replace these with your own poems.

## ❌ Known Issues

- App may not currently render properly due to unresolved bugs
- Functionality might be incomplete — **fixes are in progress!**

## 📌 Goals

- Fix UI rendering issues
- Add poem sharing or download features
- Optional: Add background music or ambient mode

## 📃 License

MIT License

---

Made with ❤️ for expression.

