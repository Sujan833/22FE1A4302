URL Shortener

A simple URL Shortener application built with React.js and Material UI.
This project allows users to enter a long URL and generate a shorter version that can be copied and shared.
When someone visits the shortened URL, they are redirected to the original website.

✨ Features

Shorten long URLs into easy-to-share links.

Redirect to the original URL when the shortened link is opened.

Local storage persistence (URLs survive refresh).

Logging utility integrated for monitoring.

Built with React Router for navigation.

🛠️ Tech Stack

Frontend: React.js, React Router

UI Framework: Material UI

State Management: React Hooks (useState, useEffect)

Persistence: Browser LocalStorage

Logging: Axios + external logging API

📂 Project Structure
url-shortener/
 ├── public/
 │    └── index.html
 ├── src/
 │    ├── components/
 │    │    └── UrlForm.js
 │    ├── pages/
 │    │    ├── Shortener.js
 │    │    ├── RedirectHandler.js
 │    │    └── Statistics.js
 │    ├── utils/
 │    │    └── logger.js
 │    ├── App.js
 │    └── index.js
 ├── package.json
 └── README.md

🚀 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/url-shortener.git
cd url-shortener

2. Install Dependencies
npm install

3. Start Development Server
npm start


Open http://localhost:3000 in your browser.

🔮 Future Enhancements

Add backend service with a database.

Support custom short codes.

Add analytics dashboard for link tracking.

Implement authentication for user-specific links.

📜 License

This project is licensed under the MIT License.
