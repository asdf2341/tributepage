# 🌟 Tribute Page

This **Tribute Page** project is a simple, responsive webpage dedicated to an influential person. The goal of this project is to create a page that shares information about the chosen person, including an image, a brief description, and a link to learn more. The design is clean, minimalistic, and responsive, allowing it to look good on any device.

## 📝 Table of Contents

- [Live Demo](#live-demo)
- [Features](#features)
- [User Stories](#user-stories)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## 🌐 Live Demo

Check out the live demo of the project: [Tribute Page](https://your-live-demo-link.com)

## ✨ Features

- Clean and responsive design
- Image with a caption describing the subject
- Informative text about the subject
- External link for more information
- Centered image with responsive resizing

## ✅ User Stories

The project fulfills the following user stories:

1. The page contains a `main` element with an `id` of `main`, which holds all the other elements.
2. There is an element with an `id` of `title`, containing a string that describes the subject of the tribute page (e.g., "Dr. Norman Borlaug").
3. A `figure` or `div` element with an `id` of `img-div` is present on the page.
4. Inside the `#img-div`, there is an `img` element with an `id` of `image`.
5. Inside the `#img-div`, there is an element with an `id` of `img-caption` that describes the image shown.
6. An element with an `id` of `tribute-info` is present, containing textual content describing the subject of the tribute page.
7. There is an `a` element with an `id` of `tribute-link`, linking to an external site for more information. It opens in a new tab (`target="_blank"`).
8. The `#image` element uses `max-width` and `height` properties to resize responsively without exceeding its original size.
9. The `img` element is centered within its parent element.

## 💻 Technologies Used

- **HTML5**: Structure of the webpage
- **CSS3**: Styling and responsive design

## 🚀 Getting Started

To run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/tribute-page.git
   ```
2. Navigate to the project directory:
   ```bash
   cd tribute-page
   ```
3. Open `index.html` in your browser.

## 📚 Usage

1. Explore the tribute page to learn about the chosen subject.
2. View the centered image with a caption describing the image.
3. Read the informative text about the subject.
4. Click the link at the bottom of the page to learn more about the subject on an external site.

## 📁 Project Structure

```
tribute-page/
├── index.html       # Main HTML file
├── styles.css       # CSS styles
├── img/             # Images folder
│   └── tribute-image.jpg
└── README.md        # Project documentation
```

### `index.html`

Contains the structure of the tribute page, including the main content, image, caption, and external link.

### `styles.css`

Defines the styles for the page, including responsive design for the image and centering elements.

### `img/`

Contains the image used on the page.

## 🎨 CSS Highlights

- **Responsive Image**: The image is styled with `max-width` and `height` properties to ensure it scales properly on different devices.
- **Centering**: The image is centered using Flexbox.
- **Responsive Design**: Media queries are used to adjust the layout for mobile devices.

### Example CSS:

```css
#img-div {
  display: flex;
  flex-direction: column;
  align-items: center;
}

#image {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
}

#tribute-link {
  color: #007bff;
  text-decoration: none;
}

@media (max-width: 600px) {
  #title {
    font-size: 1.5em;
  }
}
```
