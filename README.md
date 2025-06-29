# Portfolio Website – Israel Theodros 🚀

A modern, responsive portfolio website built with React and Vite, designed to showcase the projects, skills, and experience of Israel Theodros, an Information Systems student and aspiring developer.

## ✨ Features

- **🏠 Home:** Introduction and summary of Israel Theodros, including a professional tagline.
- **👤 About:** Personal background, education, and a downloadable CV.
- **🛠️ Skills:** Visual representation of technical skills with animated progress bars.
- **💻 Projects:** Dynamic list of GitHub repositories, each with a like button, technology badges, and direct links.
- **🌟 Testimonials:** Endorsements from colleagues and mentors.
- **✉️ Contact:** Contact form with validation, plus direct email, phone, and location info.
- **🔗 Footer:** Social media links (GitHub, LinkedIn, Twitter, Instagram, Telegram) and copyright.
- **🌙 Dark Mode:** Toggle for light/dark themes throughout the site.

## 🔗 Demo

Check out the live site here: [israel-theodros-portfolio.netlify.app](https://israel-theodros-portfolio.netlify.app)

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v16 or higher recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/israelseleshi/portfolio.git
   cd portfolio/my-portfolio-website
   ```
2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```
3. **Start the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   ```
4. Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

### 🏗️ Build for Production
```bash
npm run build
# or
yarn build
```

### 👀 Preview Production Build
```bash
npm run preview
# or
yarn preview
```

## 📁 Project Structure

- `src/pages/` – Main pages (Home, About, Projects, Contact)
- `src/components/` – Reusable UI components (Header, Footer, SkillCard, ProjectCard, TestimonialCard, AboutSection)
- `src/assets/` – Images and SVGs
- `src/App.jsx` – Main app component
- `src/main.jsx` – Entry point

## 🧰 Technologies Used

- [React](https://react.dev/) ⚛️ (with Hooks)
- [Vite](https://vitejs.dev/) ⚡ (for fast development)
- [Bootstrap](https://getbootstrap.com/) & [React-Bootstrap](https://react-bootstrap.github.io/) 🎨 (UI framework)
- [Framer Motion](https://www.framer.com/motion/) 🏃‍♂️ (animations)
- [FontAwesome](https://fontawesome.com/) ⭐ (icons)
- [Axios](https://axios-http.com/) 🔗 (API requests)
- [ESLint](https://eslint.org/) 🧹 (linting)

## 🛠️ Customization

- **GitHub Projects:**
  - The Projects section fetches repositories from [israelseleshi](https://github.com/israelseleshi). To use your own, update the GitHub username in `src/pages/Projects.jsx` and `src/pages/Home.jsx`.
- **Profile Info:**
  - Update About, Skills, and Testimonials in their respective components.
- **Social Links:**
  - Update links in `src/components/Footer.jsx`.

## 🙏 Credits

- Developed by [Israel Theodros](https://github.com/israelseleshi)
- Inspired by modern portfolio designs and open-source community

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
