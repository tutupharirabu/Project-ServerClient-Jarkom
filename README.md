# Parallax Website with Python TCP Server

This project demonstrates a simple web server implementation using Python's socket programming along with a parallax scrolling website. The server delivers HTML, CSS, and JavaScript content to clients through a TCP connection.

## Project Structure

- `Server.py` - Python TCP server implementation
- `index.html` - Main HTML content with parallax scrolling effect
- `style.css` - CSS styling for the website
- `script.js` - JavaScript for parallax scrolling animation
- Image files (not included in the repository):
  - hill1.png, hill2.png, hill3.png, hill4.png, hill5.png
  - tree.png
  - leaf.png
  - plant.png

## Server Implementation

The server is implemented in Python using socket programming. Key features:

- TCP server running on `127.0.0.1:8080`
- Handles HTTP requests and serves web content
- Automatically embeds CSS and JavaScript within the HTML response
- Provides appropriate HTTP headers
- Returns 404 error page for missing files

## Website Features

The website implements a parallax scrolling effect with the following features:

- Responsive navigation bar with hover effects
- Parallax scrolling background with multiple layers of images
- Scroll-triggered animations where elements move at different speeds
- Content section with placeholder text
- Custom Google Fonts (Poppins)
- Color scheme with earthy tones (#F2E3DB, #41644A, #263A29, #003329)

## How to Run

1. Make sure all project files are in the same directory
2. Download the required image files (hill1.png, hill2.png, hill3.png, hill4.png, hill5.png, tree.png, leaf.png, plant.png)
3. Run the server using Python:

```bash
python Server.py
```

4. Open your web browser and navigate to: `http://127.0.0.1:8080`

## Technology Stack

- **Backend**: Python (socket programming)
- **Frontend**: HTML5, CSS3, JavaScript
- **Design**: Parallax scrolling, responsive design

## Notes

- This is a simple implementation for educational purposes
- The server embeds CSS and JavaScript directly into the HTML response rather than serving them as separate files
- No external web frameworks are used; everything is implemented with native Python libraries
