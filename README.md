# GitHub Repository Fetcher

A modern, responsive web application that allows users to explore and discover public repositories from any GitHub user. Built with vanilla JavaScript, HTML, and CSS with a clean, intuitive interface.

## 🌟 Features

- **User-friendly Interface**: Clean and modern design with smooth animations
- **Real-time Search**: Fetch repositories from any GitHub user instantly
- **Repository Details**: View repository name, description, programming language, stars, forks, and last updated date
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Error Handling**: Comprehensive error messages for invalid usernames or API issues
- **Loading States**: Visual feedback during API requests
- **Direct Links**: Click on any repository to open it directly on GitHub

## Live Demo

https://shorturl.at/7jR9T


Simply open `index.html` in your browser to start exploring GitHub repositories!

## Screenshots

The application features a gradient background with a glassmorphism card design, providing an elegant and modern user experience.

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox, animations, and responsive design
- **JavaScript**: DOM manipulation and GitHub API integration
- **GitHub REST API**: Fetching repository data

## How to Use

1. Enter a valid GitHub username in the search field
2. Click the "Get Repos" button or press Enter
3. Browse through the user's public repositories
4. Click on any repository name to open it on GitHub
5. View details like programming language, stars, forks, and last update

## 🔧 Installation & Setup

1. Clone or download this repository
2. No build process required - it's a static web application
3. Open `index.html` in your preferred web browser
4. Start exploring GitHub repositories!

## 📁 Project Structure

```
WebAI/
├── index.html      # Main HTML file
├── index.css       # Stylesheet with modern design
├── index.js        # JavaScript functionality
└── README.md       # Project documentation
```

## 🎨 Features Breakdown

### CSS Features

- Glassmorphism design with backdrop filters
- Smooth hover animations and transitions
- Responsive grid layout for repository cards
- Loading spinner animations
- Fade-in effects for repository list items

### JavaScript Features

- Async/await for API calls
- Error handling for network issues
- Dynamic DOM manipulation
- Form validation
- Progressive loading with staggered animations

## 🔗 API Reference

This application uses the GitHub REST API:

- Endpoint: `https://api.github.com/users/{username}/repos`
- No authentication required for public repositories
- Rate limit: 60 requests per hour for unauthenticated requests

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔮 Future Enhancements

- [ ] Repository search and filtering
- [ ] Sort repositories by stars, forks, or update date
- [ ] User profile information display
- [ ] Repository topics and language filters
- [ ] Pagination for users with many repositories
- [ ] Dark/light theme toggle

## 🐛 Known Issues

- GitHub API rate limiting may occur with excessive requests
- Some users might have empty repository lists (private repos only)

---

Made with ❤️ using vanilla web technologies
