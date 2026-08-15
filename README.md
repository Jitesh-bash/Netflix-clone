# Netflix Clone

A front-end recreation of the Netflix landing page, built with plain HTML and CSS. It includes a responsive hero section, movie cards, custom Netflix typography, “More reasons to join” cards, and a frequently asked questions section.

![Netflix Clone hero background](images/preview.png)

## Features

- Netflix-style promotional banner and hero section
- Responsive navigation with language selector and sign-in button
- Email signup form layout
- Horizontally scrollable trending movie posters
- Hover scale and shadow effect for movie cards
- Responsive “More reasons to join” card grid
- FAQ cards with plus icons
- Local SVG icons, movie posters, and Netflix Sans font files

## Technologies

- HTML5
- CSS3
- Flexbox
- CSS Grid
- CSS media queries
- CSS `clamp()` for responsive sizing

## Preview

The project is a static website and does not require a build tool or package installation.

## Run Locally

### Open directly

Open `index.html` in your browser.

### Use a local server

Run this command from the project folder:

```powershell
python -m http.server 8000 --bind 0.0.0.0
```

Then open:

```text
http://localhost:8000
```

To view the project on a phone, connect the phone and computer to the same Wi-Fi network and open your computer's local IP address:

```text
http://YOUR-COMPUTER-IP:8000
```

Example:

```text
http://192.168.1.10:8000
```

## Project Structure

```text
.
|-- index.html          Main page markup
|-- style.css           Layout and responsive styling
|-- images/             Hero background image
|-- cards/              Movie poster images
|-- svgs/               Logo and interface icons
|-- Fonts/              Local Netflix Sans font files
|-- favicon.ico         Browser tab icon
```

## Responsive Design

Responsive styles are defined in the media query at the bottom of `style.css`:

```css
@media (max-width: 1310px) {
  /* responsive styles for smaller screens */
}
```

The layout uses flexible widths, flex wrapping, CSS Grid, horizontal scrolling, and `clamp()` to adapt across desktop, tablet, and phone screens.

## Disclaimer

This is an educational front-end project. It is not affiliated with Netflix and does not connect to Netflix services or APIs. The signup form is visual only.
