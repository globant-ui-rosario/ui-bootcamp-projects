# Games Character Web Application

## Introduction
The idea of this project is to evaluate the applicants, to see if they have all the required knowledge related to the 
on going [Bootcamp](https://github.com/globant-ui/html5bootcamp). The applicant should cover all the requirements from the
[Requiremtents](#requirements) section.

For this project we will be creating a Web Application retrieving information from the [Spotify API](https://developer.spotify.com/).
All the methods (or URLs) that will be used are explained into the API docs.

## Browser scope and devices support

- **Browsers:** Edge version of Chrome, Firefox and IE
- **Devices:** At least one mobile device running Chrome

## Tech stack

- One of the following frameworks: AngularJS, BackboneJS, ReactJS
- CSS
- HTML5

## Requirements, acceptance criteria and assumptions 

### Acceptance Criteria

| ID    | Description                                                                 |
| ----- |-----------------------------------------------------------------------------|
| AC1  | Must implement responsive design                                             |
| AC2  | Must implement BackboneJS, AngularJS or ReactJS                              |
| AC3  | Must handle asynchronous calls to the Web API in the better way possible     | 
| AC4  | Must run into edge version of Chrome, Firefox and IE (Desktop)               |
| AC5  | Must run into at least one mobile device running edge Chrome                 |


### Requirements

| ID    | Description                                                                                       |
| ----- |---------------------------------------------------------------------------------------------------|
| REQ1 | As a user I want to search tracks based on a provided query                                        |
| REQ2 | As a user I want to add tracks to a local stored playlist                                          |
| REQ3 | As a user I want to save the local stored playlist into Spotify                                    |
| REQ4 | As a user I want to see my playlists                                                               |
| REQ5 | As a user I want to share a playlist (optional)                                                    |

### Assumptions

| ID    | Description                                                                                                                                  |
| ----- |-------------------------------------------------------------------------------------------------------------------------|
| AS1  | **LocalStored playlist:** A playlist must be stored into localhost so then you can use this information for further uses |
| AS2  | **Tracks search:** A pager must be show when spotify result is limited                                                   |
| AS3  | **Saving the playlist:** Is just a button to send the local stored playlist to spotify                                   |
| AS4  | **See my playlists:** Different section than the search section when all the playlists are shown                         |

## What will be evaluated?

- Code quality.
- Project functionality.