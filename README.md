Overview


A responsive web app that displays dog images from the Dog CEO Dog API. Users can view random images, filter by breed, and refresh the gallery.

Features

Displays 5 random dog images with breed names in a responsive grid.
Filter images by breed (e.g., "labrador") via text input.
Refresh button to load new random images and clear filter.
Error handling for invalid breeds or API issues.
Styled with Tailwind CSS for a modern, mobile-friendly UI.



Technologies
HTML, JavaScript, Tailwind CSS (CDN)
Dog CEO Dog API

Setup

Save index.html locally.
Open in a browser or serve with a local server (e.g., python -m http.server).
Ensure internet access for API calls.


Usage
On load, view 5 random dog images.
Enter a breed name to filter images.
Click "Refresh Images" to load new random images.
Responsive grid adjusts to screen size.


API Endpoints


https://dog.ceo/api/breeds/image/random/5
https://dog.ceo/api/breed/{breed}/images/random/5
