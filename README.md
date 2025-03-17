# Conversation Genome Project

![Conversation Genome Project Logo](./assets/logo.png)

## Overview

The Conversation Genome Project is a platform that provides AI-powered character interactions through the Personas API. This project enables developers to implement rich, contextual AI characters for various applications including customer service bots, e-commerce sales assistants, gaming NPCs, and more.

## Features

- **Extensive Character Database**: Access to 6 million individual characters with 500TB+ of conversational training data
- **Character Customization**: Create and deploy custom AI characters with unique personalities, backgrounds, and traits
- **Simple API Integration**: Easy-to-implement API for adding character interactions to any application
- **Multiple Use Cases**: Ready for implementation in games, customer service, e-commerce, education, and more
- **Responsive Design**: Fully responsive web interface that works on all devices
- **Modern UI Components**: Clean, modern UI with animated components and interactive elements

## Technologies Used

- HTML5
- CSS3 (with custom variables and responsive design)
- JavaScript (vanilla JS)
- highlight.js for code syntax highlighting
- Custom animations and transitions

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/conversation-genome-project.git
cd conversation-genome-project
```

2. No build process is required. Simply open `index.html` in your browser to view the project locally.

3. For deployment, upload all files to your web server.

## Project Structure

```
conversation-genome-project/
├── index.html          # Main HTML file
├── styles.css          # Main CSS file
├── assets/             # Images and other static assets
│   ├── wizard.png      # Character images
│   ├── woman.png
│   ├── man.png
│   ├── child.png
│   └── dots.png        # Background pattern
└── README.md           # Project documentation
```

## Customization

### Colors and Variables

The project uses CSS variables for easy customization. Edit the `:root` section in `styles.css` to change the color scheme, typography, spacing, and more:

```css
:root {
  /* Colors */
  --color-bg: #0e0e0e;
  --color-text: #ffffff;
  --color-text-secondary: #8f8f8f;
  /* ... other variables ... */
}
```

### Images

Replace the character images in the `assets/` directory to change the appearance of the character cards. Ensure new images have similar dimensions for proper display.

### Adding New Sections

To add new sections, follow the existing HTML structure and use the provided CSS classes for consistent styling:

```html
<section class="your-section section">
  <div class="container">
    <div class="your-section__content">
      <!-- Your content here -->
    </div>
  </div>
</section>
```

## Lazy Loading Images

The project implements lazy loading for images to improve performance. Images use the `loading="lazy"` attribute and a data-src pattern:

```html
<img src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" 
     data-src="./assets/image.png" 
     loading="lazy" 
     class="lazy" 
     alt="Description" />
```

JavaScript handles loading the actual image when it enters the viewport.

## Responsive Design

The site is fully responsive with multiple breakpoints:
- Desktop: 1200px and above
- Laptop: 992px - 1199px
- Tablet: 768px - 991px
- Mobile: 576px - 767px
- Small mobile: Below 576px

## Animation Effects

The project includes various animation effects that enhance the user experience:
- Text fade-in animations
- Character card entrance and floating animations
- Hover effects on buttons and interactive elements
- Scroll-based animations for metrics and features

## Browser Support

The site is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## API Documentation

While this repository contains the marketing website, API documentation can be found at the following endpoint:
`https://api.conversationgenome.com/docs`

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a pull request

## License

[MIT License](LICENSE)

## Contact

For questions or support, please reach out to:
- Email: info@conversationgenome.com
- Twitter: [@ConvoGenome](https://twitter.com/ConvoGenome)

## Acknowledgements

- Font icons provided by [FontAwesome](https://fontawesome.com/)
- Fonts used: Inter and Space Mono from [Google Fonts](https://fonts.google.com/)
- Code highlighting by [highlight.js](https://highlightjs.org/)
