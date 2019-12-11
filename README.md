![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) 

# PROJECT 2: Your React App

Congratulations everyone! You're nearly done with Unit 2, which means you've conquered the basics of HTML, CSS, and Javascript, and now we get to kick it up a notch with modular and modern front-end applications using the React framework!

As with P1, the Unit 2 Project is a chance to be creative and build something you can be proud of. You will be working individually on this project, but don't worry– we know stateful versus stateless can be very confusing at first, but that doesn't mean you'll be _persona non grata_ for this project. We'll be helping you out along the way.

Remember to have fun and _read all the directions before you start_!

<br>

## The MVP Requirements

**In order to pass, these are ALL required.** Please note, we will be less willing to make compromises here. By project 2, you're well on your way to becoming **real** devs, and attention to detail, consistency, and using convention in your code is important.

### Planning

- Have a **thoroughly** developed `README.md` file. (Refer below to _"Step 5: Pitch Your Project Idea"_ for more.)

### React

- Be a working, interactice React app, built using `create react app`.
- Utilize React Router, installed via NPM. 
- Have at least 6 separate, rendered components.
- Implement an organized and understandable React file structure.
- Utilize functional and class React components appropriately.
- Use Axios to consume data from an third party API, and render that data in your components. (Remember, many lists of good API's are listed in the #Resources section.)
- Use **only** React for DOM Manipulation.

### Styling

- Be styled with CSS.
- Use flexbox (`display: flex`) or CSS Grid.
- Implement responsive design on 3 screen sizes (including desktop) using 2 media queries (tablet and mobile).
  
### Linting

- Indent properly.
- Utilize high-quality, semantic variable names.
- Follow `camelCase` and `kebab-case` conventions.
- Remove unnecessary boilerplate React files and code.
- Remove all `console.log()`s and commented out code (functional notes and comments are okay).

### Deployment

- Deployed via GitHub & on Surge.

### Procedural

- Have GitHub commits (documenting good progress) **every day**.

<br>

## The Post-MVP

Achieve your MVP with time to spare? Try aiming for some stretch goals. (The following are not mandatory for your second app.)

- Incorporate React component libraries for design and styling. (Instructors must sign off on this.)
- Get input from a UX student on how to make your app have intuitive UI and design.

<br>

## The Presentation

Finally, to get you familiar with presenting your work to audiences, the last requirement: 

- Present your app to your cohort. Be sure to show it's functionality and features, including responsiveness. (Chrome Dev Tools' _Device Toolbar_ is helpul for this.)

<br>

# GETTING STARTED

##  STEP 1. Remember to Read All Directions BEFORE You Start

_We'll know if you don't._

<br>

## STEP 2. Make A New Repo

You will start by creating your project repository on your **personal** GitHub. _(Refer to the Resources section below if you need help with this.)_

<br>

| **DO**                              | **DO NOT**                         |
| ----------------------------------- | ---------------------------------- |
| ... Use your personal GitHub.       | ... Use your Enterprise GitHub.    |
| ... Make a new repo through GitHub. | ... Clone this SEI repo.           |
| ... Make the new repo public.       | ... Initialize with a ReadMe file. |

<br>

## STEP 3. Research and Choose Your API

You have the freedom to choose an API that aligns with your interests or goals, but remember our requirements from P1.

  * Use an API that is public, free, and– if an API key is required– that accepts that key in the URL or header. If it requires membership, granted access, payment, or OAuth, it will likely take too much time to gain access to the data, both to get your keys and to program the requests.
  * Second, you must prove you can retrieve and consume data at project pitch time to be approved. **If you cannot do this, we will tell you to find another API.**

<br>

| **DO**                                                    | **DO NOT**                                  |
| --------------------------------------------------------- | ------------------------------------------- |
| ... Have some fun in choosing an API.                     | ... Choose a terrible API.                  |
| ... Consider the clarity of the API's data structure.     | ... Choose a terrible API.                  |
| ... Consider the thoroughness of the API's documentation. | ... Seriously, don't choose a terrible API. |

<br>

As you saw for P1, there are _literally_ hundreds, if not thousands, of APIs that have been tested, used and abused by previous students. Start with those lists and it'll make your life easier. 

Refer to the Resources section below for suggestions and lists of available APIs; if you find one not on this list that you'd like to use, feel free, just remember the above requirements.

<br>

## STEP 4. Wireframe Your App

You can make your wireframes as lo-fi and hand-drawn, or as hi-res and computer-generated, as you'd like. Just prove that you've thought about what this layout will require. Include desktop, tablet, and mobile screen sizes.

<br>

##  STEP 5. Pitch Your Project Idea

Before you start coding away, you must meet with an instructor to get your ideas approved. We will have 8 minute pitches in which you'll present your ideas. **You must have your ideas prepared and written up in a ReadMe file, including all of the following items, to get approved.**

1. **Title:** A working title for your app. (Feel free to have some fun with this.)
2. **Description:** 4 to 5 sentences in non-technical speak summarizing the features, functions, and goals.
3. **Wireframes:** Mockups of your app on desktop, tablet, and mobile.
4. **Component Heirarchy:** A visual tree of your components, depicting the parent/child relationships, as well as an indication of which will be class components, requiring state, and which will be functional components, taking props.
5. **API:** The API you will be using and a link to the documentation.
6. **MVP:** Your goals for MVP, including the minimum, need-to-have features of your app.
7. **Post-MVP:** Write out what your goals are for post-MVP, including nice-to-have features that you would like to implement once your MVP is complete. (If you plan to use a component library, please link that here as well.)
8. **SWOT Analysis:** Heading into project week and with all your planning in mind, consider your Strengths, Weaknesses, Opportunities, and Threats as they relate to your final project. How will you overcome your weaknesses and threats?
   
> Optionally, include a final section, your `Code Showcase`. Put snippets you're proud of here, and let your viewers know when you've written brag-worthy code!

> For putting wireframes in your ReadMe, we recommend uploading to Imgur, then linking the file directly into your markdown using the `!(imageAlt)[imageURL]` format. The imageURL must be a direct link ending with the file format, such as `.png`.

<br>

| **DO**                                  | **DO NOT**                        |
| --------------------------------------- | --------------------------------- |
| ... Create a ReadMe file locally.       | ... Leave your ReadMe empty.      |
| ... Add, commit & push your ReadMe.     | ... Leave your GitHub repo empty. |
| ... Have your Pitch materials prepared. | ... Waste the instructors' time.  |

<br>

##  STEP 6. Get Hacking

Did you read this far?! If so, we're getting sneaky and hiding these before the end of the repo. So do us a favor: Make the very first thing in your Project **Pitch** ReadMe a funny/happy/cute gif of cheetahs.

### Remember what project week looks like?

All students will be grouped into a Squad. Every morning and evening, squads will do standups, where each person will answer:

1. What did you work on?
2. What will you work on?
3. What's something you expect will block your progress?

After this, we'll go around the squad once more, indicating what "percent MVP" you are at with your project.

### Getting Support

When you experience issues with your code, once again, you will need to use the GitHub Issues tab. The Issue Ticket templates help you observe, research, and attempt to resolve your issue. If there's still no resolution, submit and slack the issue ticket your squad leader to reserve time to troubleshoot together.

<br>

# MOAR RESOURCES

## Some Available APIs

- Star Wars: https://swapi.co/
- Weather: https://openweathermap.org/api
- News: https://newsapi.org/
- Giphy: https://developers.giphy.com/
- Pokemon: http://pokeapi.co/
- Card Deck: https://deckofcardsapi.com/
- Google Books: https://developers.google.com/books/
- City of Chicago: https://data.cityofchicago.org/
- Beer: https://www.brewerydb.com/developers
- Chuck Norris: http://www.icndb.com/
- Rick and Morty: https://rickandmortyapi.com/documentation/#rest
- Word API: https://www.wordsapi.com/

- For more comprehensive lists, check:
  - https://github.com/toddmotto/public-apis
  - https://github.com/abhishekbanthia/Public-APIs
  - https://rapidapi.com/

## Templates

- [Project ReadMe Template](https://github.com/mishakessler/class-resource-template/blob/master/templates/Template_Project-README.md)
- [Project Issue Ticket Template](https://github.com/mishakessler/class-resource-template/blob/master/templates/Template_Project-Issue-Ticket.md)

## Relevant Guides

- [GitHub Docs: Create A New Repo](https://help.github.com/articles/create-a-repo/)
- [React Router Training Docs](https://reacttraining.com/react-router/)

## Sample Projects & Their Readme's

<br>

# RECOMMENDATIONS

_(From previous survivors of project week.)_

> "This is a nice chance to make a portfolio piece, but you don't expect perfection. After graduating the SEI, no matter how great your project is now, you will want to return to it to improve and polish, before recruiters and potential employers see it."

> "Manage your expectations. Have a clear MVP goal and stick to it. If you're doing something that has nothing to do with your end goal, stop it. Also, try to just get your project working and improve it from there. Don't try to make it perfect the first time because you'll probably be unsuccessful. Get it working, make it better, repeat."

> "Mobile-first design, stick to your wireframes; it’s stressful to redo your whole CSS and lose precious project time."

> "Narrow your scope, especially if you’re chasing down a specific feature that you’ve never implemented.  Treat it as a chance to learn by doing and most importantly: build something you are happy to claim ownership of."

> "Don’t try too hard. Really. Do something that’s achievable and put cool graphics and styling on it."

# PLAGIARISM

Remember. We have a **zero tolerance policy** towards plagiarism. More on our plagiarism policy can be found in our course wiki's [plagiarism page](https://github.com/mishakessler/class-resource-template/blob/master/guidelines/Guidelines_Plagiarism.md).
