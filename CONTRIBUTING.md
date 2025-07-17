# Contributing to Incline Pace Calculator

Thank you for your interest in contributing to the Incline Pace Calculator project! This guide will help you get started with local development.

## Local Development Setup

### Prerequisites

- Python 3.6 or higher installed on your system
- A web browser for testing

### Running the Project Locally

Since this is a static HTML/CSS/JavaScript project, you can serve it locally using Python's built-in HTTP server.

#### Option 1: Using Python 3 (Recommended)

```bash
# Navigate to the project directory
cd altitude-calculator

# Start the server on port 8080 (assuming port 8000 is already in use)
python -m http.server 8080
```

#### Option 2: Using Python 2 (if Python 3 is not available)

```bash
# Navigate to the project directory
cd altitude-calculator

# Start the server on port 8080
python -m SimpleHTTPServer 8080
```

### Accessing the Application

Once the server is running, open your web browser and navigate to:
```
http://localhost:8080
```

You should see the main calculator suite page with links to all available calculators.

### Alternative Ports

If port 8080 is also in use, you can specify any available port:

```bash
# Example using port 3000
python -m http.server 3000

# Example using port 9000
python -m http.server 9000
```

Then access the application at `http://localhost:[PORT]` where `[PORT]` is your chosen port number.

## Development Workflow

1. **Fork the repository** (if contributing to the main project)
2. **Clone your fork** or the main repository
3. **Start the local server** using the instructions above
4. **Make your changes** to the HTML, CSS, or JavaScript files
5. **Test your changes** by refreshing the browser
6. **Submit a pull request** with your improvements

## Project Structure

```
altitude-calculator/
├── index.html                    # Main landing page
├── altitude_to_o2_percentage.html
├── o2_percentage_to_altitude.html
├── README.md
└── CONTRIBUTING.md              # This file
```

## Tips for Development

- Changes to HTML/CSS/JS files will be reflected immediately after refreshing the browser
- Use your browser's developer tools for debugging
- Test your changes across different browsers if possible
- Ensure all calculator links work correctly from the main page

## Troubleshooting

### Port Already in Use Error
If you get an error that the port is already in use, try a different port number:
```bash
python -m http.server 8081
```

### Python Not Found
Make sure Python is installed and added to your system PATH. You can check by running:
```bash
python --version
```

### Browser Caching Issues
If changes aren't appearing, try:
- Hard refresh (Ctrl+F5 or Cmd+Shift+R)
- Clear browser cache
- Use incognito/private browsing mode

## Questions or Issues?

If you encounter any problems or have questions about contributing, please open an issue on the project repository.
