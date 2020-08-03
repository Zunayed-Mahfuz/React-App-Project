# Vendor Connector - readme

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

**Vendor Connector** is an easy-to-use app whereby a person who is considering a wedding vendor can connect with people who have already used that vendor. They can hopefullly then gain more insight and make a more informed decision on whether on not to use them on their special day.

<br>

### Wireframes:


#### Desktop

- [Desktop landing](https://wireframe.cc/FooNMC)

- [Create Reviews](https://wireframe.cc/6Dlx53)

- [Read Reviews](https://wireframe.cc/XL2QiL)

- [Browse Reviews](https://wireframe.cc/1ecskb)

#### Mobile

- [Mobile landing](https://wireframe.cc/9Uf1yg)

#### Tablet

- [Tablet landing](https://wireframe.cc/E2Srqb)

<br>

### MVP

The **Vendor Connector**'s goal is simple: connect someone planning an event to those who have done it already: make them more informed about who they choose as vendors.

<br>

#### Goals

A user should be able to:
- Create a review for each of their vendors
- Be able to browse vendor reviews
- Be able to connect with the person who made the review

<br>

#### Libraries

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|   React Router   | Allows for different paths for components
|  Axios  |  Makes requests for Airtable data  |

<br>

#### Data


|    API     | Quality Docs? | Website       | Sample Query                            |
| :--------: | :-----------: | :------------ | :-------------------------------------- |
| Airtable |      Yes      | airtable.com | https://api.airtable.com/v0/appGtN1jraBuzwFTz/Table%201 |

<br>

#### Component Hierarchy


```
src
|__ assets/
      |__ fonts
      |__ images
|__ App.js
|__ Header.js
|__ Form.js
|__ SelectVendor.js
|__ DisplayVendor.js
|__ Browse.js
```

<br>

#### Component Breakdown


|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|   App    | functional |   n   |   n   | Backbone of the site - landing/navigation               |
|    Header    | functional |   n   |   n   | Site brand / links               |
|  Form  | functional |   y   |   n   | What the user must input to create reviews       |
|   SelectVendor    |   functional    |   y   |   n   | Pick what vendors to research further      |
| DisplayVendor | functional |   n   |   y   | Display selected vendor's reviews                 |
|    Browse    | functional |   n   |   y   | Browse all reviews |

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
| TOTAL               |          |     36 hrs      |     0 hrs     |     TBD     |

(* Denotes Post-MVP)

<br>

#### Helper Functions


|  Function  | Description                                |
| :--------: | :----------------------------------------- |
| capitalize | Capitalizes (e.g. - vendor names) |
| generateProperties | Generates listings |

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

> Looking forward to shpw my code snippet of the project that I am proud of.

### Code Issues & Resolutions

> I will use this section to list of all major issues that I encountered and what steps I can take to improve.
