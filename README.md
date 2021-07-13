# NetConstruct React Developer Assessment

**NetConstruct React Developer Assessment**
_by Marc Joyce_

**Requirements**

- Retrieve the data from the mock API.
- Output the data in a list, including properties from the data that are appropriate for a list view.
- Implement a category filter - this can be single or multi-select.
- Implement pagination - this can be traditional numbered pages or "load more". (I completed this requirement by displaying a subset of the API data as it was a limited dataset)
- Use semantic markup where possible.
- Create a responsive layout with HTML and CSS.
- Use client-side routing to create a "detail" page.
- Persist filter state in the query string.
-  Use a CSS preprocessor or CSS-in-JS rather than plain CSS.

**Non-filtered list**
![Screenshot (48)](https://user-images.githubusercontent.com/60116589/125422467-b0a5ff29-5192-40c3-b994-f76dd7face0d.png)

**Filtered List**
![Screenshot (50)](https://user-images.githubusercontent.com/60116589/125421472-91e6f325-e3f4-463f-a181-e6947c545ed0.png)

**Filter by search**
![Screenshot (51)](https://user-images.githubusercontent.com/60116589/125421615-0b593bf0-bad5-40cd-a1f5-89d9a23c25f7.png)

**Detail Page & URL client side routing via React Router**
![Screenshot (52)](https://user-images.githubusercontent.com/60116589/125421780-704f8065-940a-4ae1-b116-5cf02d3e85eb.png)

**Responsive Design**
![Screenshot (53)](https://user-images.githubusercontent.com/60116589/125421972-d5dbb270-25f7-4b3c-a1d1-9daba5c6c660.png)
![Screenshot (54)](https://user-images.githubusercontent.com/60116589/125422042-3daf8a48-142e-48cf-9c85-9b8a83353a24.png)





## Overview

The purpose of this assessment is to demonstrate:

1. An understanding of React syntax
2. Working with an API
3. Storing and manipulating React state
4. Structuring an application with multiple components
5. HTML and CSS ability
6. Responsive web development ability

### Prerequisites

In order to run the provided solution the following software will need to be installed:

- NodeJS (LTS) [here.](https://nodejs.org/en/)
- A code editor (We recommend VS Code [here.](https://code.visualstudio.com/))

### Setup

1. Fork and clone the repository or download and extract the ZIP file [here.](https://github.com/netconstruct/react-developer-assessment/archive/master.zip)
2. Open the repository folder and install the dependencies using `yarn` or `npm install`.
3. Run the development server using `yarn start` or `npm start`.

The repository contains a `App.jsx` file inside the `components` folder; this should be the starting point for your exercise. Please feel free to create more components to structure your app in a logical manner.

The repository also contains an API endpoint mocked using MirageJS. This can be accessed when running the development server at the URL `/api/posts`.

We would love to see code comments to help explain your approach and thought process, this will also be discussed in a follow-up technical interview.

Finally, the use of third party libraries and/or components is permitted - and in some cases encouraged. However, please ensure that you are still demonstrating the skills we have outlined above.

### Requirements

These are the minimum requirements for the exercies:

1. Retrieve the data from the mock API.
1. Output the data in a list, including properties from the data that are appropriate for a list view.
1. Implement a category filter - this can be single or multi-select.
1. Implement pagination - this can be traditional numbered pages or "load more".
1. Use semantic markup where possible.
1. Create a responsive layout with HTML and CSS.

### Additional Exercises

If you have time then demonstrating any of the following would be considered as a bonus:

1. Use client-side routing to create a "detail" page.
1. Persist filter state in the query string.
1. Include animated transitions between application state, e.g. when filtering.
1. Convert the application to use TypeScript instead of JavaScript.
1. Use a CSS preprocessor or CSS-in-JS rather than plain CSS.

## Submission

Please submit your completed exercise either by supplying the URL of your forked repository or by including a ZIP archive of your local folder - please ensure you **do not** include the `node_modules` folder.
