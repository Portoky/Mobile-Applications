The main entity of this app is a trip/adventure, It has the following fields: \n
Name (string)
Coordinates (double, double)
Difficulty (1-5)
Panorama (1-5) 
Review (string)

This application initially will have no social media function
When starting the app you have to press the get started button. You are redirected to the list page which is the main page, here you can see all the trips/adventures the user have been so far. You have infinite scroll for the list and this is how you navigate between them. 
The edit and delete buttons are disabled if nothing is selected.
When 1 entity is selected the edit is enabled and the delete is enabled. If more entities are selected the edit is disabled.
Pressing add will redirect to the add page, you have to fill out the form press Add and on successful addition it will redirect you to the list main page, show errors otherwise. All the fields are required except the description
Pressing Edit you are redirected to the Edit/Update Page, the fields are initially loaded with the selected entities values. Pressing delete on that page will delete the object. On successful update or deletion you are redirected to the main page, show errors otherwise.
On the main page multiple trips can be selected, and we can operate bulk deletion on them.
