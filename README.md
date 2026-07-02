# Spylt Landing Page

Modern landing page built with **React**, **Vite**, **GSAP**, and **Tailwind CSS**. Designed for a bold, premium visual experience with smooth motion, responsive layouts, and a clean component structure.

---

## Features

* **Modern animated landing page** with a premium editorial feel
* **Fully responsive** layout for desktop, tablet, and mobile
* **React 19** for a fast component-based UI
* **Vite** for a lightweight development and build experience
* **GSAP and @gsap/react** for smooth, high-performance animations
* **Tailwind CSS 4** for utility-first styling and rapid iteration
* **Reusable section-based structure** for easy expansion
* **Custom typography and assets** already prepared in the project

---

## Project Structure

```text
src/
├── App.jsx
├── components/
│   ├── ClipPathTitle.jsx
│   ├── FlavorSlider.jsx
│   ├── FlavorTitle.jsx
│   ├── Navbar.jsx
│   └── VideoPinSection.jsx
├── constants/
│   └── index.js
├── index.css
├── sections/
│   ├── BenefitSection.jsx
│   ├── FlavorSection.jsx
│   ├── FooterSection.jsx
│   ├── HeroSection.jsx
│   ├── MessageSection.jsx
│   ├── NutritionSection.jsx
│   └── TestimonialSection.jsx
└── main.jsx

├── public/
│   ├── fonts/
│   ├── images/
│   ├── videos/
│   └── favicon.ico

├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── README.md
├── SECURITY.md
├── LICENSE
└── vite.config.js
```

---

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/AymaneMehdi/Spylt-React.js-GSAP.git
```

2. **Navigate to the project**

```bash
cd Spylt-React.js-GSAP
```

3. **Install dependencies**

```bash
npm install
```

---

## Running the Project

```bash
npm run dev
```

This starts the Vite development server, usually available at:

```text
http://localhost:5173
```

Open the app in your browser and edit the files in `src/` to see live updates.

---

## Building for Production

```bash
npm run build
npm run preview
```

Builds the app for production and serves the generated build locally for verification.

---

## Tech Stack

| Tool / Library     | Description                                       |
| ------------------ | ------------------------------------------------- |
| **React 19**       | Component-based UI library                        |
| **Vite**           | Fast frontend build tool                          |
| **JavaScript**     | Application logic                                 |
| **Tailwind CSS 4** | Utility-first styling framework                   |
| **GSAP**           | Animation library                                 |
| **@gsap/react**    | React integration for GSAP                        |
| **ESLint**         | Code quality and linting                          |

---

## Scripts

| Command          | Description                      |
| ---------------- | -------------------------------- |
| `npm run dev`    | Run the development server       |
| `npm run build`  | Build the project for production |
| `npm run preview`| Preview the production build     |
| `npm run lint`   | Run ESLint                       |

---

## Deployment

The easiest way to deploy your app is using [Vercel Platform](https://vercel.com) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

---

## Security

Please review our [Security Policy](SECURITY.md) for information about reporting vulnerabilities.

## License

This project is licensed under the [MIT License](LICENSE).

---

**Copyright © Aymane Mehdi**
