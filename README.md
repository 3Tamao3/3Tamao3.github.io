# Rene Özbay — Personal Portfolio

> My personal portfolio site, built on top of the [Dark Minimal](https://astro.build/themes/details/darkminimal/) Astro theme.

<img width="1920" height="1080" alt="astro-portfolio" src="https://github.com/user-attachments/assets/0df80067-5fe2-4c24-90c4-4eb28e1a7508" />

![Deploy Status](https://img.shields.io/badge/Deploy-Vercel-black?style=flat&logo=vercel)

---

[Live site](https://darkminimal.vercel.app) | [GitHub](https://github.com/3Tamao3) | [LinkedIn](https://www.linkedin.com/in/rene-%C3%B6-17b263232/)

## **About**
This site is built with the [Dark Minimal](https://astro.build/themes/details/darkminimal/) Astro theme, then customized with my own content, projects, and experience.

## **Features**
- **Blazing fast performance** powered by Astro
- **Beautifully styled** with Tailwind CSS
- **Experience timeline** showcasing my apprenticeship, internships, and courses
- **Projects grid** linking out to my GitHub repos
- **Like counter** backed by Firebase Firestore
- **Spotify integration** showing my current playlist
- **Working contact form** powered by Formspree
- **Interactive UI** including the `<LetterGlitch />` component from [ReactBits.dev](https://www.reactbits.dev/)

## **Stack**
### **Frontend**
![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)

### **Backend / Services**
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![Formspree](https://img.shields.io/badge/Formspree-E21A28?logo=formspree&logoColor=white)

## **Project structure**
```text
public/
└── svg/
src/
├── components/
|    ├── contact.astro
|    ├── experience.astro
|    ├── footer.astro
|    ├── home.astro
|    ├── logoWall.astro
|    ├── nav.astro
|    └── projects.astro
├── layouts/
|    └── Layout.astro
├── React/
|    ├── LetterGlitch.tsx
|    ├── LikeButton.tsx
|    └── SkillsList.tsx
├── pages/
|    └── index.astro
└── firebase.ts
```

## **Local setup**

### Prerequisites
- **Node.js** (v20 or higher)
- **pnpm**

1. Clone the repo:
```bash
git clone https://github.com/Gothsec/dark-minimal
```
2. Install dependencies:
```bash
pnpm install
```
3. Copy the environment file and fill in your Firebase credentials (used by the like counter):
```bash
cp .env.example .env
```
4. Start the development server:
```bash
pnpm dev
```

## **Deployment**
This project is built with Astro and deployed to [Vercel](https://vercel.com/).

> Built on the [Dark Minimal](https://astro.build/themes/details/darkminimal/) Astro theme, licensed under the [MIT License](https://opensource.org/licenses/mit).
