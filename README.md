# IJN | Web Developer Portfolio

A clean, modern, and high-performance personal portfolio website built with **HTML**, **Tailwind CSS**, and **Vanilla JavaScript**.

## 🎨 Visual Identity
- **Primary Palette**: Vibrant Sky Blue & Emerald Green (#0ea5e9, #10b981)
- **Aesthetics**: Glassmorphism, dynamic gradients, and smooth micro-animations
- **Typography**: Inter (Body) & Space Grotesk (Display)

## 🚀 Live Demo
[View Portfolio](https://ijn.github.io)

## ✨ Key Features
- **Modern Theme**: Professional dark-mode-first design with a clean, vibrant aesthetic.
- **Dynamic Contact Form**: Powered by **Web3Forms** for background email delivery without a backend.
- **Project Filtering**: Interactive project grid with real-time filtering (Web Apps, VB.Net, Graphic Design).
- **Interactive Experience**: 
    - Auto-dismissing animated splash screen.
    - Floating tech badges & profile ring.
    - Scroll-reveal animations for all sections.
    - Type-writer effect for role headlines.
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices.
- **Light/Dark Toggle**: User preference persists across visits via `localStorage`.

## 🛠️ Technology Stack
- **Structure**: HTML5 Semantic Markup
- **Styling**: Tailwind CSS v3 (CDN-based for ease of update)
- **Logic**: Vanilla JavaScript (ES6+)
- **Icons**: Font Awesome 6
- **Typography**: Google Fonts API
- **Form Delivery**: Web3Forms API (AJAX Interface)

## 📁 Project Structure
```text
MyPortfolio/
├── index.html      ← Main HTML structure & SEO
├── style.css       ← Custom design system, variables & animations
├── app.js          ← Application logic, data & form handling
├── images/         ← Asset directory (profile photos, project screenshots)
│   └── profile.jpg
├── cv.pdf          ← Downloadable CV (add yours!)
└── README.md       ← Documentation
```

## ⚙️ Setup & Deployment

### 1. Local Development
Simply open `index.html` in any modern web browser or use a "Live Server" extension in VS Code.

### 2. Form Activation
To receive emails from the contact form:
1. Get a free Access Key at [web3forms.com](https://web3forms.com/).
2. Update the `ACCESS_KEY` constant in `app.js`.

### 3. Deploy to GitHub Pages
1. Create a repository named `yourusername.github.io`.
2. Push all files to the `main` branch.
3. Go to **Settings → Pages → Build and deployment → Deploy from branch → main**.
4. Your portfolio will be live at `https://yourusername.github.io`.

### 4. Deploy to Vercel (Manual Upload)
If you want to deploy without using a GitHub repository:

**Method A: Vercel Dashboard (Drag & Drop)**
1. Sign in to your [Vercel](https://vercel.com/) account.
2. Go to the [Vercel Dashboard](https://vercel.com/dashboard).
3. Click the **"Add New..."** button and select **"Project"**.
4. Instead of importing from Git, look for the **"Deploy a Project"** section or the **drag-and-drop** area (usually at the bottom of the page).
5. Drag and drop your **MyPortfolio** folder directly into the browser.
6. Vercel will automatically detect the static project.
7. Click **Deploy**.

**Method B: Vercel CLI (Command Line)**
1. Open your terminal in the project folder.
2. Install the Vercel CLI: `npm install -g vercel`.
3. Log in: `vercel login`.
4. Run the deploy command: `vercel`.
5. Follow the prompts (Select "Yes" to set up and continue).
6. Once completed, your portfolio will be live at `https://your-project-name.vercel.app`.

## 📝 Customization
- **Personal Data**: All text data (Skills, Experience, Projects) is managed in `app.js` within arrays for easy updates.
- **Assets**: Swap images in the `images/` folder and replace `cv.pdf` with your actual CV.

---
© 2025 IJN. Built with ❤️ for the web developer community.
