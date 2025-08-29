# Simple REST API Frontend

This project is a basic frontend built with **HTML, CSS, and Vanilla JavaScript** to interact with a REST API.
It demonstrates how to fetch data from an API and display it dynamically in a webpage without using frameworks.

## Features

- Static webpage layout with HTML
- Styling with CSS (responsive and clean design)
- Data fetching using JavaScript (`fetch`)
- Dynamic rendering of API data on the page

## Getting Started

### Prerequisites

- A running REST API to fetch data from (update the URL in `script.js`).
- Any modern browser (Chrome, Firefox, Edge, etc.).

### Setup

1. Clone this repository:

```bash
   git clone https://github.com/afuhflynn/codeveda-internship-task3
   cd simple-rest-frontend
````

2. Open `index.html` in your browser, or serve it locally using a simple server (optional):

   ```bash
   # Using Python
   python -m http.server 8000
   live-server extension in vscode
   nodejs server.
   ```

3. Update the API URL in `main.js`:

   ```javascript
   const res = await fetch("http://localhost:5000/api/todos");
   ```

4. Load the html page in a browser or refresh the the page and preview your changes.

## Project Structure

```txt
simple-rest-frontend/
│── index.html      # Main HTML file
│── styles.css       # Styling
│── main.js       # Fetch + DOM logic
│── README.md       # Documentation
│── LICENSE.md      # License
```

## License

This project is licensed under the MIT License – see the [LICENSE.md](LICENSE.md) file for details.
