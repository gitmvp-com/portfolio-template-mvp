# Portfolio Template MVP

> A minimal, responsive portfolio template for developers - MVP version based on [dopefolio](https://github.com/rammcodes/dopefolio)

## ✨ Features

- **Easy to Setup** - Simple HTML/CSS/JS structure
- **Fully Responsive** - Works on all devices
- **No Frameworks Required** - Pure HTML, CSS (SASS), and vanilla JavaScript
- **Clean Design** - Professional and modern look
- **SEO Optimized** - Fast loading and search engine friendly
- **Customizable** - Easy to modify colors and content

## 🚀 Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/gitmvp-com/portfolio-template-mvp.git
cd portfolio-template-mvp
```

### 2. Install dependencies

```bash
npm install
```

### 3. Compile SASS (Optional)

If you want to modify the styles:

```bash
npm run compile:scss
```

This will watch for changes in your SASS files and automatically compile them to CSS.

### 4. Open in browser

Simply open `index.html` in your favorite browser or use a live server extension.

## 🎨 Customization

### Change Theme Color

Edit `sass/abstracts/_variables.scss`:

```scss
$themeClrPrimary: #0062b9; // Change this to your preferred color
```

Then run `npm run compile:scss` to apply changes.

### Update Content

1. **Header & Logo** - Edit the header section in `index.html`
2. **Hero Section** - Update your name and tagline
3. **About Section** - Add your bio and skills
4. **Projects** - Replace placeholder projects with your own
5. **Contact Form** - Configure form action (use Formspree or similar service)
6. **Footer** - Update social links and information

### Add Your Images

Replace placeholder images with your own:
- Logo/Avatar in the header
- Project screenshots in the Projects section

## 📁 Project Structure

```
portfolio-template-mvp/
├── css/
│   └── style.css          # Compiled CSS
├── sass/
│   ├── abstracts/
│   │   ├── _variables.scss
│   │   ├── _mixins.scss
│   │   └── _utilities.scss
│   ├── base/
│   │   └── _base.scss
│   ├── components/
│   │   ├── _header.scss
│   │   ├── _footer.scss
│   │   ├── _skills.scss
│   │   └── _mouse-scroll.scss
│   ├── pages/
│   │   └── _home.scss
│   └── main.scss
├── index.html             # Main HTML file
├── index.js               # JavaScript functionality
└── package.json           # Dependencies
```

## 🛠️ Technologies Used

- **HTML5**
- **CSS3 / SASS**
- **JavaScript (ES6)**
- **Node-sass** - For SASS compilation
- **PostCSS** - For CSS autoprefixing

## 📦 Build Scripts

- `npm run compile:scss` - Watch and compile SASS files
- `npm run prefix:css` - Add vendor prefixes to CSS
- `npm run compress:css` - Minify CSS
- `npm run build` - Prefix and compress CSS for production

## 🌐 Deployment

You can deploy this portfolio to:
- **Netlify** - Drop your folder or connect your Git repository
- **Vercel** - Import your project from Git
- **GitHub Pages** - Push to GitHub and enable Pages in settings

## 📝 License

MIT License - feel free to use this template for your personal or commercial projects.

## 🙏 Credits

This MVP is inspired by [Dopefolio](https://github.com/rammcodes/dopefolio) created by [Ram Maheshwari](https://github.com/rammcodes).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

---

**Made with ❤️ for developers**