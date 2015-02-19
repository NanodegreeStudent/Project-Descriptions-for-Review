Students will develop a cloud-based API server to support a provided conference organization application that exists on the web as well as a native Android application. The API supports the following functionality found within the app: user authentication, user profiles, conference information and various manners in which to query the data.

##How will I complete this project?
1.  do not have to do any work on the frontend part of the application to finish this project. All your added functionality will be testable via APIs Explorer. <a href="https://docs.google.com/a/knowlabs.com/document/d/1JAvhhxTFfMCJ8kbCAlOHJ7GC2lwjatz-APGBImdAfHU/pub" target="_blank">More in-depth explanation</a>.
2. Clone the [conference application](http://github.com/udacity/fullstack-nanodegree-conference) repository.
2. Add Sessions to a Conference
  - Define the following endpoint methods
     * getConferenceSessions(websafeConferenceKey) -- Given a conference, return all sessions
     * getConferenceSessionsByType(websafeConferenceKey, typeOfSession) Given a conference, return all sessions of a specified type (eg lecture, keynote, workshop)
     * getSessionsBySpeaker(speaker) -- Given a speaker, return all sessions given by this particular speaker, across all conferences
     * createSession(User, SessionForm, websafeConferenceKey) -- open to the organizer of the conference
* Define Session class and SessionForm
     * Session name
     * highlights
     * speaker
     * duration
     * typeOfSession
     * date
     * start time (in 24 hour notation so it can be ordered).
3. Work on indexes and queries
* Create indexes
* Come up with 2 additional quereies
* Solve the following query related problem: Let’s say that you don't like workshops and you don't like sessions after 7 pm. How would you handle a query for all non-workshop sessions before 7 pm? What is the problem for implementing this query? What ways to solve it did you think of?
4. Add a Task
* Define the following endpoints method: getFeaturedSpeaker()
