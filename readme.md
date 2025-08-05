# WordPress Coding Services Homepage

A simple, clean homepage template for selling coding services on WordPress. This is designed to be pasted directly into the WordPress page editor.

## Features

- **Minimal Design**: Clean layout that won't conflict with most WordPress themes
- **Responsive**: Works on mobile, tablet, and desktop
- **Essential Sections**:
  - Hero banner with call-to-action
  - Services grid with pricing
  - Contact form
  - Footer with company info
- **No Theme Conflicts**: Uses inline styles to avoid CSS conflicts

## Installation

1. In your WordPress dashboard, go to **Pages** → **Add New**
2. Click on the "Text" or "Code Editor" tab (not Visual editor)
3. Paste the entire HTML code
4. Publish or update the page

## Customization

### Content Changes
- Replace all placeholder text with your actual content
- Update the service offerings and prices
- Change contact information in the footer

### Style Changes
Modify the inline styles to match your brand:
- Change colors by editing the hex values (e.g., `#2c3e50`)
- Adjust padding/margin values (e.g., `padding: 60px 20px`)
- Update font sizes (e.g., `font-size: 2rem`)

### Form Handling
By default, the form shows an alert on submission. To actually process form submissions:
1. Install a form plugin like WPForms or Contact Form 7
2. Replace the form HTML with the plugin's shortcode
3. Remove the JavaScript form handler

## Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers
- IE11+ (with possible minor styling issues)

## Troubleshooting

**Page looks broken:**
- Ensure you're pasting in the "Text" tab, not "Visual" editor
- Try disabling any page builder plugins temporarily
- Check for JavaScript errors in browser console

**Styles not applying:**
- Your theme might be overriding styles - try adding `!important` to critical styles
- Some WordPress security plugins may strip inline styles - check plugin settings

**Form not working:**
- JavaScript might be disabled by security plugins
- Consider using a dedicated form plugin instead

## License
Free to use and modify. No attribution required.
