<h1 align="center">A Valentine's Letter for Winter ❆</h1>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black">
  <img alt="Status: school project" src="https://img.shields.io/badge/status-school%20project-ffb6c1">
</p>

A website project made for our Website Development course.

## Features

- **Interactive envelope:** a sliding, silk-textured envelope that opens to reveal a personal letter.
- **Vinyl player:** a custom-styled music widget with a spinning vinyl animation, powered by JavaScript.
- **Winter atmosphere:** gently falling snow and a soft pastel color palette.
- **Message box:** a built-in contact form. Anything typed in the text area is delivered straight to the creator's email.

## Getting Started

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

Before opening the project, please check that:

1. Your music files (for example, `iu - i stan u.mp3`) are in the root folder.
2. `winter.png` and `winterlogo.png` are in the root folder.
3. The message form is connected to a backend, such as [EmailJS](https://www.emailjs.com) or a custom script, and configured with your own email address.

Then open `index.html` in your favorite browser. No build step required.

## Customizing the Playlist

To change the music, edit the `playlist` array in the JavaScript file:

```javascript
const playlist = [
  { name: "Song Name", src: "your-file.mp3" },
  { name: "Another Song", src: "another-file.mp3" },
];
```

## Project Structure

```text
.
├── index.html          # Letter and page structure
├── style.css           # Envelope, snow, and vinyl styling
├── script.js           # Envelope, snowfall, vinyl player, and form logic
├── winter.png
├── winterlogo.png
└── your-song.mp3       # Music files for the vinyl player
```

## Built With

- **HTML5** for the page structure
- **CSS3** for the envelope, pastel theme, and animations
- **JavaScript** for the vinyl player, snowfall, and form handling
- **EmailJS** (or a similar service) for delivering messages by email

## Disclaimer

This is a fan-made project and is not affiliated with Winter or her agency. It was made with plenty of admiration and wishing her happiness. 
