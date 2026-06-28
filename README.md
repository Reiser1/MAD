# Justification 
## Flow library 
The flow library is not covered in the lectures, but this library is useful for real-time data processing between the front end and the databases. 

In this project, we need to synchronise data between the cloud and the local database. And the local database is the 'reliable source of truth' in the 'BookRepository'. So, the front end will fetch data from the local database rather than the Firebase. When the synchronisation happens, the flow library makes sure the front end shows the latest data.

This will improve the user experience when there are lots of books to synchronise. User can perceive that the app is synchronising data while looking at the full favourites list.



**Glide (com.github.bumptech.glide:glide:4.16.0)**  
Used for efficient image loading and caching. Glide simplifies handling book cover images from URLs and improves app performance by automatically managing memory and image scaling.
