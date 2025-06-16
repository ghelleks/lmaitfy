# Let Me Gemini That For You

A parody of "Let Me Google That For You" (LMGTFY) that creates shareable links with typing animations for Google Gemini searches.

## Features

- 🎭 **Typing Animation**: Watch as your query gets "typed" into a simulated Gemini interface
- 🔗 **Shareable Links**: Generate URLs that others can visit to see the animation
- 📋 **Easy Copy**: One-click copying of Gemini search URLs
- 📱 **Responsive Design**: Works on desktop and mobile devices
- ✨ **Clean UI**: Modern gradient design with smooth animations

## How It Works

1. **Enter a query** in the input field
2. **Click "Gemini It For Them!"** to start the animation
3. **Watch the typing animation** simulate entering your query into Gemini
4. **Copy the generated link** to share with others
5. **Recipients see the animation** and can then visit Gemini with your query

## Usage

### Creating a Shareable Link
1. Visit the site and enter your query
2. Click "Gemini It For Them!" to see the animation
3. Copy the generated shareable link like:
   ```
   https://yourdomain.com/?q=your+search+query
   ```
4. Share this link with others - the actual Gemini URL is hidden until after the animation

### What Recipients See
When someone visits your shared link:
1. They see the typing animation with your query
2. After the animation, they can click "Visit Gemini" to go to the actual search
3. The Gemini URL remains obscured until they choose to visit it

## Deployment

This is a single-file web application ready for GitHub Pages:

1. Upload `index.html` to your repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `https://yourusername.github.io/repository-name/`

## Technical Details

- **Pure HTML/CSS/JavaScript** - No frameworks or dependencies
- **URL encoding** for special characters in queries
- **Clipboard API** with fallback support for older browsers
- **Responsive design** using CSS Grid and Flexbox

## License

MIT License - feel free to fork and customize!
