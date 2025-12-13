# Flash Cards App

This is a **Flash Cards** project built with **Astro** as part of the [roadmap.sh Flash Cards project](https://roadmap.sh/projects/flash-cards). The goal is to create a simple study application where users can review questions and answers using interactive cards and track their progress.

---

## Description

The application displays a set of flash cards containing questions and answers. Users can flip cards to reveal answers, navigate between cards, and visualize their progress through a progress bar.

## Getting Started

### Prerequisites

Make sure you have the following installed:

* **Node.js** (v18 or later recommended)
* One of the following package managers:

  * **pnpm** (recommended)
  * **npm**
  * **yarn**

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Steven-lh/flash-cards.git
cd flash-cards
```

---

### 2. Install dependencies

#### Using **pnpm** (recommended)

```bash
pnpm install
```

#### Using **npm**

```bash
npm install
```

#### Using **yarn**

```bash
yarn install
```

---

## Running the project

Start the development server:

#### pnpm

```bash
pnpm dev // pnpm run dev
```

#### npm

```bash
npm run dev // npm run dev
```

#### yarn

```bash
yarn dev // yarn run dev
```

The application will be available at:

```
http://localhost:4321
```

---

## Build for production

To generate the production build:

#### pnpm

```bash
pnpm build // pnpm run build
```

#### npm

```bash
npm run build
```

#### yarn

```bash
yarn build
```

To preview the production build locally:

```bash
pnpm preview
```

(or the equivalent command for npm/yarn)

---

## Project Structure

```
flash-cards/
├─ public/
├─ src/
│  ├─ components/
│  │  ├─ Card.astro
│  │  ├─ ProgressBar.astro
│  ├─ data/
│  │  └─ flashcards.json
│  ├─ layouts/
│  └─ pages/
│     └─ index.astro
├─ astro.config.mjs
├─ package.json
├─ pnpm-lock.yaml
└─ README.md
```

## Example Data (`flashcards.json`)

```json
[
  {
    id: 1,
    question: "What is JavaScript?",
    answer: "A programming language mainly used for web development."
  },
  {
    question: "What is Astro?",
    answer: "A modern web framework for building fast, content-focused websites."
  }
]
```

---

## Roadmap.sh Reference

This project follows the requirements defined in:

👉 [https://roadmap.sh/projects/flash-cards](https://roadmap.sh/projects/flash-cards)

---

## Contact

If you have suggestions or feedback, feel free to open an issue or reach out via GitHub.

---

Thanks.
