# Spotify Web Player Clone

A responsive web-based clone of the Spotify web interface built with HTML and CSS.

## Project Overview

This project is a front-end implementation of the Spotify web player interface, replicating key UI elements including:

- Navigation sidebar with Home and Search options
- Library section with playlist creation options
- Content feed with music cards and sections
- Music player controls at the bottom
- Responsive design that adapts to different screen sizes

## Features

- **Navigation UI**: Sidebar navigation with Home and Search options
- **Library Section**: Your Library header with create playlist and podcast sections
- **Content Sections**: 
  - Recently Played
  - Trending now near you
  - Featured Charts
- **Music Cards**: Display album/playlist artwork with titles and descriptions
- **Music Player**: 
  - Now playing information
  - Playback controls
  - Progress bar
  - Volume controls
- **Responsive Design**: UI elements hide on smaller screens

## Technologies Used

- HTML5
- CSS3
- Font Awesome for icons
- Google Fonts (Montserrat)

## File Structure

- `Spotify.html` - Main HTML structure
- `Spotify.css` - Styling for the application
- `position.css` - CSS positioning examples
- `assets/` - Contains images for album artwork, icons, and logos

## Implementation Details

### Layout

The interface uses a CSS flexbox layout with three main sections:
- Left sidebar for navigation (340px width)
- Main content area (flex: 1)
- Fixed music player at the bottom (72px height)

### Styling

- Dark theme with black (`#000`) and dark gray (`#121212`, `#232323`) backgrounds
- White text and accent colors
- Custom-styled input sliders for playback and volume
- Interactive elements (buttons, links) with hover effects

### Responsive Design

A media query adjusts the interface for screens under 1000px:
```css
@media(max-width: 1000px){
    .hide {
        display: none;
    }
}