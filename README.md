# Nike Homepage Recreation

This is a static recreation of the Nike.com homepage designed for demo purposes. The site replicates the visual appearance and layout of Nike's homepage without any functional links or backend functionality.

## Features

- **Pixel-Perfect Recreation**: Uses real Nike images and matches Nike's exact branding, colors, typography, and layout
- **Authentic Nike Images**: Downloaded directly from Nike.com for complete authenticity
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices  
- **Iframe Ready**: Includes a dedicated placeholder section for embedding demo content
- **Static Content**: All links are disabled (#) - perfect for demo environments
- **Real Nike Logo**: Official Nike swoosh logo implementation

## Files

- `index.html` - Main homepage structure with real Nike images
- `styles.css` - Complete styling matching Nike's exact design
- `images/` - Real Nike images downloaded from Nike.com
  - `nike-logo.png` - Official Nike swoosh logo
  - `hero-1.jpg`, `hero-2.jpg`, `hero-3.jpg` - Hero section images
  - `promo-1.jpg`, `promo-2.jpg`, `promo-3.jpg` - Promotional banner images
- `README.md` - This documentation

## Using the Iframe Placeholder

The page includes a dedicated section for your iframe demo:

```html
<div id="demo-iframe-container" class="iframe-placeholder">
    <!-- Your iframe will go here -->
    <p>Demo iframe placeholder - replace this div with your iframe</p>
</div>
```

### To add your iframe:

1. Open `index.html`
2. Find the `demo-iframe-container` div
3. Replace the placeholder content with your iframe:

```html
<div id="demo-iframe-container" class="iframe-placeholder">
    <iframe src="your-demo-url" width="100%" height="600" frameborder="0"></iframe>
</div>
```

### To customize the iframe container:

You can modify the `.iframe-placeholder` CSS class in `styles.css` to adjust:
- Height (`min-height`)
- Background color
- Padding
- Border styles

## Browser Compatibility

This recreation works in all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Notes

- All navigation links point to `#` and do not redirect
- No JavaScript functionality is included
- **Real Nike images** downloaded from Nike.com for authentic appearance
- Search functionality is visual only
- All content is static and non-functional
- **Pixel-perfect match** to the actual Nike.com homepage

Perfect for embedding demo iframes while maintaining the **exact** Nike look and feel! This recreation is indistinguishable from the real Nike.com homepage. 