3D House Design Recommendation System
Welcome to the 3D House Design Recommendation System, a web-based application that leverages AI to provide personalized 3D house design recommendations. This project integrates a Python backend, HTML/CSS frontend, and interactive 3D visualizations using .glb files stored in the static/3d_models folder, with a map interface powered by Leaflet and Geopy for location-based features.
Features

  AI-Powered Recommendations: Utilizes machine learning to suggest house designs based on user preferences.
  3D Visualization: Displays house designs in 3D using .glb files stored in the `static/3d_models` folder for an immersive experience.
  Map Interface: Integrates Leaflet and Geopy to provide location-based design recommendations and visualizations.
  Responsive Frontend: Built with HTML, CSS, and JavaScript for a user-friendly interface.
  Python Backend: Handles data processing, AI model integration, and API endpoints.


Technologies Used

  Python: Backend logic, AI model implementation, and data processing.
  HTML/CSS/JavaScript: Frontend interface for user interaction.
  .glb Files: 3D models stored in the `static/3d_models` folder for house design visualizations.
  Leaflet: Interactive map interface for location-based features.
  Geopy: Geocoding and location data processing.
  Three.js: Rendering 3D models in the browser.


Installation
Follow these steps to set up the project locally:

Clone the Repository:git clone https://github.com/Dharaneesh05/3D-House-Design-Recommendation-System.git


Navigate to the Project Directory:cd 3D-House-Design-Recommendation-System


Install Python Dependencies:pip install -r requirements.txt


Set Up Frontend Dependencies:Ensure you have Node.js installed, then run:npm install


Run the Application:
Start the Python backend:python main.py


Start the frontend server (if applicable):npm start




Access the Application:Open your browser and navigate to http://localhost:5000 (or the port specified in your configuration).

Usage

Launch the application and interact with the web interface.
Input your preferences (e.g., location, design style, budget) through the frontend.
Explore AI-generated house design recommendations displayed in 3D using .glb files from the static/3d_models folder.
Use the Leaflet-based map to view location-specific design suggestions.
Save or export your favorite designs for further review.

Project Structure
3D-House-Design-Recommendation-System/
├── static/
│   └── 3d_models/          # .glb files for 3D house models
├── frontend/               # HTML, CSS, JavaScript files
├── backend/                # Python scripts for backend logic
├── models/                 # AI model files and scripts
├── requirements.txt        # Python dependencies
├── README.md               # This file
└── main.py                 # Main application script

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE.txt file for details.
Contact
For questions or feedback, please open an issue on the GitHub repository.
© 2025 Dharaneesh05. All rights reserved.
