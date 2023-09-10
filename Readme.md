# Pokémon Pokedex Web App

This web application allows users to explore information about the first generation of Pokémon. It provides a user-friendly interface to search and filter Pokémon by their names and types.

## Features

- **Fetch Pokémon Data:** The app retrieves data for the first 151 Pokémon using the PokeAPI.

- **Search Pokémon:** Users can search for Pokémon by entering their names in the search bar. The search is case-insensitive.

- **Filter by Type:** Users can filter Pokémon by their types using a dropdown menu. This filter updates the displayed Pokémon in real-time.

- **View Pokémon Details:** Clicking on a Pokémon card redirects the user to a detailed page for that Pokémon.

- **Responsive Design:** The app is designed to be responsive and can be used on various devices, including desktops, tablets, and mobile phones.

- **Ability Information:** Each Pokémon card displays the abilities of the respective Pokémon.

- **Shiny Pokémon:** The app provides both regular and shiny versions of each Pokémon.

## Hosted Link
  https://ameya-shinde.github.io/PokeMon-Cards-Gen1/

## JavaScript Functionality Used

This project utilizes JavaScript for various functionalities:

1. **Fetching Pokémon Data:**
   - The code uses the `fetch` API to retrieve information about the first 151 Pokémon from the PokeAPI.

2. **Search and Filtering:**
   - The application allows users to search for Pokémon by name. As users type in the search bar, the code filters the displayed Pokémon cards in real-time based on the input.

3. **Type Filtering:**
   - Users can select a Pokémon type from the dropdown menu. The code responds to this selection by filtering and displaying only Pokémon of the chosen type.

4. **Creating Pokémon Cards:**
   - JavaScript is used to dynamically generate HTML elements to display Pokémon information. This includes images, names, IDs, types, and abilities.

5. **Event Handling:**
   - The code sets up event listeners to respond to user interactions, such as clicking on Pokémon cards or entering text in the search bar.

6. **Clearing the Pokedex:**
   - There's a function to clear the Pokedex section, allowing for the display of a new set of Pokémon.

7. **Generating Type Filters:**
   - The code dynamically populates the type filter dropdown menu with unique Pokémon types.

8. **Responsive Design:**
   - The application is designed to be responsive and compatible with various devices, including desktops, tablets, and mobile phones.

9. **Promise Handling:**
   - Promises are used to manage asynchronous requests when fetching Pokémon data.
