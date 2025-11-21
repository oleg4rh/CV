# Resume Website

This project is a simple resume website that showcases the professional profile of Oleh Peretiatko, a Junior Developer and Technology Graduate. The website includes sections for personal information, work experience, education, and technical skills.

## Project Structure

```
resume-website
├── index.html          # Main HTML document for the resume website
├── styles              # Directory for CSS styles
│   └── styles.css      # Styles for the website
├── scripts             # Directory for JavaScript files
│   └── main.js         # JavaScript functionality for interactivity
├── data                # Directory for data files
│   └── resume.json     # JSON data file for structured resume information
├── package.json        # npm configuration file
├── .gitignore          # Git ignore file
└── README.md           # Documentation for the project
```

## Getting Started

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```
   git clone <repository-url>
   ```

2. **Navigate to the project directory**:
   ```
   cd resume-website
   ```

3. **Install dependencies** (if any):
   ```
   npm install
   ```

4. **Open `index.html` in your web browser** to view the resume website.

## Features

- Responsive design that adapts to different screen sizes.
- Sections for work experience, education, and skills.
- Dynamic content loading from the `resume.json` file (to be implemented in `main.js`).

# Ініціалізувати git (якщо ще не ініціалізовано)
git init

# Додати всі файли (або вкажи конкретні: index.html styles img)
git add .

# Зробити коміт
git commit -m "Add resume site: index.html and styles"

# Перевірити, чи є віддалений репозиторій
git remote -v

# Якщо remote не встановлений — додати ваш репозиторій
git remote add origin https://github.com/oleg4rh/CV.git

# Якщо потрібно змінити URL origin
# git remote set-url origin https://github.com/oleg4rh/CV.git

# Перейменувати гілку в main і запушити
git branch -M main
git push -u origin main

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is open-source and available under the [MIT License](LICENSE).
