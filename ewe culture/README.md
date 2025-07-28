# Ewe Culture Website

A comprehensive website showcasing the rich cultural heritage of the Ewe people of Ghana, featuring festivals, dances, language, traditional attire, tourism sites, and cuisine.

## Features

- **Homepage**: Overview of Ewe culture with hero section
- **About**: Detailed information about the Ewe people
- **Festivals**: Showcase of major Ewe festivals (Hogbetsotso, Asafotu, Yam Festival)
- **Dance**: Traditional Ewe dances (Agbadza, Borborbor)
- **Language**: Basic Ewe phrases and language learning resources
- **Culture**: Cultural evolution timeline and traditions
- **Dressing**: Traditional and modern Ewe attire
- **Tourism**: Tourist attractions in Ewe land
- **Food**: Traditional Ewe cuisine
- **Learn Ewe**: Language learning signup form

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Responsive design
- Ghana flag colors (Green, Yellow, Red)

## File Structure

```
ewe-culture/
├── index.html          # Main homepage
├── about.html          # About the Ewe people
├── festivals.html      # Ewe festivals
├── dance.html          # Traditional dances
├── language.html       # Ewe language
├── culture.html        # Cultural information
├── tourism.html        # Tourism sites
├── food.html           # Traditional cuisine
├── learn-ewe.html      # Language learning
├── style.css           # Main stylesheet
└── README.md           # Project documentation
```

## Deployment on Vercel

### Prerequisites
- A Vercel account (free at [vercel.com](https://vercel.com))
- Git installed on your computer

### Steps to Deploy

1. **Push to GitHub** (if not already done):
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/ewe-culture.git
   git push -u origin main
   ```

2. **Deploy on Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Sign up/Login with your GitHub account
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will automatically detect it's a static HTML site
   - Click "Deploy"

3. **Custom Domain** (Optional):
   - In your Vercel dashboard, go to project settings
   - Add your custom domain if desired

### Alternative: Direct Upload

1. Go to [vercel.com](https://vercel.com)
2. Click "New Project"
3. Choose "Upload" option
4. Drag and drop your project folder
5. Click "Deploy"

## Local Development

To run the website locally:

1. Clone or download the project files
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## Customization

- **Colors**: Modify CSS variables in `style.css`:
  ```css
  :root {
      --primary-color: #006b3f;    /* Ghana green */
      --secondary-color: #fcd116;  /* Ghana yellow */
      --accent-color: #ce1126;     /* Ghana red */
  }
  ```

- **Content**: Edit the HTML files to update text and images
- **Images**: Replace placeholder images with authentic Ewe culture photos

## Contributing

Feel free to contribute by:
- Adding more authentic Ewe culture content
- Improving the design and user experience
- Adding more interactive features
- Translating content to Ewe language

## License

This project is open source and available under the MIT License.

## Contact

For questions or contributions, please open an issue on GitHub. 