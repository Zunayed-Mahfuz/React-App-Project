# Aashiyaan vacation Rentals - readme

- [Project Planning](#Project-Planning)
  - [Overview](#Overview)
  - [Wireframes](#Wireframes)
  - [MVP](#MVP)
    - [Goals](#Goals)
    - [Libraries](#Libraries)
    - [Data](#Data)
    - [Component Hierarchy](#Component-Hierarchy)
    - [Component Breakdown](#Component-Breakdown)
    - [Component Estimates](#Component-Estimates)
    - [Helper Functions](#Helper-Functions)
  - [Post-MVP](#Post-MVP)
- [Project Delivery](#Project-Delivery)
  - [Code Showcase](#Code-Showcase)
  - [Code Issues & Resolutions](#Code-Issues--Resolutions)

<br>

## Project Planning

<br>

### Overview

Aashiyaan Homes can be used on both desktop and as well as on mobile device. Users can use this to rent as well as list their properties on this app. Anyone can use their own data to create listings and show the descriptions of their properties and can rent it using this app.

<br>

### Wireframes:


#### Desktop

- [Desktop landing](https://wireframe.cc/pro/pp/603308272363460)

- [Create Listing](https://wireframe.cc/pro/pp/603308272363460)

- [Rentals](https://wireframe.cc/pro/pp/603308272363460)

<br>

### MVP

Aashiyaan vacation Rental's goal is to provide people with easy access to list their houses or apartments like Airbnb as vacation rental place as well as other users can also rent using this app.

<br>

#### Goals

A user should be able to:
- Create a lisitng of their new properties for people to rent from them.
- Be able to browse different listings and see their descriptions.

<br>

#### Libraries

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|   React Router   | Allows for different paths for components
|   Axios  |  Makes requests for Airtable data  |

<br>

#### Data


|    API     | Quality Docs? | Website       | Sample Query                            |
| :--------: | :-----------: | :------------ | :-------------------------------------- |
| Airtable |      Yes      | airtable.com | https://api.airtable.com/v0/appQ5OD0NipfBhQT6/Properties/recyIknXa7br2lzVt |

<br>

#### Component Hierarchy


```
src
|__ components/
      |__ Banner.js
      |__ Featuredlisting.js
      |__ Banner.js
      |__ Navbar.js
      |__ Marketplace.js
      |__ Title.js
      |__ images
      |__ FeaturedListing.js
|__ pages/
      |__ Error.js (will show 404 if the listing is not there)
      |__ Home.js
      |__ Rentals.js (will show listings of the newly added properties)
      |__ SingleRoom.js (will show the description of individual listing)
      
```

<br>

#### Component Breakdown


|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|   App    | functional |   n   |   n   |  Landing/navigation navbar              |
|    Header    | functional |   n   |   n   | Site brand / links to navigate to other pages              |
|  Navigate to listings  | functional |   y   |   n   | Add listings and update listings       |
|   Featured listings    |   functional    |   y   |   n   | Click on featured listings to see descriptions.      |

<br>

#### Component Estimates


| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Basic HTML     |    L     |     1 hrs      |     0 hrs     |    TBD    |
| Basic CSS | L | 4 hrs | 0 hrs | TBD |
| Create CRUD Actions |    H     |     4 hrs      |     0 hrs     |     TBD     |
| Display listings to browse from airtable | H | 2 hr | 0 hrs | TBD |
| Advanced CSS | L | 10 hrs | 0 hrs | TBD |
| Responsive Design | H | 8 hrs | 0 hrs | TBD |
| Update listings | L | 2 hr | 0 hrs | TBD |
| TOTAL               |          |     31 hrs      |     0 hrs     |     TBD     |

(* Denotes Post-MVP)

<br>

#### Helper Functions


|  Function  | Description                                |
| :--------: | :----------------------------------------- |
| capitalize | Capitalizes (e.g. - Listings names) |
| generate properties listing | Generates listings |

<br>

### Post-MVP


It would be nice if the user would be able to:
- Add their listings on the site directly from their database.
- View multilpe cities and locations where they can upload their listings.
- Potential clients can make earnings from their listing from using this app.
- Add trackers of their lisitngs where they can track how much they made from their listings.



<br>

***

## Project Delivery

### Code Showcase

> Looking forward to show my code snippet of the project that I am proud of.

### Code Issues & Resolutions

> I will use this section to list of all major issues that I encountered and what steps I can take to improve.
