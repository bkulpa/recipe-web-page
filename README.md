# Description of the "Murzynek - Recipe" Web Page

This web page, featuring a recipe for "Murzynek" cake, is created using HTML and CSS, showcasing various web development techniques.

## HTML

- **Doctype**: `<!DOCTYPE html>` signifies that the document is an HTML5 webpage.
- **Language**: `lang="pl"` indicates that the primary language of the page is English.
- **Meta Tags**:
  - `charset="UTF-8"` sets the character encoding to UTF-8.
  - `http-equiv="X-UA-Compatible"` ensures compatibility with Internet Explorer.
  - `name="viewport"` enables responsiveness for different screen sizes.
- **Link to External CSS File**: `<link rel="stylesheet" href="style.css">` separates the presentation from the content.
- **Google Fonts**: Custom fonts (`Kotta One`, `Lato`) are imported from Google Fonts.

## HTML Structure and Content

- **Page Header**: Contains the title `PRZEPIS NA MURZYNKA` within an `<h1>` element.
- **Recipe Description**: A brief description of the recipe is placed in a `<p>` element.
- **Ingredients List**: Presented as an unordered list `<ul>`.
- **Preparation Method**: The steps to prepare the cake are listed in an ordered list `<ol>`.
- **Images**: Uses `<img>` elements to display photos of the cake.

## CSS

### General Styles

- **Page Background**: `background-image: url(./images/background.jpg);` sets the background for the entire page.

### Page Header (.page-header)

- **Text Color and Alignment**: `color: burlywood; text-align: center;`
- **Margins and Maximum Width**: Controls the size and positioning of the header element.
- **Font Family**: `font-family: 'Lato', sans-serif;`

### Paragraph (p)

- Styles such as margins, text alignment, font size, font weight, font family, line height, and maximum width.

### Image Containers (.div-photo-1, .div-photo-2) and Images (.photo-1, .photo-2)

- Styles for image containers and images including margins, borders, border radius, shadow, width, height, and opacity.

### Box (.box)

- Styling for the container of ingredients and preparation method, including background, margins, width, padding, opacity, and border radius.

### Ingredients List (.div-skladniki)

- Styling for the text and image in the ingredients section, including vertical alignment, margins, width, text alignment, font size, font weight, font family, and line height.

### Preparation Method (.sposob-przygotowania)

- Similar styling to the ingredients section, including background, text alignment, font size, font weight, font family, line height, padding, opacity, and border radius.

### Unordered List (ul)

- Font style settings for the ingredients list.

### Photo Gallery (.box\_\_gallery, div.gallery, div.desc)

- Gallery styling including margins, borders, width, border radius, background, hover effects, image sizes, and text alignment.

---

**Note**: This description assumes that the CSS stylesheet (`style.css`) and images are properly configured and available in the paths specified in the HTML code.
