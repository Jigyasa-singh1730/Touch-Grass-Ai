# 🌿 TouchGrass AI — Your Personal Outdoor Adventure Planner

**TouchGrass AI** is a nature-inspired web application that encourages people to take a break from screens, explore the outdoors, and build healthier daily habits. It helps users discover simple outdoor activities and create personalized nature adventures using AI.

The project combines **HTML, CSS, JavaScript, and open-source AI** to make spending time outdoors easier, more engaging, and fun.

## ✨ Features

- 🤖 **AI-Powered Adventure Planning:** Generate personalized outdoor activity suggestions based on your preferences.
- 🌳 **Nature Activity Challenges:** Explore activities that encourage you to spend more time outside.
- ✅ **Challenge Tracking:** Mark completed activities and track your progress.
- 📊 **Progress Dashboard:** View your completed challenges and activity progress.
- 🎨 **Nature-Inspired UI:** Enjoy a clean interface with a green color palette and a nature-focused design.
- 📱 **Responsive Design:** Designed to work across desktop and mobile screen sizes.
- 💾 **Local Progress Storage:** Save challenge progress in your browser using Local Storage.
- 🔄 **Fallback Suggestions:** Use predefined activity suggestions if AI generation is unavailable.

## 🎯 Problem Statement

Modern lifestyles often involve long hours of screen time and limited opportunities to enjoy nature. People may want to spend more time outdoors but struggle to decide what activities to try.

TouchGrass AI addresses this problem by making outdoor exploration simple, accessible, and interactive.

## 💡 Our Solution

TouchGrass AI acts as a personal outdoor adventure companion. Users can explore nature-based challenges, generate activity plans, and track their progress as they build a habit of spending more time outdoors.

The goal is to make outdoor activities feel achievable, enjoyable, and easy to start.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structures the web application |
| CSS3 | Provides styling, layout, and responsive design |
| JavaScript | Handles user interactions and application logic |
| Transformers.js | Enables compatible AI models to run in the browser |
| Hugging Face | Hosts the open-source model used by the application |
| Browser Local Storage | Saves challenge progress locally |
| VS Code | Development environment |
| Live Server | Runs the website locally during development |

## 🤖 AI Integration

The project uses [Transformers.js](https://huggingface.co/docs/transformers.js) to load a compatible language model directly in the browser.

**Model configured in the current implementation:** `onnx-community/Qwen2.5-0.5B-Instruct`

The AI is intended to generate outdoor adventure suggestions based on user input.

- AI model loading may require an internet connection.
- The first model download may take time, depending on model size and network speed.
- AI generation depends on browser compatibility, available memory, and model support.
- If AI generation fails, the application can use predefined fallback suggestions.

**Note:** The configured model must be compatible with the Transformers.js version and text-generation pipeline being used. If model loading fails, check the browser console and the model's Hugging Face page.

## 📂 Project Structure

```text
TouchGrass-AI/
│
├── index.html      # Main webpage structure
├── style.css       # Styling and responsive layout
├── script.js       # Application logic and AI integration
└── README.md       # Project documentation
```

## 🚀 Getting Started

Follow these steps to run the project on your computer.

### Prerequisites

- A computer with a modern web browser
- Visual Studio Code
- Internet access for loading the AI library and model
- The Live Server extension for VS Code

### Step 1: Clone the Repository

Replace `YOUR-USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR-USERNAME/TouchGrass-AI.git
```

### Step 2: Open the Project

Open Visual Studio Code, select **File → Open Folder**, and choose the project folder.

### Step 3: Install Live Server

1. Open Extensions in VS Code.
2. Search for **Live Server**.
3. Install the extension by Ritwick Dey.

### Step 4: Run the Website

1. Open `index.html` in VS Code.
2. Right-click inside the file.
3. Select **Open with Live Server**.
4. The website should open in your default browser.

You can also use the **Go Live** button in the VS Code status bar if it is available.

## 🧭 How to Use

1. Open TouchGrass AI in your browser.
2. Explore the available nature challenges.
3. Enter your preferences in the adventure planner, if prompted.
4. Click the relevant button to generate an outdoor adventure.
5. Review the suggested activities.
6. Complete an activity in real life.
7. Mark the corresponding challenge as completed.
8. Check your progress dashboard.

The exact options depend on the features enabled in the current version of the application.

## 💾 Data and Privacy

- Challenge progress is stored in the browser's Local Storage.
- Local Storage data remains on the same browser and device unless cleared or otherwise removed.
- Clearing browser data may erase saved progress.
- AI model files may be downloaded and cached by the browser.
- Avoid entering personal or sensitive information into the application.

## ⚠️ Limitations

- AI generation requires a compatible model and browser environment.
- The first AI model download can be slow.
- AI output may occasionally be inaccurate or irrelevant.
- Saved progress is not automatically synchronized across devices.
- The application does not verify whether an outdoor activity has actually been completed.
- Live Server is intended for local development, not as a production hosting service.

## 🔮 Future Improvements

- 🌦️ Weather-aware outdoor activity recommendations
- 📍 Location-based nature exploration
- 🏆 Streaks, badges, and achievement rewards
- 🗓️ Daily and weekly outdoor goals
- 🗺️ Maps for parks and nearby green spaces
- 🌱 Personalized recommendations based on interests
- ☁️ Optional cloud-based progress synchronization
- ♿ Improved accessibility and keyboard navigation
- 📲 Progressive Web App support
- 🧪 Automated testing and improved error handling

These are planned ideas, not necessarily features already implemented.

## 🌍 Impact

TouchGrass AI aims to encourage:

- More opportunities for outdoor exploration
- Regular breaks from screens
- Greater awareness of the natural environment
- Simple, enjoyable daily challenges
- A healthier balance between digital activities and outdoor experiences

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test the application locally.
5. Submit a pull request describing your improvements.

For significant changes, consider opening an issue first to discuss the proposed feature.

## 🐛 Reporting Issues

If you encounter a problem:

1. Check that all project files are in the correct folder.
2. Confirm that `style.css` and `script.js` are linked correctly in `index.html`.
3. Run the website using Live Server.
4. Open your browser's Developer Tools with `F12`.
5. Check the **Console** tab for JavaScript or AI-loading errors.
6. Include the error message when reporting the issue.

## 📄 License

This project does not yet specify a license. Add a suitable open-source license, such as the MIT License, only after deciding how you want others to use, modify, and distribute the work.

## 👩‍💻 Author

**Project:** TouchGrass AI  
**Category:** AI / Web Development / Sustainability  
**Built with:** HTML, CSS, JavaScript, and open-source AI

---

⭐ If you find this project interesting, consider giving the repository a star!

**Take a break. Step outside. Touch grass. 🌿**
