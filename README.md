# Project-4# Full Stack Project

> The Project Planning section **should be completed** for your project pitch with instructors.
> To ensure correct Markdown, I recommend cloning this wiki and copy/pasting the raw template code.

## Overview

_**Project Title** Keep Fitness


## MVP

> Having a users linked to fitness posts and then being able to comment on what each user has done for each.


#### Wireframes

> Use the Wireframes section to display desktop, tablet and mobile views.

![Dummy Link](url)

- Desktop Landing

![Dummy Link](url)


#### Component Hierarchy

> Use this section to define your React components and the data architecture of your app.

``` structure

src
|__ components/
      |__ header
      |__ users
      |__ fitness
      |__ comments
      |__ nav
      |__ footer
|__ services/
      |__ api-helper

```

#### Component Breakdown

> Use this section to go into further depth regarding your components, including breaking down the components as stateless or stateful, and considering the passing of data between those components.

|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|    Header    | functional |   n   |   y   | _The header will contain the navigation and logo._               |
|  Navigation  | functional |   y   |   y   | _The navigation will provide a link to each of the pages._       |
|   fitness    | functional |   y   |   y   | _The contains each fitness post                                  |
|  comments    | functional |   y   |   y   | _The comment for each user on the fitness app                    |
|  api-helper  | na         |   n   |   n   | _The gallery will render the posts using cards in flexbox._      |
|  users       | functional |   y   |   y   | _being able to change the user profile and information           |
|    Footer    | functional |   y   |   y   | _The footer will show info about me and a link to my portfolio._ |

#### Component Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above.

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Header              |    L     |     1 hrs      |     0 hrs     |    0 hrs    |
| Nav                 |    M     |     2 hrs      |     0 hrs     |    0 hrs    |
| Fitness             |    H     |     3 hrs      |     0 hrs     |    0 hrs    |
| Comments            |    H     |     3 hrs      |     0 hrs     |    0 hrs    |
| Users               |    H     |     3 hrs      |     0 hrs     |    0 hrs    |
| footer              |    H     |     1 hrs      |     0 hrs     |    0 hrs    |
| Users               |    H     |     3 hrs      |     0 hrs     |    0 hrs    |
| css                 |    H     |    10 hrs      |     0 hrs     |    0 hrs    |
| TOTAL               |          |    26 hrs      |     ?         |     ?       |

> _Why is this necessary? Time frames are key to the development cycle. You have limited time to code your app, and your estimates can then be used to evalute possibilities of your MVP and post-MVP based on time needed. It's best you assume an additional hour for each component, as well as a few hours added to the total time, to play it safe._

<br>

### MVP Server (Back End)

#### ERD Model

> Use this section to display an image of a computer generated ERD model.

#### Data Heirarchy

> Use this section to display the database, table, and attribute heirarchy.

``` structure

database_db
|__ users/
|__ resources/
|__ posts/

```

<br>

***

## Post-MVP

> Use this section to document ideas you've had that would be fun (or necessary) for your Post-MVP. This will be helpful when you return to your project after graduation!

***

## Project Delivery

> The Delivery section should be expanded and revised as you work on your project.

## Code Showcase

> Use this section to include a brief code snippet of functionality that you are proud of and a brief description.

## Code Issues & Resolutions

> Use this section to list of all major issues encountered and their resolution, if you'd like.

***

