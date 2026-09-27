# Techfest 2026 - Official Landing Page

A modern, responsive landing page for Asia's largest science and technology festival - **Techfest**, hosted by IIT Bombay.

## Features

✨ **Modern Design**
- Clean and professional UI with gradient accents
- Smooth animations and transitions
- Responsive design for all devices
- Dark theme with cyan/magenta color scheme

🎨 **Interactive Elements**
- Animated navigation bar that hides on scroll down
- Smooth scroll behavior with Intersection Observer
- Hover effects on cards and buttons
- Animated gradient text
- Button press animations

📱 **Sections**
- **Hero Section**: Eye-catching welcome with CTAs
- **Stats Section**: Key festival metrics (5000+ participants, 50+ events, ₹50L+ prizes)
- **Featured Events**: 6 major event categories (Robotics, Code Sprint, Game Dev, AI/ML, Hardware, Web Dev)
- **Timeline**: Festival schedule and important dates
- **Footer**: Links, social media, and contact information

## Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with animations and gradients
- **Vanilla JavaScript**: Smooth scroll, animations, and interactions
- **Responsive Design**: Mobile-first approach

## File Structure

```
techfest-landing-page/
├── index.html          # Main landing page
├── README.md          # Project documentation
└── assets/            # Images and media (if needed)
```

## Installation & Usage

1. Clone the repository:
```bash
git clone https://github.com/yourusername/techfest-landing-page.git
```

2. Navigate to the project:
```bash
cd techfest-landing-page
```

3. Open `index.html` in your browser:
```bash
open index.html
# or
start index.html  # Windows
xdg-open index.html  # Linux
```

## Features Breakdown

### Navigation
- Fixed sticky navigation bar with smooth animations
- Gradient logo with hover effects
- Underline animation on nav links
- Call-to-action button for registration

### Hero Section
- Large animated gradient title
- Compelling tagline
- Dual CTA buttons (primary and secondary)
- Scroll indicator with bounce animation

### Stats Section
- 4 key metrics displayed in grid
- Glowing text effects
- Responsive layout

### Events Showcase
- 6 event cards with emoji icons
- Shimmer effect on hover
- Smooth elevation and border color transitions
- "Learn More" links with arrow animation

### Timeline
- Festival schedule with numbered timeline dots
- Dates, titles, and descriptions
- Glowing timeline dots
- Clear visual hierarchy

### Footer
- Multi-column layout with quick links
- Social media links
- Contact information
- Copyright notice

## Customization

### Colors
Edit the CSS variables in `:root`:
```css
:root {
    --primary: #00d4ff;      /* Cyan */
    --secondary: #0099ff;    /* Blue */
    --accent: #ff00ff;       /* Magenta */
    --dark-bg: #0a0e27;      /* Dark background */
    --card-bg: rgba(20, 30, 60, 0.8);  /* Card background */
    --text-light: #e0e0e0;   /* Light text */
    --text-muted: #999;      /* Muted text */
}
```

### Content
Update the event cards, timeline, and footer information directly in the HTML.

## Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies
- Pure vanilla HTML, CSS, and JavaScript
- Fast load times
- Optimized animations

## Future Enhancements

- [ ] Add event registration form
- [ ] Integrate with backend API
- [ ] Add event filtering
- [ ] Implement dark/light mode toggle
- [ ] Add news/blog section
- [ ] Sponsor showcase gallery
- [ ] Live event updates

## Contributing

Feel free to fork and submit pull requests for improvements!

## License

© 2026 Techfest, IIT Bombay. All rights reserved.

## Contact

- Email: support@techfest.org
- Website: techfest.org
- Location: IIT Bombay, Mumbai, India

---

**Made with ❤️ by the Techfest Team**
