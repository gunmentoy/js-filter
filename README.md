# js-filter

## Description
This is a simple web application that allows you to filter through a list of contacts. The contacts are organized in an alphabetical order and each contact is associated with a letter. The application is built using HTML, CSS (Materialize CSS Framework), and JavaScript.

## Features
- **Contact List:** The application displays a list of contacts, each with a name that can be clicked. The contacts are grouped by the first letter of their names.
- **Search Functionality:** There is a search bar at the top of the page that allows you to filter the contacts by name. As you type in the search bar, the list of contacts updates in real time to match your search query.

## How It Works
The core functionality of this application is implemented in JavaScript. Here’s a brief overview of how it works:
1. **Getting the Input Element:** The JavaScript file first gets the input element from the HTML file using its ID, ‘filterInput’.
2. **Adding an Event Listener:** An event listener is added to the input element. This event listener listens for the ‘keyup’ event, which is triggered whenever a key is released on the keyboard.
3. **Filtering Function:** When the ‘keyup’ event is triggered, the filtering function, ‘filterNames’, is called. This function gets the current value of the input element and converts it to uppercase.
4. **Getting the Names:** The function then gets the unordered list element that contains the names from the HTML file using its ID, ‘names’. It selects all the list items in the unordered list that have the class ‘collection-item’.
5. **Looping Through the Names:** The function loops through each list item and gets the ‘a’ element within it. It checks if the inner HTML of the ‘a’ element, converted to uppercase, contains the current value of the input element.
6. **Displaying the Matches:** If a match is found, the display style of the list item is set to an empty string, which makes it visible. If no match is found, the display style of the list item is set to ‘none’, which hides it.

## Usage
To use this application, simply open the index.html file in your web browser. You can then start typing in the search bar to filter the contacts.

## Conclusion
This is a simple yet powerful application that demonstrates how you can manipulate the DOM using JavaScript to create dynamic behavior on your web pages. It’s a great starting point for anyone interested in learning more about web development. Enjoy exploring and expanding on this project!
