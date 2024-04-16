# Wildhacks2024
Northwestern's 2024 Wildhacks Best Technology Award.

Inspiration:

Music plays a vital role in our lives, having the power to influence emotions and mental states. Understanding this, we created MoodGenie, an iOS app that empowers you to be in tune with your mood and discover your "music personas".

What it does:

By analyzing your most-listened-to songs and tracking your mood, it creates personalized playlists that resonate with your mood and personality to empower your wellness journey.

How we built it:

Frontend in Swift: We used a rich array of Swift documentation to develop a visually appealing and interesting app interface. This includes, but is not limited to, animations, navigation lead and stack, text and secure fields, as well as a range of buttons. The creative efforts that went into creating this app can by no means be ignored either. Pens and papers in our hands, we sketched out the elements we wanted our app to include — from the log-in page to the profile breakdown and persona ideation. With these ideas, we executed our creative vision by creating a basic wireframe and designed most of our app within Figma to serve as a reference while coding. Illustrations, the logo, and other multimedia elements were designed with Adobe software and Procreate. 

Backend in Python:
The algorithm dynamically adjusts to the user’s listening habits and preferences. 

Here's how it works:

Song playlist recommendation algorithm: Based on the mapped mood, it generates criteria based on similar artists and genres and guides Spotify’s recommendation engine to select tracks that match the user’s mood.

Persona matching: It extracts the user’s recently played songs, most played songs, and top artists. Then, it analyzes the song attributes (valence, tempo, speed, danceability, instrumentality) to determine the most fitting mood of each song. After characterizing all the songs, it determines the most dominant mood of the music (happy, sad, study music, popular music, etc.) and generates the fitting persona/character via the Spotify API.

We integrated Flask and the Spotify API to create an iOS application. It authenticates users via Spotify OAuth, retrieves their listening data, and provides API routes to retrieve user data, get recommendations based on the desired mood, and get the user’s persona.

Challenges:

Additionally, we integrated the backend and frontend of a mobile application for the first time. We programmed API routes in Python and created HTTP requests in Xcode to retrieve user data, get recommendations based on the desired mood, and get the user’s persona. The end product was a fleshed-out user experience and a heavily interconnected frontend and backend structure.

Accomplishments that we're proud of:

The end product was a fleshed-out user experience and a heavily interconnected frontend and backend structure. The algorithm dynamically adjusts to the user’s listening habits and preferences.

What's next:

Adding more functionality including the ability to share your listening playlists and moods with friends

Built With:

adobe-illustrator
flask
python
spotify-api-and-authentication
swift
xcode
git
