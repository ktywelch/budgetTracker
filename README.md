# BudgetTracker

The BudgetTrakcer application utilizes a mongo database and mongoose and code provided with added PWA implementation to enable a user to create and track 
expense through a budget tracking application. If the application goes offline the user will still be able to enter items and when the system comes back online
the entries will be added to the  mongo db server when the connection is reestablished.

[Budget tracker application can be found on github repository ](https://github.com/ktywelch/budgetTracker)

## Table of contents
* [Design](#Design)
* [Installation](#Installation)
* [Usage](#Usage)
* [Technologies](#Technologies)
* [Contributions](#Contributions)
* [License](#License)

## Design
The design utilizes a server, controllers, DB and that utilize express and mongoose to create a web site that will  allow the user to track budget in a database and chart the entires.

The application is deployed on [Heroku at budgettrak-kw.herokuapp.com](https://budgettrak-kw.herokuapp.com/).

## Database:

Is is NoSQL DB that creates and utilizes a transactions collection to track budget items.  


## Installation
Assumptions prior to installation that the user has installed MongoDB community edition and installed and is familiar with starting MongoDB services. For additional details on install MongoDB and tools please refer to the [MongoDB Community Edition site.](https://www.mongodb.com/try/download/community) 

The installation process is a download of git source, using npm install to install required modules based on the package.json file included in the same directory as the application.


## Usage
To start the application run:

```node server.js```
    or 
``` npm start ```

Below is  gif image of the user interface.

![](./public/images/fitness.gif)


## Technologies
* MongoDB NoSQL Database Server
* Robo 3T
* Node.js
* NPM modules express, mongoose, router, views, bootstrap & HTML
* Code provided by Instructor

## Contributions - Study peers
* Sam Ayler
* Vincent Gines
* Albert Cheng
* Lucah Endicott
* Sean Melody

## License
ISC License (ISC)


Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
