# Beets-client for Android
Some preliminary planning for an Android client utilizing the Beets-project, once it has an API of some kind.

Some ideas:
 
  * The start page of the app would list recently imported albums in a nice grid view or similar.
  * Another page would contain a grid view with all the user's albums, allowing the user to browse and edit their metadata. They could also be grouped by Artist/Genre/Year/etc. to prevent having to fetch a huge payload of data at once.
  
  * The API service would monitor some defined folders for added files. If new albums are found, they are marked as pending. The app would then receive a push notification, prompting the user to choose what to do, similar to normal beet import, but showing a grid of album covers that can be clicked to view track lists and percentages for the match etc. The user then chooses the matching album and the app tells the API to perform the import. The user could also configure the import to be fully automatic if the match is close enough.
  * If the machine running the service has a CD/DVD/BD -drive, it could notify the app to ask the user whether he wants to rip an inserted CD into the collection.
  * More ideas to come, hopefully.
