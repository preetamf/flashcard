
# FlashCard Generator

Flash Card Project Summary:

The Flash Card Project is a web application designed to help users create and manage flashcards for studying purposes. The project consists of two main pages:

1. Create Flashcard Page:
   - Users can create a main flashcard with a title, optional image, and description.
   - They can also add multiple terms to the flashcard, each with a title, definition, and optional image.
   - Users can dynamically add or remove terms, and edit their details.
   - Form validations and submissions are handled using the Formik library.

2. My Flashcards Page:
   - Displays the details of a specific flashcard, including its title and description.
   - Terms associated with the flashcard are shown on the left side.
   - Clicking on a term displays its details in the center, potentially in a carousel format for easy navigation.
   - Includes a share button to generate a modal with a link to the flashcard, allowing users to copy the link to the clipboard.

Overall, the Flash Card Project provides a user-friendly interface for creating, managing, and studying flashcards efficiently.


## Run Locally

Clone the project

```bash
  git clone https://github.com/preetamf/flashcard.git
```

Go to the project directory

```bash
  cd flashcard
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```


## Deployment

To build this project

```bash
  npm run build
```
Deployed on Netlify: https://preetamflashcard.netlify.app/


## Screenshots

![Dashboard](https://postimg.cc/vx5p515J)
![App Screenshot](https://postimg.cc/VSVQwPYV)
![App Screenshot](https://postimg.cc/dkZMtN3t)


## Tech Stack

**Client-side:** React, Redux, TailwindCSS, React-icons,
React Formik & Yup,
React-toastify



## Instruction to use
1. Open the flashcard generator.

2. Fill up all the input boxes without any Errors and click on the "Create" button.

3. For viewing recently created flashcards click on the "My flashcard" link this will show all flashcards you created recently.

4. For the Viewing Details of the flashcard click on the "view card" button it will redirect you to the flashcard details page where you take a look at your flashcard details.
## Authors

- [@preetamf](https://www.github.com/preetamf)

