# Project Plan (pasted from a google doc i worked on at home)

Liam Reilly

**Event:** Website Coding & Development

Our (My) project in one sentence:

My website is a lost and found portal that allows students and staff to report missing items, browse found items, submit ownership claims, and manage unclaimed property.

## 1. Features

| Feature | Need it serves | Group | Size |
|---|---|---|---|
| Users can browse and search found items using keywords. | Helps users find belongings that may have been lost. | Must-have | M |
| Users can filter found items by category, location, and date. | Makes it easier to find specific items. | Must-have | M |
| Students and staff can submit found items with descriptions, photos, and locations. | Allows people to report items they have found. | Must-have | L |
| Users can report lost items with descriptions and identifying details. | Helps connect lost items with items that have been found. | Must-have | M |
| Users can submit claims that administrators can review and approve or deny. | Helps prevent people from claiming items that aren't theirs. | Must-have | L |
| Finders or administrators can set private verification questions for claims. | Gives users another way to prove ownership of an item. | Should-have | M |
| The system can suggest possible matches between lost and found reports. | Helps users find items that may match their missing belongings. | Should-have | L |
| Administrators can view statistics and manage pending claims and item listings. | Makes it easier to manage the portal and keep track of its activity. | Should-have | M |
| Unclaimed items can automatically be archived after a set number of days. | Keeps old listings from cluttering the website. | Should-have | M |
| Users can receive email verification when submitting claims. | Adds another way to verify claims. | Stretch | L |

## 2. Rating Sheet Check

| Rating sheet line | Where my plan covers it |
|---|---|
| Separate HTML, CSS, and JavaScript files | The website will use separate files for HTML, CSS, and JavaScript. |
| Accessibility | I will use semantic HTML, descriptive labels, keyboard navigation, readable colors, and accessible forms. |
| Consistent pages | Pages will share the same navigation, layout, colors, and general styling. |
| Works on desktop, tablet, and mobile | I will use responsive CSS and test the website at different screen sizes. |
| Error-free interactivity | I will test the search, filters, forms, claims, and admin controls to make sure they work correctly. |
| No templates | All of the website's code and page designs will be made by me without using prebuilt website templates. |

## 3. Tools

| Option | Fit | Learn | Industry | Free | Offline | Total |
|---|---:|---:|---:|---:|---:|---:|
| HTML, CSS, JavaScript, and Node.js | 5 | 4 | 5 | 5 | 5 | 24 |
| Python with Flask and HTML/CSS | 4 | 3 | 5 | 5 | 5 | 22 |
| PHP, HTML, and CSS | 4 | 3 | 4 | 5 | 5 | 21 |

**Our choice and why:**

I chose HTML, CSS, and JavaScript with Node.js because I think they provide the flexibility needed for this project. Visual Studio Code will be my IDE, and Git will provide version control so I can keep track of changes. I plan to use JavaScript libraries when needed, but I want to keep the code modular and avoid adding unnecessary dependencies. I didn't choose Flask or PHP because I'm more familiar with JavaScript and would rather keep the project using one main programming language.

**Tech spike results:**

- HTML, CSS, JavaScript, and Node.js: [Add results from testing.]
- Python with Flask: [Add results from testing.]
- PHP: [Add results from testing.]

**Libraries, templates, and assets I'm planning to use:**

- HTML5, CSS3, and JavaScript.
- Node.js and Express for backend functionality.
- Additional libraries will be documented if I end up needing them.
- All website layouts, styling, and code will be original.
- No prebuilt website templates will be used.

## 4. Timeline

| Week | Feature or task |
|---|---|
| 6 | Sprint 1: Set up the website structure, navigation, and found-item browsing page. |
| 7 | Sprint 2: Add item posting, descriptions, photo uploads, and lost-item reporting. |
| 8 | Midpoint demo: Show the working website, browsing features, and initial forms. Collect feedback and identify anything that needs fixing. |
| 9 | Sprint 3: Add keyword searching, filters, claim submissions, and admin review. |
| 10 | Add input validation, error handling, and claim verification checks. |
| 11 | Work on a standout feature: automatic suggestions for matching lost and found items. |
| 12 | Clean up the code, fix inconsistencies, and improve accessibility and styling. |
| 13 | Test the website on desktop, tablet, and mobile. Fix remaining bugs and prepare the final version without adding new features. |

## 5. Risks

| Risk | What we will do |
|---|---|
| Backend features, especially claims and photo uploads, end up being more complicated than expected. | Start with simpler versions of these features and build on them once the basic system works. |
| The website doesn't work properly without internet or on competition devices. | Test it locally ahead of time and make sure the required dependencies and assets are available offline. |
| Team members are absent or don't understand parts of the code. | Keep the code organized, document important functions, and make sure more than one person understands how the main parts work. |

## 6. How we will know it works

1. A user can search for a found item using keywords and narrow the results with category, location, and date filters.
2. A user can submit a lost-item report or found-item listing, and the information appears correctly on the website.
3. An administrator can review a submitted claim, approve or deny it, and have the item's status update correctly.
