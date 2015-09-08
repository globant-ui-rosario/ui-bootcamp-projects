# Games Character Web Application

## Introduction
The idea of this project is to evaluate the applicants, to see if they have all the required knowledge related to the 
on going [Bootcamp](https://github.com/globant-ui/html5bootcamp). The applicant should cover all the requirements from the
[Requiremtents](#requirements) section.

For this project we will be creating a Web Application retrieving information from the [Battle.net API](https://dev.battle.net).
All the methods (or URLs) that will be used are explained into the API docs. The API could be used without any kind of Authentication,
the only requirement is to have an application key registered.


## Browser scope and devices support

- **Browsers:** Edge version of Chrome, Firefox and IE
- **Devices:** At least one mobile device running Chrome

## Tech stack


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
| REQ1 | As a user I want to see each realm's current status                                                |
| REQ2 | As a user I want to input a character name and see basic information about it                      |
| REQ3 | As a user I want to see the top 10 players of the Challenge Mode Leaderboard                       |
| REQ4 | As a user I want to see the top 10 players of the PvP Leaderboard                                  |
| REQ5 | As a user I want to input a guild name and see its basic information                               |
| REQ6 | As a user I want to select one of the guild members and see its information                        |
| REQ7 | As a user I want to select one of the characters of the Leaderboards and see its basic information |

### Assumptions

| ID    | Description                                                                                                                                  |
| ----- |----------------------------------------------------------------------------------------------------------------------------------------------|
| AS1  | **Basic information:** common character information, common items information, all PVP information, guild name and overall stats              |
| AS2  | **Common character information:** name, class, race, gender, level, achievement points and thumbnail                                          |
| AS3  | **Common items information:** equipped average item level and list of items. For each item some information of your choice.                   |
| AS4  | **All PVP information:** Arena 2v2, Arena 3v3, Arena 5v5, RBG rate                                                                            |
| AS5  | **Overall stats:** health, power type + power (x mana, x energy as example), strength (str), agility (agi), intelligence (int), stamina (sta) |
| AS6  | **Guild basic information:** guild level, members (at least thumbnail, name, class and race)                                                  |

## What will be evaluated?

- Code quality.
- Project functionality.