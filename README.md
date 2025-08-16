# Cecilia – Personal Website

A simple, single-page personal website for **Cecilia Berrouet**, built with vanilla HTML, CSS, and JavaScript. It highlights an About section, Projects, Blog (Markdown-powered), and Contact information. This site is designed to be lightweight, easy to maintain, and deployable on any static hosting service.

---

## Features
- **Responsive design** with clean, modern styling.
- **About section** for personal introduction.
- **Projects section** to showcase portfolio work (currently includes placeholders).
- **Markdown-powered Blog**: posts written in `.md` files inside the `/posts` folder, rendered dynamically using [marked.js](https://marked.js.org/).
- **Contact section** with email, LinkedIn, and GitHub links.
- Lightweight: no frameworks or build tools required.

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourhandle/your-repo.git
cd your-repo
```

### 2. Run locally
Simply open `index.html` in your browser. No build step required.

### 3. Add your information
- Update `index.html` with your **name**, **email**, and **links**.
- Replace the placeholder project cards with real project details.

### 4. Blog setup
- Add Markdown files to the `/posts` directory.
  - Example: `posts/hello-world.md`
- Update the `postList` array in the script section of `index.html` with your file names:
  ```js
  const postList = ["hello-world.md", "my-second-post.md"];
  ```
- Each post will render inside the Blog section automatically.

#### Example: `posts/hello-world.md`
```markdown
# Hello World 👋

Welcome to my very first blog post on this site! This is a **Markdown-powered** blog, which means I can write posts using simple text formatting.

## Why this site?
I wanted a lightweight way to showcase my projects, background, and thoughts while learning more about web development.

## What’s next?
- Add more projects to my portfolio
- Share learning notes from my Computer Science M.S.
- Connect my biomedical research background with software engineering insights

Thanks for stopping by!
```

---

## Deployment
You can host this site for free using any static hosting service:
- **GitHub Pages**: Push to a repo named `yourhandle.github.io` and enable Pages in repo settings.
- **Netlify** or **Vercel**: Drag-and-drop the folder or connect your repo.
- **Other hosts**: Upload the files to any web server.

---

## Customization
- **Colors & Styles**: Tweak the CSS inside `<style>` in `index.html`.
- **Projects**: Replace placeholders with links to your GitHub repos or live demos.
- **Blog**: Continue adding Markdown posts in `/posts/`.

---

## License
MIT License — feel free to fork, modify, and adapt for personal use.

---

## Author
**Cecilia Berrouet**  
Software Developer in Training | M.S. Computer Science Student | Biomedical Research Background
