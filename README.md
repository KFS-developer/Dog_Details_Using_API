# Dog Breeds API Website  

This project is a simple website that displays information about different dog breeds. The website fetches data from a `db.json` file using JavaScript and renders it dynamically.  

## Features  
- Displays detailed information about various dog breeds, including:  
  - Breed type  
  - Size  
  - Lifespan  
  - Origin  
  - Temperament  
  - Colors  
  - Description  
- Fetches data from a local JSON server (`db.json`).  
- Responsive layout using HTML, CSS, and JavaScript.  

## Technologies Used  
- **HTML** – For structuring the webpage.  
- **CSS** – For styling and layout.  
- **JavaScript** – For fetching data and rendering content dynamically.  
- **JSON Server** – To serve data locally from `db.json`.  

## How to Run the Project  
1. Install JSON Server if not already installed:  
   ```sh
   npm install -g json-server
   ```
2. Navigate to the project folder and start the JSON Server:  
   ```sh
   json-server --watch db.json
   ```
3. Open `index.html` in a browser or use a live server extension in VS Code.

## Live Demo
https://dog-details-using-api.vercel.app/
