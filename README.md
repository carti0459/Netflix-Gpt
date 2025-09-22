# Netflix-GPT 🎬🤖

A modern Netflix clone powered by AI, built with React and integrated with GPT for intelligent movie recommendations and search capabilities.

![Netflix-GPT Banner](https://img.shields.io/badge/Netflix-GPT-E50914?style=for-the-badge&logo=netflix&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)

## 🌟 Features

- **AI-Powered Search**: Leverage GPT to search movies with natural language queries
- **Smart Recommendations**: Get personalized movie suggestions based on your preferences
- **Netflix-like UI**: Familiar and intuitive user interface inspired by Netflix
- **Responsive Design**: Seamlessly works across desktop, tablet, and mobile devices
- **Real-time Updates**: Fast and reactive user experience powered by React
- **Movie Database Integration**: Access to extensive movie collections and details

<!--## 🚀 Demo

[Live Demo Link](#)  Add your deployment link here -->

<!--## 📸 Screenshots

 Add screenshots of your application here 
![Homepage](screenshots/homepage.png)
![Search Feature](screenshots/search.png)
![Movie Details](screenshots/details.png)-->

## 🛠️ Built With

- **React** - Frontend framework
- **Vite** - Build tool and development server
- **GPT API** - AI-powered search and recommendations
- **TMDB API** - Movie database
- **Firebase** - Authentication and hosting
- **Tailwind CSS** - Styling and responsive design
- **Redux Toolkit** - State management

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v16.0 or higher)
- npm or yarn package manager
- Git

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/carti0459/Netflix-Gpt.git
   cd Netflix-Gpt
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory a sample env file is also given and add your API keys:
   ```env
   VITE_GEMINI_API_KEY=your_openai_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173` to see the application running

## 🔑 API Keys Setup

### Gemini API Key
1. Visit [GeminiAI Platform]
2. Sign up or log in to your account
3. Navigate to API keys section
4. Create a new API key

### TMDB API Key
1. Visit [TMDB](https://www.themoviedb.org/)
2. Create an account
3. Go to Settings → API
4. Request an API key

### Firebase Setup
1. Visit [Firebase Console](https://console.firebase.google.com/)
2. Create a new project
3. Enable Authentication
4. Get your configuration keys

## 📝 Usage

### Basic Usage
1. Sign up or log in using your email
2. Browse trending movies on the homepage
3. Use the AI-powered search to find movies
4. Click on any movie to view details
5. Add movies to your watchlist

### AI Search Examples
- "Show me sci-fi movies with time travel"
- "Romantic comedies from the 90s"
- "Movies similar to Inception"
- "Best action movies with high ratings"

## 🏗️ Project Structure

```
Netflix-Gpt/
├── public/
│   └── assets/
├── src/
│   ├── components/
│   │   ├── Browse/
│   │   ├── Login/
│   │   ├── GPTSearch/
│   │   └── common/
│   ├── hooks/
│   ├── utils/
│   │   ├── firebase.js
│   │   ├── openai.js
│   │   └── constants.js
│   ├── store/
│   │   ├── appStore.js
│   │   └── slices/
│   ├── App.jsx
│   └── main.jsx
├── .env.example
├── .gitignore
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 🚀 Deployment

### Deploy to Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/carti0459/Netflix-Gpt)

### Deploy to Netlify
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/carti0459/Netflix-Gpt)

### Manual Deployment
```bash
# Build the project
npm run build

# Preview the build
npm run preview
```

## 🧪 Testing

```bash
# Run tests
npm run test

# Run tests with coverage
npm run test:coverage
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Carti0459**

- GitHub: [@carti0459](https://github.com/carti0459)

## 🙏 Acknowledgments

- Netflix for the design inspiration
- Gemini for Gemini API
- TMDB for movie database
- React and Vite communities
- All contributors and supporters

## 📞 Support

For support, please open an issue in the [GitHub repository](https://github.com/carti0459/Netflix-Gpt/issues).

## 🔮 Future Enhancements

- [ ] Multi-language support
- [ ] Voice search functionality
- [ ] Social features (share lists, reviews)
- [ ] Offline mode support
- [ ] Advanced filtering options
- [ ] User profiles and preferences
- [ ] Watch party feature
- [ ] Mobile app development

---

⭐ Star this repo if you find it helpful!

Made with ❤️ by Carti0459
