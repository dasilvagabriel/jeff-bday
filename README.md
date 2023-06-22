# Jeff's Birthday Celebration

This project is a web page created to celebrate Jeff's birthday. It includes various sections with birthday-themed content, such as images, animations, and a slideshow. The project consists of an HTML file, a CSS file, and a JavaScript script.

## Usage

To view and interact with the birthday celebration page, follow these steps:

1. Download or clone the project files to your local machine.
2. Open the `index.html` file in a web browser.

## Features

### Header Section

The header section displays information about Jeff's birthday, including his name, an image, his age, and the date of his birthday.

### Gift Sections

The page includes multiple gift sections, each with a different theme related to Jeff's birthday. These sections display a title, a hint, and an animated image. Clicking on the image triggers the animation.

- "Here's how happy I am for you today 🥳": Displays an image that animates when clicked.
- "How people react when you enter the room 😍": Displays an image that represents people's reactions.
- "If I had to describe you with ONE word 👇": Displays an image representing one word to describe Jeff.
- "The only person as badass as you 💪": Displays an image representing Jeff's badassery.
- "This one's for you, my friend 🥂": Displays an image that animates when clicked.

### Slideshow

The page includes a slideshow with five images. Each image is accompanied by a number indicating its position in the slideshow. The slideshow automatically transitions between images, and you can navigate through the images using the dots at the bottom.

## Customization

You can customize the appearance of the page by modifying the CSS file (`styles.css`). The following CSS classes are available for customization:

- `body`: Styles applied to the body element.
- `img`: Styles applied to all images.
- `#bff-img`: Styles specific to the image of Jeff.
- `#bday-age`: Styles specific to Jeff's age.
- `#bday-date`: Styles specific to the date of Jeff's birthday.
- `.gift-section`: Styles applied to each gift section.
- `.gift-title`: Styles applied to the title of each gift section.
- `.gift-hint`: Styles applied to the hint of each gift section.
- `.gift-img`: Styles applied to the image container of each gift section.
- `#gift-img-happy`, `#gift-img-hot`, `#gift-img-genius`, `#gift-img-badass`, `#gift-img-cheers`: Styles specific to each gift image.
- `#footer`: Styles applied to the footer section.
- `a`: Styles applied to anchor links.

Feel free to modify these styles to customize the visual aspects of the page.

## Dependencies

This project does not have any external dependencies.

## Scripts

The project includes a `package.json` file with the following scripts:

- `start`: Starts the development server using Vite.
- `dev`: Alias for `start`.
- `build`: Builds the project for production.
- `preview`: Serves the production build locally for previewing.
