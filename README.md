# AVSP 2026 Conference Website

This repository contains the official website for the 16th International Conference on Auditory-Visual Speech Processing (AVSP 2026), to be held in Sydney, Australia on October 2, 2026.

## Deployment Instructions for GitHub Pages

### Option 1: Deploy from Repository Root

1. Create a new GitHub repository (e.g., `avsp2026`)
2. Upload both `index.html` and `AVSP2026.png` to the root of your repository
3. Go to your repository Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select the `main` branch and `/ (root)` folder
6. Click Save
7. Your site will be available at `https://yourusername.github.io/avsp2026/`

**Important**: Make sure to upload the `AVSP2026.png` image file along with the HTML file for the background image to display correctly.

### Option 2: Use a Custom Domain

1. Follow steps 1-6 from Option 1
2. In the Pages settings, add your custom domain (e.g., `avsp2026.org`)
3. Configure your domain's DNS settings as instructed by GitHub

### Option 3: Use GitHub's gh-pages Branch

1. Create a new branch called `gh-pages`
2. Upload `index.html` to this branch
3. In repository Settings → Pages, select the `gh-pages` branch
4. Your site will be published automatically

## File Structure

```
.
├── index.html          # Main website file
├── AVSP2026.png       # Sydney Harbour Bridge hero image
└── README.md          # This file
```

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Navigation**: Fixed navigation bar with smooth scrolling to sections
- **Elegant Aesthetics**: Inspired by Sydney's iconic sunset and harbor views
- **Self-Contained**: All CSS and JavaScript included in a single HTML file
- **SEO-Friendly**: Proper meta tags and semantic HTML structure

## Sections Included

- Home / Hero section with conference details
- About AVSP
- Conference Venue
- Program
- Call for Papers
- Important Dates
- Committees
- Invited Speakers
- Registration

## Customization

To update the content, simply edit the `index.html` file. The design uses:

- **Fonts**: Cormorant Garamond (serif, headings) and Jost (sans-serif, body)
- **Color Scheme**: Inspired by Sydney sunset (oranges, pinks, purples, blues)
- **Animations**: Smooth fade-ins and hover effects

## Browser Support

This website works on all modern browsers including:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2026 AVSP Conference. All rights reserved.

## Contact

For questions about the conference, please refer to the official AVSP website once it's live.
