# Explore Ontario 
Explore Ontario is a group project created through UofT's CSC301: Introduction to Software Engineering and partnered with John Leadston from Ontario Public Service.

**NOTE: The repo with the code is currently private, however can be demoed upon request.**

## Demo
[<img src="https://github.com/helenaglow/Ontario-Public-Service-Explore-Ontario-Demo/assets/113125436/427e0530-cb69-4518-83f1-21b1fdabb56d">](https://youtu.be/9D7S-SC50J8)
[Link to Demo Video](https://youtu.be/9D7S-SC50J8)

## Partner Intro
John Leadston is a Co-Chair of the Muskoka/Simcoe Central Region with the Ontario Public Service Leadership Network. His email is john.leadston2@ontario.ca, and he is our primary contact for this project. John is passionate about getting more people to experience the beautiful cultural and natural diversity of Ontario, and shining a spotlight on the indigenous history of our land. This project has had a great partnership history with CSC301, and we're excited to bring to life his newest vision for Explore Ontario!

Ontario Public Service is a government organization comprised of 60,000+ public servants responsible for providing government services to Ontario residents. The organization is overseen by the head of the service and a team of deputy ministers, comprised of the most senior public servant in each ministry. Ontario Public Service emphasizes the importance of accesibility and diversity in its services and workplace, which are values that John wants to champion through this app as well.

If you'd like to learn more about Ontario Public Service, please see here: https://www.ontario.ca/page/about-ontario-public-service

## Project Description
ExploreOntario is an iOS app that provides an enhanced travelling experience to Ontario residents and visitors alike while they are driving. The app uses geolocation to identify nearby historical, cultural, and environmental points of interest. The app then provides auditory stories of landmarks tailored to users' interests as users encounter them on their journey throughout the province. To reduce the interaction between the drivers and the app, a voice recognition system is implemented so the app understand basic instructions regarding audio playback. The app also suggests possible detours a user could make to visit some of these landmarks along the way.

Ontario hosts plenty of exciting and culturally rich locations, but most people driving through the province may be unaware of their significance or even their existence. ExploreOntario provides a hands-free, hassle-free way of informing travellers of the stories and locations of the landmarks they pass by on their road trips in the province. This app will be great for people who have long commutes to work, or who are going on a provincial road trip. Audio stories will be provided by employees of different tourism, environmental, and cultural ministries.
​

## Key Features
 * **Log In/Sign Up**
     * At initial sign-up, after the user has inputted their email and password, the app will prompt them for their interests (for example, "Culture" or "Geography") and save their preferences in a database.
     * It will remember the user's login session so they don't need to log in again before their authentication token has expired.
     * Users will later be able to log in to the app if they are ever signed out. The app will remember their saved preferences and visited locations, and won't play the visited locations' audio again.
 * **Geographical Location Tracking**
     * The app will track a user's location in real time in conjunction with calls to the Landmarks table in the database to determine which Ontario landmarks are within a 1km radius.
 * **Audio Play**
     * The app will play short audio stories about a landmark when a user is within a 1km range of it.
     * This audio will take into account the user's preferences will also be an audio the user has not heard before.
     * The app will also play longer, more detailed audio stories if the user indicates interest, either by clicking the available buttons or by saying "Tell me more" to the voice recognition system after the short audio has finished playing.
     * The user can also mute audio play by either clicking the volume button on the home page or by instructing the app through voice recognition. They can stop audio play by clicking the 'x' icon on the popup for the landmark.
     * In the visited landmarks page, users can hear the audio again that they've heard before by accessing visited landmarks.
 * **Speech Recognition**
     * When the app prompts users for longer audio stories, the user can respond vocally with "Tell me more" to ensure that they keep their attention on the road.
     * The user may pause the audio at any time by simply saying "Pause" to minimize the distraction.
     * The user may resume the audio at any time by simply saying "Resume".
     * The user may stop the audio at any time by simply saying "Stop".
     * The user may be directed to the landmark by simply saying "Take me there". 
 * **Navigation**
     * Take the user to the current highlighted landmark by saying "Take me there" or by pressing the button that pops up. This will transfer them to Apple Maps with the landmark's coordinates already inputted.
 * **Administrative Control**
     * There are three levels of users: super admin, admin and user.
     * When an administrative entity logs into the app, the administrator has access to additional options allowing for existing landmark information to be edited and new landmarks to be added along with audio contents
     * Admins can submit requests to the super user to add another user as an admin.
     * Super admin has additional access to special pages to approve/reject admin requests as well as revoke admin priveleges.
 * **Explored Pins**
     * The app has a tab that displays the pins of all the landmarks that the user has visited (i.e. heard the audio stories of)
     * The users will also see a list of these past visited pins in the Library tab, and there they will also be able to replay the stories
     *In the Library tab, a user can also favourite the landmarks they have visited
​
## Team 
  1. Helena Glowacki	
  2. Thakshajiny Mangaleswaran	
  3. Hannah Pan
  4. Noelle Ransom
  5. Alyson Roh
  6. Seo Won Yi (Sean)
  7. Ramy Zhang 
