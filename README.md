# Griffin Bonomo-Clough

## Introduction

> I'm a developer currently studiyng Computer Science at John Abbott College.
 <!!ADD MORE!!>

## Contact

- insert email here
- insert Github link here

## Projects

Below is a list of projects I've worked on over the past few years as well as what I learned from them.

### PrivacyXPresso

> [PrivacyXPresso](https://github.com/tjklint/BellGeekfest2023) is a web app that was developed for the Bell Geekfest 2023 Hackathon, in which it placed top #5. <br/><br/> It was developed over the course of a day and a half alongside [tjklint](https://github.com/tjklint) and [DylanSavelson](https://github.com/DylanSavelson).

PrivacyXPresso is a hub for privacy-conscious individuals to manage the data they share with companies and test the strength of their passwords. 

The main feature, <ins>DataEraseX</ins> allows a user to demand a company delete their user data via email in accordance with the [CCPA](https://oag.ca.gov/privacy/ccpa) and the [GDPR](https://gdpr.eu/eu-gdpr-personal-data/).<br/>
PrivacyXPresso also includes a basic password strength tester with a dictionary of over <ins>1000</ins> words. It was developed as a bonus feature.

Further information about how this email works [here](https://ico.org.uk/for-the-public/your-right-to-get-your-data-deleted/#no).

#### The Development Process

The first few hours of the hackathon were hectic as I had never actually met my teammates in person before. Nevertheless, we quickly established roles and a document to organize our notes and ideas for how the app should look, feel and work. 

I worked primarily on the <b>JavaScript</b> side of things, helping teammates with merge conflicts along the way as well. At each major step of development, I showed the code to my teammates and asked them to test it out. This strategy proved to be incredibly helpful in the long run as it avoided long debugging sessions.

#### Future Ambitions [POSSIBLY TEMPORARY]

While the hackathon has ended, there are still some features I would like to see added to this app.

First is a better password strength tester. In reality, [dictionary attacks](https://www.techtarget.com/searchsecurity/definition/dictionary-attack) often use much more than <ins>1000</ins> words and aren't fooled by simply adding numbers to the end of a commonly used word like "password". 

>A link to the code can be found [here](https://github.com/tjklint/BellGeekfest2023).

### JS Video Game [CHANGE NAME AT SOME POINT]

> This is a game that is still in early stages of development. It uses the [JavaScript Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) for graphical rendering and utilizes many of the techniques learned in my Game Programming course at John Abbott College.

The intention for this game is to fuse the stealth mechanics of games like [DEADBOLT](https://store.steampowered.com/app/394970/DEADBOLT/) with the randomness and replayability of [roguelikes](https://en.wikipedia.org/wiki/Roguelike) like [The Binding of Isaac](https://store.steampowered.com/app/250900/The_Binding_of_Isaac_Rebirth/).

#### Features

- The game currently supports full player movement and a basic collision system (more on that below) as well as character animation.

- A rudimentary projectile shooting system has been added.

- Levels can be loaded into the game from a map-data file using a specified template.

#### Features in Development

- Enemy pathfinding using an implementation of the [A* Algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm) is currently in development.

- Improving player collision to prevent players from jittering upon running into a solid object.

- Full player animations for each possible action.

#### What I've Learned

Game development is a difficult process that requires an extraordinary amount of planning and patience. I've realized that spending some time up-front to set up tools, templates and environments is crucial for efficient development. 

> A few notable examples would be:

- Researching common data-structures and optimizations for a problem before jumping straight into code.

- Drawing out state diagrams for complex events or processes.

- Setting up a simple asset pipeline using Photoshop with custom templates, brushes, colour palettes and pixel grids matching the resolution of my sprites. 