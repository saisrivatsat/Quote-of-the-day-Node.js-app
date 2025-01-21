# Quote of the Day - Node.js Application

This is a simple Node.js application that displays the "Quote of the Day" on a beautifully styled webpage using Bootstrap and EJS templating. The quotes are fetched from the **Quotes REST API**.

## Features
- Fetches and displays the "Quote of the Day."
- Responsive and visually appealing user interface.
- Uses **EJS** for templating.
- Lightweight and easy to set up.

## Prerequisites
Before running this project, ensure you have:
- **Node.js** installed on your machine.
- **npm** (Node Package Manager) installed.

## Installation

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd quote-of-the-day-nodejs
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Run the Application**
   ```bash
   npm start
   ```

4. **Access the Application**
   Open your browser and go to: `http://localhost:5000`

## File Structure
```
quote-of-the-day-nodejs/
├── VIEW/
│   └── view.js         # EJS template for rendering the Quote of the Day
├── server.js           # Main server logic
├── package.json        # Project configuration and dependencies
└── README.md           # Project documentation
```

## Dependencies
- **express**: Web framework for Node.js.
- **ejs**: Embedded JavaScript templating.
- **axios**: Promise-based HTTP client for Node.js.
- **bootstrap**: CSS framework for responsive design.

## API Used
- **Quotes REST API**: Fetches the "Quote of the Day."
  - API URL: `https://quotes.rest/qod`

## How It Works
1. The server (`server.js`) fetches a quote from the Quotes REST API using **axios**.
2. The quote and its author are passed to the EJS template (`view.js`) for rendering.
3. The webpage displays the quote with a styled background and responsive design.

## Troubleshooting
- Ensure the API endpoint (`https://quotes.rest/qod`) is accessible.
- Check for any errors in the console/logs and ensure dependencies are correctly installed.
