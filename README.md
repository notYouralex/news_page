# UM News Website

This project is a static website created as an HTML activity, showcasing news articles related to the University of Mindanao, Tagum City, and the world.

## Table of Contents

*   [Project Structure](#project-structure)
*   [Features](#features)
*   [Technologies Used](#technologies-used)
*   [Setup and Installation](#setup-and-installation)
*   [Deployment](#deployment)
*   [Contributing](#contributing)
*   [Authors](#authors)
*   [License](#license)

## Project Structure

├── .github
│ └── workflows
│ └── static.yml
├── .vscode
│ └── settings.json
├── README.md
├── about.html
├── img
│ ├── (various image files)
├── index.html
├── tagumNews.html
└── worldNews.html

*   **`.github/workflows/static.yml`:** GitHub Actions workflow for deploying to GitHub Pages.
*   **`.vscode/settings.json`:** VS Code settings for Live Server.
*   **`img/`:** Directory containing images used on the website.
*   **`index.html`:** Main landing page of the website.
*   **`about.html`:** "About Us" page introducing the team.
*   **`tagumNews.html`:** Page dedicated to news from Tagum City.
*   **`worldNews.html`:** Page dedicated to world news.

## Features

*   **News Sections:**  The website is divided into sections for University of Mindanao news, Tagum City news, and World news.
*   **Image Gallery:** The Tagum News page features a gallery of local attractions.
*   **Detailed News Articles:** Each news page contains articles with headlines, publication dates, images, and descriptive text.
*   **About Us Page:**  Provides information about the creators of the website with humorous descriptions.
*   **Contact and Social Links:** The footer includes contact information and links to social media profiles.
*   **GitHub Pages Deployment:**  The website is set up for easy deployment using GitHub Actions.

## Technologies Used

*   **HTML:** Structure and content of the website.
*   **CSS:** (Currently inline) Styling and layout.
*   **GitHub Actions:** For continuous integration and deployment.
*   **VS Code Live Server:** For local development server.

## Setup and Installation

1. **Clone the repository:**

    ```bash
    git clone <repository-url>
    ```

2. **Navigate to the project directory:**

    ```bash
    cd <project-directory>
    ```

3. **Open in VS Code (optional):**

    ```bash
    code .
    ```

4. **Start Live Server:**
    *   If you have the Live Server extension installed in VS Code, right-click on `index.html` and select "Open with Live Server."
    *   This will open the website in your default browser and automatically refresh when you make changes to the files.

## Deployment

The website is configured for deployment to GitHub Pages using the provided GitHub Actions workflow (`.github/workflows/static.yml`).

**To deploy:**

1. Push your changes to the `main` branch of your GitHub repository.
2. The GitHub Actions workflow will automatically build and deploy the website to GitHub Pages.
3. You can access your deployed website at `https://<your-github-username>.github.io/<repository-name>/`

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your forked repository.
5. Submit a pull request to the `main` branch of the original repository.

## Authors

*   **Jervis James Pedotim**
*   **Kyne Anthony Pizon**
*   **Gerald Andrei Villa**
*   **Alexander Arche**

## License

This project is licensed under the [MIT License](LICENSE) - see the `LICENSE` file for details. (You should add a LICENSE file if you want to specify a license).
