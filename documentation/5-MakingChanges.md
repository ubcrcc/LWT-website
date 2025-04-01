# 5 - Making Changes

Finally, you're set up and ready to do what you want with the website! This document will go into the website code and structure, and how to make the changes you want. 

## Website Structure

First let's go through the website structure quickly so you know what's up. There are five pages:

1. Landing page - "https://www.ubcredcrossclub.ca"\
This is the main page where users will end up after searching for the website. 

2. Events page - "https://www.ubcredcrossclub.ca/events/"\
This pages describes some upcoming and past events,

3. Sign up page - "https://www.ubcredcrossclub.ca/signup/"\
This page allows users to sign up as members, and offers links to job postings.

4. People page - "https://www.ubcredcrossclub.ca/people/"\
This page has profiles for our execs and directors.

5. About page - "https://www.ubcredcrossclub.ca/about/"\
This page describes all of our committees and our club.

## Landing Page

### Changing Text and Structure
The text for the landing page can be accessed in the top level folder, in the "index.md" file. You can change the descriptions on the main page here. You can also change the formatting and structure if you're so inclined.

### Changing Pictures
This page uses pictures in the "images/home" folder. If you'd like to change pictures, following these steps:

1. Find the picture you'd like to change in the "images/home" folder.

2. Find the link to that picture in the "index.md" file. You can do this by searching for the name of the picture.

3. Replace the picture in the "images/home" folder.

4. Make sure the name matches in the index.md file.

## Events

### Changing Text and Structure
To edit the text at the top of the "Events" page, or make changes to the structure of the page, edit the file "events/index.md".

### Adding An Event

To add an event, do the following steps:

1. Open "_data/projects.yaml". You should see a list of the events currently on the website.

<img src="media/vscode_events.png" alt="alt text" title="Title" width="50%">\

2. Add a text in the format of the other events in this file. If you don't have some things that other events do (a link to the event, for example), just leave these sections blank.

3. If you have a picture for this event, add a link to it as seen in the picture above: "image: images/events/test_event.jpg".

4. Now add your image to the "images/events" folder. Make sure the extension (eg. jpg, png) is the same as what you added to the "projects.yaml" file.

### Deleting An Event

To delete an event, do the following steps:

1. Delete the section of text related to the event in the "_data/projects.yaml" file.

2. Delete the image associated with this event from the "images/events" folder UNLESS it's used by another event. As of writing this document, event images are used for one event only. 