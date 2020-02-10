# GIPHY Search Engine

- This project focused on building something fun with my knowledge of axios and AJAX

## Functionality

This project does the following:
- Allows the user to search for a GIF and when the form is submitted, makes an AJAX request to the Giphy API and returns a single GIF
- Once the Giphy API has responded with data, appends the GIF to the page
- Allows the user to search for as many GIFs as they would like and keep appending them to the page
- Allow the user to remove all of the GIFs by clicking the remove button

### Building the form

When the user submits the form, I use axios to make a request to GIPHY for information based on that term. After receiving the response, I console.log the response data to make sure I'm getting back what I expect.

For example, here is what the AJAX request URL would look like for search term of “hilarious”: http://api.giphy.com/v1/gifs/search?q=hilarious&api_key=MhAodEJIJxQMxW9XqxKjyXfNYdLoOIym. You can click on this URL and see the JSON you will get back. To view this in a nicer format, it is recommended to use the JSON Viewer chrome extension. 

### Appending GIFs

Grabs a GIF from the response data and appends the GIF to the page. If you submit the form multiple times, you’ll get multiple GIFs showing up.

### Removing GIFs

Added a button next to the form which, when clicked, will remove all GIFs from the page.


## Screenshot of Application
![Image of the application](https://github.com/crwirth/GIPHYSearchEngine/blob/master/Screen%20Shot%202020-02-10%20at%2012.01.07%20PM.png)


You can access the GIPHY search engine here:

https://crwirth.github.io/GIPHYSearchEngine/

