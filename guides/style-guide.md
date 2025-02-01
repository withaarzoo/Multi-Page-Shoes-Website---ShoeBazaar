# Style Guide

This document outlines the typography and color styles used in the project. It includes custom font integration via Google Fonts and global CSS variables to maintain design consistency.

## Google Fonts Integration

We are using the Poppins font family for typography, which is integrated into the project using the `@font-face` rule. Below are the different font weights and their corresponding styles.

```css
@font-face {
    font-family: 'Poppins';
    src: url('/assets/fonts/Poppins-Regular.ttf') format('truetype');
    /* Regular weight */
    font-weight: normal;
    font-style: normal;
}

@font-face {
    font-family: 'Poppins';
    src: url('/assets/fonts/Poppins-Medium.ttf') format('truetype');
    /* Medium weight */
    font-weight: 500;
    font-style: normal;
}

@font-face {
    font-family: 'Poppins';
    src: url('/assets/fonts/Poppins-SemiBold.ttf') format('truetype');
    /* SemiBold weight */
    font-weight: 600;
    font-style: normal;
}

@font-face {
    font-family: 'Poppins';
    src: url('/assets/fonts/Poppins-Bold.ttf') format('truetype');
    /* Bold weight */
    font-weight: bold;
    font-style: normal;
}
```

### Notes:

* **Poppins Regular:** Default body font with normal weight.
* **Poppins Medium:** Used for medium-emphasis text, like subheadings.
* **Poppins SemiBold:** Used for high-emphasis text, like section headers.
* **Poppins Bold:** For the most prominent text, such as titles or important elements.

## Global Color Variables

To maintain consistency across the design, we use CSS variables for colors. These variables ensure that the color scheme can be easily updated or adjusted without modifying individual elements.

```css
:root {
    --main-color: #FF3131;
    --secondary-color: #979797;
    --title-color: #212121;
    --text-color: #7b7b7b;
    --bg-color: #FFFFFF;
    --hover-color: #181b18;
    --light-bg: #F2F2F2;
}
```

### Explanation of Variables:

* **--main-color:** The primary color used throughout the project for key elements.
* **--light-color:** A lighter variation of the main color for less prominent elements.
* **--text-color:** The default text color, ensuring readability against the background.
* **--hover-color:** Color used for hover effects on buttons or interactive elements.
* **--bg-color:** The main background color, providing a soft, neutral look.
* **--light-bg:** A lighter background used for certain sections to create contrast.
