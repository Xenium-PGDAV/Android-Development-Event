# Android Dev Buid the Movie app! 
## XENIUM '19
### *Note:*

Following text is just the guidelines for building the app.
You are expected to show your creativity to achieve the features and functionality of the app.

## Guidelines for making the app:

* The app would contain three Activities and two fragments.
* **1st Activity** is the LoginActivity containing two input fields and two buttons (login, sign up)

	- On clicking the login button, there should be proper fetching of the data from the database. After the sucessful authentication of the username and password a toast message of `Login Successful` should appear.  The `list_of_movies fragment` (Fragment 1) should open which is in the 3rd activity.	
	
	- On clicking the signup button, the `Sign up activity` (Activity 2) should open for the registration of a new user.
	

* **2nd Activity** is the Sign up  Activity  containing 2 input fields and 2 buttons (signup, login).

	- On clicking the signup button, There should be proper insertion of data in the Database, i.e. the new user information, with a toast message appearing `Registration successful!`.
	 And, the `list_of_movies fragment` (Fragment 2 ) will open which is inside the 3rd Activity.
	 
	 
* **3rd Activity** contains two Fragments.

**API Link (Movies)** - http://api.themoviedb.org/3/movie/upcoming?api_key=b7cd3340a794e5a2f35e3abb820b497f

**Image Base URL**    - http://image.tmdb.org/t/p/w185/

   - **1st Fragment** (Movies List Fragment) - 
        - Shows the list of movies fetched from the internet along with their images in the card view.
        - On click of each movie, `Detail Fragment` (Fragment 2) will open.
	
   - **2nd Fragment** (Detailed Fragment)
        - Shows the following details of the movie that is clicked:
            - Name (Title of the movie)
            - Genre
            - Release Date
            - Summary
            - Ratings


Submit the code? 
>Make a zip/rar/tar file of your project and email it to : `yousufprv@gmail.com`
