Collecting workspace information

# Dashboard

This project is a simple dashboard layout built using HTML and CSS. It includes a header, main content area, and an aside section for navigation.

## Project Structure

```
images/
index.html
style.css
```

- 

images

: Contains image assets used in the project.
- 

index.html

: The main HTML file that structures the dashboard.
- 

style.css

: The CSS file that styles the dashboard.

## Getting Started

To get started with this project, simply clone the repository and open 

index.html

 in your browser.

### Prerequisites

- A modern web browser

### Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Open 

index.html

 in your web browser.

## Usage

The dashboard includes the following sections:

- **Header**: Contains a search form, notification icon, user profile image, and greeting.
- **Main Content**: Displays user projects and announcements.
- **Aside**: Provides navigation links to different sections of the dashboard.

### CSS Classes

- `.container`: Main container for the dashboard layout.
- `.header-section`: Container for the header section.
- `.main-section`: Container for the main content area.
- `.aside-container`: Container for the aside navigation.

### Example CSS

```css
body {
    margin: 0;
    padding: 0;
    font-family: 'Roboto', sans-serif;
    box-sizing: border-box;
}

.container {
    display: grid;
    grid-template-columns: 0.25fr 1fr;
    grid-template-rows: .1fr 1fr;
    min-height: 100vh;
    grid-template-areas:
    "aside header"
    "aside main";
}
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)

---

