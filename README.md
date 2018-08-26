This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

File Browser
## Problem Statement

You are expected to create pseudo frontend web app File Browser. Your web app should let user create and display the nested project structures and should provide file handling functionality mentioned below.
 
## Minimum Requirement
The user should be able to perform following operations in this.
- Show the file browser with proper indentation based on nesting.
- The default state is every folder closed.
- The view can have multiple folders.
- Use data in the file provided for rendering the view
- Add the file/folder inside any folder.
- Just need a way to show the file, No Need to create an actual file, Just create a dummy file item, Show that file as an item in the folder.
- Delete any file/folder. Implement Trash bin.
- View to see the detail of the content.
- Like createdAt, UpdatedAt, Owner. Etc.
- Search view for searching any file/folder.
 
## Intermediate
- Update any file/folder.
- The user can only update the name of the file/folder.
- Restore/Empty operations in the trash bin.
- Move files and folders by dragging and dropping.
- Implement a Recent activity view. Instantly updates the recently updated/added items in this view. With most recently updated at the top.


## Advanced
- Update/Delete/add/get operations in O(1).
- Infinite scroll.
- Keyboard handling.
- Use local storage for persistent data.
Think about user flows to accomplish the above operations.

## Expectation
- You have to implement the file browser project structure provided in the JSONs.
- Your Web app should allow users to create, update name and delete folders and files.
- You should implement drag & drop of files between folders.
- You should save both the long and short JSON in local storage, and load them on demand.
- All CRUD operations mentioned above should happen and update the short JSON in local storage.
- All infinite scroll etc should be implemented on the long JSON.
- You don’t have to implement a File/Text editor in your app. File name with an icon would be enough.


- Structure should be:
- Game Title(Folder)
- Game Play Resources(Folder)
-Installation(Folder)
- install.iso(File)
- archive_unbox.dat(File)
- Resource Dependency(Folder)
- profile.sav(File)
- snd0.AT3(File)
 
## Guide
-  Long JSON: http://hck.re/jimM8z
- Short JSON: http://hck.re/yNa9a3
 
## Tech Stack:
- HTML, CSS, Vanilla Javascript
- Angular/React (Optional)
 
## Wireframe reference (src: Hacker Earth Challenges)
 
![alt text](https://github.com/IshantL/File-Browser-React-App/blob/master/src/resources/wireframe.png)
 



