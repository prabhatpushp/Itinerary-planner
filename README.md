# Itinerary Planner

## Introduction
The Itinerary Planner is a web application that helps users plan their trips by providing information about tourist places, hotels, and restaurants based on user-defined parameters. It utilizes advanced language models to generate accurate and relevant recommendations.

## Features
- **Tourist Place Recommendations**: Generates a list of tourist spots in a specified city within a certain distance from the nearest airport, formatted in JSON.
- **Hotel Listings**: Retrieves a list of hotels near a specified tourist spot, including details like name, address, rating, distance, and average price.
- **Restaurant Listings**: Provides a list of restaurants near a specified location, including name, address, cuisine type, rating, distance, and price range.
- **Dynamic Input Handling**: Uses prompts to dynamically generate queries for the language model based on user input.

## Tech Stack
- **Python**: The programming language used for development.
- **LangChain**: A framework for building applications with language models.
- **Transformers**: A library for state-of-the-art natural language processing.
- **Torch**: A deep learning framework for building and training models.

## Usage
1. Run the main script:
   ```bash
   python main.py
   ```
2. Follow the prompts in the console to input your desired parameters for tourist places, hotels, and restaurants.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/prabhatpushp/Itinerary-planner
   cd itinerary-planner
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Development
To contribute to the project, follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes and create a pull request.

## Future Ideas
- Integrate a user interface for easier interaction.
- Add support for multiple cities and regions.
- Implement user authentication for saving itineraries.

## Contributing
Contributions are welcome! Please follow the development guidelines above.

## License
This project is licensed under the MIT License. Feel free to use this project for personal or commercial purposes. 
