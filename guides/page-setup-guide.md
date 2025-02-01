# Shoe Bazaar - Website Setup

This guide covers the essential per-page meta tags, CSS links, icon setups, and custom JavaScript files required for the Shoe Bazaar website. Ensure that all URLs and paths are replaced with the actual ones used in your project.

## Index Page Setup

### Meta Tags

These meta tags optimize the SEO and social media sharing experience for the index page.

```html
<meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Primary Meta Tags -->
    <title>Shoe Bazaar - Timeless Ethnic Wear with a Modern Twist</title>
    <meta name="title" content="Shoe Bazaar - Timeless Ethnic Wear with a Modern Twist" />
    <meta name="description"
        content="Explore Shoe Bazaar for exquisite handcrafted Indian ethnic wear. Discover sarees, lehengas, kurtas, and more that blend traditional heritage with contemporary style." />

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://yourwebsite.com" />
    <meta property="og:title" content="Shoe Bazaar - Timeless Ethnic Wear with a Modern Twist" />
    <meta property="og:description"
        content="Explore Shoe Bazaar for exquisite handcrafted Indian ethnic wear. Discover sarees, lehengas, kurtas, and more that blend traditional heritage with contemporary style." />
    <meta property="og:image" content="https://yourwebsite.com/path/to/your/image.jpg" />
    <!-- Replace with actual image URL -->

    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:url" content="https://yourwebsite.com" />
    <meta name="twitter:title" content="Shoe Bazaar - Timeless Ethnic Wear with a Modern Twist" />
    <meta name="twitter:description"
        content="Explore Shoe Bazaar for exquisite handcrafted Indian ethnic wear. Discover sarees, lehengas, kurtas, and more that blend traditional heritage with contemporary style." />
    <meta name="twitter:image" content="https://yourwebsite.com/path/to/your/image.jpg" />
    <!-- Replace with actual image URL -->
```

### CSS Link

Ensure your website has a clean and consistent look by linking the external CSS file.

```html
    <link rel="stylesheet" href="assets/css/style.css" />
```

### Remix Icon Integration

Use Remix Icon, a popular icon library, to enhance the design elements on your website.

```html
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.3.0/fonts/remixicon.css" rel="stylesheet" />
```

### Fav Icon

A favicon helps create brand recognition when users visit or bookmark your site.

```html
    <link rel="shortcut icon" href="assets/images/favicon.ico" type="image/x-icon">
```

### Custom JavaScript File

Load custom JavaScript functions to add interactivity and functionality to your website.

```html
    <script src="assets/js/script.js" defer></script>
```

## About Page Setup

### Meta Tags

Provide the right meta information for the "About Us" page, enhancing search visibility and social media previews.

```html
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- Primary Meta Tags -->
    <title>About Shoe Bazaar - Trusted Footwear Destination</title>
    <meta name="title" content="About Shoe Bazaar - Trusted Footwear Destination" />
    <meta name="description"
        content="Learn more about Shoe Bazaar, your trusted destination for trendy, affordable, and premium-quality footwear. Discover our commitment to comfort, style, and customer satisfaction." />

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://yourwebsite.com/about.html" />
    <meta property="og:title" content="About Shoe Bazaar - Trusted Footwear Destination" />
    <meta property="og:description"
        content="Explore Shoe Bazaar's journey in offering trendy, durable, and stylish footwear that ensures both comfort and value for your money." />
    <meta property="og:image" content="https://yourwebsite.com/path/to/your/about-image.jpg" />
    <!-- Replace with actual image URL -->

    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image" />
    <meta name="twitter:url" content="https://yourwebsite.com/about.html" />
    <meta name="twitter:title" content="About Shoe Bazaar - Trusted Footwear Destination" />
    <meta name="twitter:description"
        content="Find out how Shoe Bazaar delivers trendy, high-quality footwear while prioritizing customer satisfaction and affordability." />
    <meta name="twitter:image" content="https://yourwebsite.com/path/to/your/about-image.jpg" />
    <!-- Replace with actual image URL -->
```

## Product Page Setup

### Meta Tags

Provide the right meta information for the "Product" page, enhancing search visibility and social media previews.

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- Primary Meta Tags -->
<title>Explore All Shoes | Shoe Bazaar</title>
<meta name="title" content="Explore All Shoes | Shoe Bazaar" />
<meta name="description"
    content="Discover the latest collection of stylish and comfortable shoes at Shoe Bazaar. Shop premium quality sneakers, loafers, heels, and more for every occasion. Order now!" />

<!-- Open Graph / Facebook -->
<meta property="og:type" content="website" />
<meta property="og:url" content="https://yourwebsite.com" /> <!-- Replace with actual URL -->
<meta property="og:title" content="Explore All Shoes | Shoe Bazaar" />
<meta property="og:description"
    content="Discover the latest collection of stylish and comfortable shoes at Shoe Bazaar. Shop premium quality sneakers, loafers, heels, and more for every occasion. Order now!" />
<meta property="og:image" content="https://yourwebsite.com/path/to/shoes-image.jpg" />
<!-- Replace with actual image URL -->

<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:url" content="https://yourwebsite.com" /> <!-- Replace with actual URL -->
<meta name="twitter:title" content="Explore All Shoes | Shoe Bazaar" />
<meta name="twitter:description"
    content="Discover the latest collection of stylish and comfortable shoes at Shoe Bazaar. Shop premium quality sneakers, loafers, heels, and more for every occasion. Order now!" />
<meta name="twitter:image" content="https://yourwebsite.com/path/to/shoes-image.jpg" />
<!-- Replace with actual image URL -->

```

## Contact Page Setup

### Meta Tags

Provide the right meta information for the "contact" page, enhancing search visibility and social media previews.

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- Primary Meta Tags -->
<title>Contact Us | Shoe Bazaar</title>
<meta name="title" content="Contact Us | Shoe Bazaar" />
<meta name="description"
    content="Get in touch with Shoe Bazaar for any inquiries, orders, or support. We are here to assist you with the best shopping experience. Contact us now!" />

<!-- Open Graph / Facebook -->
<meta property="og:type" content="website" />
<meta property="og:url" content="https://yourwebsite.com/contact" /> <!-- Replace with actual URL -->
<meta property="og:title" content="Contact Us | Shoe Bazaar" />
<meta property="og:description"
    content="Get in touch with Shoe Bazaar for any inquiries, orders, or support. We are here to assist you with the best shopping experience. Contact us now!" />
<meta property="og:image" content="https://yourwebsite.com/path/to/contact-image.jpg" />
<!-- Replace with actual image URL -->

<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:url" content="https://yourwebsite.com/contact" /> <!-- Replace with actual URL -->
<meta name="twitter:title" content="Contact Us | Shoe Bazaar" />
<meta name="twitter:description"
    content="Get in touch with Shoe Bazaar for any inquiries, orders, or support. We are here to assist you with the best shopping experience. Contact us now!" />
<meta name="twitter:image" content="https://yourwebsite.com/path/to/contact-image.jpg" />
<!-- Replace with actual image URL -->

```

### Email.js CDN

To enable email functionality on the Contact Us page, include the Email.js CDN.

```html
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
```
