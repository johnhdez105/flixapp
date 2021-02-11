# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [X] (5pts) User can tap a cell to see more details about a particular movie.
- [X] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="https://i.imgur.com/NrZ7fCD.gif" width=250><br>

### Notes
One of the challenges I face during this part was getting the segue to work. It kept crashing whenever I tried to open up the movie, but I found that the fix for this was changing the class in the storyboard. I had accidentally set it to the wrong one.


---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [X] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="https://i.imgur.com/WxrDtC3.gif" width=250><br>

### Notes
Describe any challenges encountered while building the app.

I had an issue getting my system to install cocoapods for the movie posters and such and so I had to troubleshoot this problem for a while.
I eventually was able to get this issue resolved, but then I also ran into an issue of the pod not being installed correctly. 
After getting these issues resolved, I was able to succesfully get my app to load the movie posters correctly.
