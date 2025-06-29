# Deadlock Detection and Avoidance Web Application

## Overview
This web application demonstrates Deadlock Detection and Avoidance concepts in Operating Systems through an interactive interface. Users can input process and resource data to visualize and understand deadlock scenarios using the Banker's Algorithm.

## Features
- User-friendly interface built with HTML, CSS, and JavaScript
- Implementation of Banker's Algorithm for deadlock detection and avoidance
- Dynamic input system for processes, resources, and allocation matrices
- Real-time computation and result display
- Visual representation of safe sequences and deadlock states

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 5.3.0

## Installation
1. Clone or download this repository
2. Open `index.html` in a modern web browser
3. No additional installation or setup required

## Usage
1. Enter the number of processes and resources
2. Click "Generate Matrices" to create input matrices
3. Fill in the following data:
   - Available resources
   - Allocation matrix (currently allocated resources)
   - Maximum need matrix
4. Choose either:
   - "Run Deadlock Detection" to check for existing deadlocks
   - "Run Deadlock Avoidance" to find a safe sequence using Banker's Algorithm
5. View the results displayed below

## Algorithm Implementation
- **Deadlock Detection**: Identifies currently deadlocked processes
- **Banker's Algorithm**: Determines if the system is in a safe state and finds a safe sequence

## File Structure
```
root/
│── index.html    # Main application interface
│── style.css     # Custom styling
│── script.js     # Core logic and algorithms
│── README.md     # Documentation
```

## Contributing
Feel free to fork this repository and submit pull requests for any improvements.

## License
This project is open-source and available under the MIT License.
