# Image Gallery

A simple PHP-based image gallery application that displays and manages image collections.

## Features

- Display grid of image thumbnails
- View individual images in full size
- Responsive design using CSS
- Clean and simple interface

## Project Structure

```
├── images/         # Contains all gallery images
├── inc/           # PHP include files
│   ├── functions.inc.php
│   └── images.inc.php
├── styles/        # CSS stylesheets
│   ├── custom.css
│   └── simple.css
├── views/         # Template files
│   ├── header.php
│   └── footer.php
├── gallery.php    # Main gallery page
└── image.php      # Individual image view
```

## Setup

1. Place the project files in your web server directory
2. Ensure PHP is properly configured on your server
3. Add images to the `images/` directory
4. Access gallery.php through your web browser

## Requirements

- PHP 7.0 or higher
- Web server (Apache/Nginx)
- Modern web browser

## Usage

- Browse the gallery by accessing `gallery.php`
- Click on any thumbnail to view the full-size image
- Navigate back using browser controls or gallery links

## License

This project is open source and available under the MIT License.