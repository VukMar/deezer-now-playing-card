# Deezer Card Showcase
The Deezer Card Showcase is a React project that demonstrates the usage of the DeezerCard component. The DeezerCard component displays information about a currently playing track from Deezer and fetches track data from a specified API. It updates the card's content every 30 seconds and fetches data only when needed.
## Examples
### Active
![Example Active](/public/ExampleActive.PNG)

### Inactive
![Example Inactive](/public/ExampleInactive.PNG)
## Installation
To run the Deezer Card Showcase locally, follow these steps:

Clone this repository to your local machine:

`git clone https://github.com/your-username/deezer-card-showcase.git`

Navigate to the project directory:

`cd deezer-card-showcase`

Install the required dependencies:

`npm install`

Start the development server:

`npm start`

Open your web browser and visit http://localhost:3000 to view the Deezer Card Showcase.

## Features

Includes the DeezerCard component, which:
Fetches track data from a specified API.
Displays the album cover, artist name, and track title.
Opens a link to the Deezer track when clicked.
Updates the card's content every 30 seconds to keep the information up to date.

## Usage
To use the DeezerCard component in your own projects, you can follow these steps:

Copy the DeezerCard.js and DeezerCard.css file from the src/ directory of this repository to your project's component directory.

Import the component into your React application:

`import DeezerCard from './path-to-DeezerCard/DeezerCard';`

Use the DeezerCard component in your JSX code where you want to display the Deezer card:

`<DeezerCard />`

## Configuration
You can configure the DeezerCard component by modifying the following parameters in the DeezerCard.js file:

**apiUrl**: The URL of the API that provides track data from Deezer.

You can even modify the DeezerCard.css file to meet your styling needs.

## Dependencies
This project relies on the following dependencies:

**React***: The core library for building the user interface.
Make sure to install these dependencies in your project if they are not already present.

## License
This code is provided under the MIT License. You are free to use and modify it as needed for your projects.

## Author
**Vuk Marić**

## Support
If you have any questions or encounter any issues with this project or the DeezerCard component, please feel free to contact me on [My Website](https://vukmaric.rs/ContactMe).

The info on how to setup the API to fetch the track is on [My Blog](https://vukmaric.rs/Blog/Deezer%20App%20API%20-%20Now%20Playing%20Card)!

Happy coding! 🎵
