# photo-collection

**Structure**

The application should have a left sidebar and a main content container. The left sidebar should be a list of collections. Clicking on a collection displays the photos for that collection in the main content area. The main content container should be a grid of photos. Either all photos show in this content container, or just the photos in the selected collection. Initially there will only be `All` in the left sidebar, which shows the initial set of photos available to add to collections. 

**Basic functionality**

- To add a photo to a collection, each photo should have an 'Add to collection' link that toggles a modal or popover with a dropdown of existing collections to choose from, as well as an input to create a new collection on the fly. Once the collection is selected or input is filled out, clicking the add button adds the photo to the collection and closes the modal/popover.
- When viewing a collection each photo should have a 'Remove' link that removes that photo from the collection upon clicking.
- A collection should include a total count of photos somewhere in the main content area, as well as a button to delete the entire collection. Show a confirmation message before deleting an entire collection.
- When creating or deleting a collection, the left sidebar should update accordingly.

**Specs**
- Initially, there should be around 20 photos available to add to collections
- A collection should have a name and can be empty or contain photos
- A photo can only be added to a collection once
- A photo can be added to multiple collections
- It is not necessary to persist anything to a backend (app can reset to initial state on a refresh)
- It is not necessary to build in urls for everything unless you want to
- Feel free to style it up as you see fit, but it just needs to be functional