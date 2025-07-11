
# 🐙 GitHub User Repository Search (React + TypeScript)

This is a **React** app built using **TypeScript** that allows users to search for GitHub users by their username and view their repositories. It uses **Axios** for API calls, **Material-UI** for styling, and **Vite** as the build tool.

## ✨ Features
- 🔍 **Search for GitHub users** by username.
- 📜 **Display a list of users** matching the search query.
- 🔗 **View repositories** of a selected user, along with details such as stars, descriptions, and links.
- 📱 **Mobile-friendly design** for smooth usage across all devices.

## 🛠️ Technologies Used
- **React** (for the front-end framework)
- **TypeScript** (for type safety)
- **Axios** (for API requests)
- **Material-UI** (for UI components and styling)
- **Vite** (for faster development build)
- **Node.js v20.15.0 or above** (for server-side JavaScript execution)

## ⚙️ Installation

### Prerequisites:
Make sure you have **Node.js v20.15.0 or above** installed. You can download it from the official website:  
[Download Node.js v20.15.0](https://nodejs.org/en/download/)

You can check your installed Node.js version by running:

```bash
node -v
```

### 1. Clone this repository:

```bash
git clone https://github.com/antonurhidayanto/githubsearch-repository.github.io.git
```

### 2. Navigate into the project directory:

```bash
cd github-user-repository-search
```

### 3. Install dependencies:
```bash
npm install
```

### 4. Start the development server:
```bash
npm run dev
```


## 🖥️ How to Use

1. **Search** for a GitHub user by entering their **username** in the search bar.
2. **Select a user** from the list of results.
3. The user's **repositories** will be displayed, with information such as:
   - **Repo Name**
   - **Stars**
   - **Description**
   - **Link to the repo**

## 🏗️ Project Structure

```
github-user-repository-search/
├── public/                  # Public assets (index.html, etc.)
├── src/                     
│   ├── components/          # React components (UserCard, UserSearch)
│   ├── utils/               # Utility functions (API calls)
│   ├── types/               # TypeScript types
│   ├── App.tsx              # Main app component
│   └── index.tsx            # Entry point of the app
├── package.json             # Project dependencies and scripts
└── tsconfig.json            # TypeScript configuration
```

## 📱 Mobile View

This application is designed to be fully **responsive**. On smaller devices, the layout adjusts automatically to fit the screen, ensuring a seamless experience whether on a desktop, tablet, or phone.

## 🎨 Demo

Check out the live demo of the app:

[Live Demo](https://antonurhidayanto.github.io/githubsearch-repository.github.io)

## 🤝 Contributing

Feel free to fork the repository, make your changes, and open a pull request. Contributions are welcome!

### Steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -am 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## 📝 License

This project is licensed under the [Anto Nurhidayanto](https://github.com/antonurhidayanto) License - see the [LICENSE](LICENSE) file for details.

---

Made with 💙 by [Anto Nurhidayanto](https://github.com/antonurhidayanto)
