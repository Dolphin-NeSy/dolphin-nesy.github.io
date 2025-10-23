# Dolphin Website

This is the official website for [Dolphin](https://github.com/Dolphin-NeSy/Dolphin), a GPU-accelerated neurosymbolic learning framework.

## About

Dolphin is a Python package that enables scalable neurosymbolic learning by performing probabilistic computations over the GPU. It is integrated with PyTorch and provides a set of primitives for writing Pythonic probabilistic programs.

## Website Structure

- `index.html` - Main HTML file with all content
- `styles.css` - CSS styling with modern design
- `script.js` - JavaScript for interactivity and animations

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, sleek design with smooth animations
- **Interactive Elements**: Smooth scrolling, mobile menu, copy-to-clipboard functionality
- **Optimized Performance**: Lightweight and fast-loading

## Local Development

To view the website locally, simply open `index.html` in a web browser.

Alternatively, you can use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

Then navigate to `http://localhost:8000` in your browser.

## Deployment

This site is designed to be hosted on GitHub Pages. To deploy:

1. Push the code to your GitHub repository
2. Go to Settings → Pages
3. Set Source to "Deploy from a branch"
4. Select the `main` branch
5. Save

Your site will be available at `https://dolphin-nesy.github.io/`

## Credits

- Framework: [Dolphin](https://github.com/Dolphin-NeSy/Dolphin)
- Paper: [Dolphin: A Programmable Framework for Scalable Neurosymbolic Learning](https://arxiv.org/abs/2410.03348)

## License

This website is part of the Dolphin project. Please refer to the main repository for license information.
