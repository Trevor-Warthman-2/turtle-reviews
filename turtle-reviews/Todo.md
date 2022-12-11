# Todo List


## Start
[] - Figma
[] - JSON files to start


## Libraries
[] - Install some component library so we can steal their theme


## Homepage
[] - Blog post component

## Admin
[] - Basic admin login 
[] - Form to enter info about a resturant visit
  [] - Ratings
    [] - Taste / 10 * TasteWeight
    [] - Atmosphere /10 * AtmosphereWeight
    [] - Service / 10 * ServiceWeight
    [] - I want to eat there again tomorrow 0 or 1? * TomorrowWeight
  [] - pick Restarant from dropdown or create new Restarant record
[] - blog Post creation form. Pick a restarant visit or multiple and it'll link them to the new blog post object being made. 
  [] - When creating the post we obviously "write the post"
  [] - also shows a post creation date, visit date(s) drawn from the visit objects
  [] - #s we add to allow for filtering later. Mandatory one for cusine.


## Data
[] - Collection of restarants we've visited
  [] - Are these only our own, or do we pull restarants from the google maps api and select which one we visted?
  [] - Cusine is a mandatory subcollection. Probably array of string? Could also point to a cusine collection.
[] - Collection of restarant visits
[] - Collection of blog postings that can get generated using the restarant visit


Ratings different from posts?
1 blog : many reviews
1 restarant : many reviews


- A way to enter in restarant visits in admin
- a way to write blog posts grouping by restarant maybe?
- a way to view individual blog post
- a way to view all blog posts (homepage)