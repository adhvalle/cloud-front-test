## Circutor Technical Test

This is a very simple application that shows some energy data Helsinki buildings from 1st January 2021 to around 28 Feb 2022.

It has an API written in GO and a frontend written in React.

## Launch

Clone/Fork the repo with git clone <url>
Build the docker containers and launch the project with:
```sh
docker-compose up --build
```

The api is accessible on `http://localhost:1234/docs/index.html`
The frontend is accessible on `localhost:3001`

## Tasks

- Implement an error message when login fails
- Implement a small test for this new feature

Feel free to implement any other improvement as long as you write a test for it.

## List Redflags

Write here all red flags that you find in the code. Any examples that would stop a code review. If you want to fix some of them, go on.

* Use `form` label and preventDefault event to handle forms data.
* Create `hooks` and try to reuse common functions, for example email validation.
* Use `try catch`.
* Avoid using `callbacks` functions to manage promises.

## How you would make this application maintainable and scalable

Write here all the steps you would take.

* Solid linters configuration to give a consistent code.
* Add **TypeScript**, it helps to create documentation and helps to keep the code consistent.
* Create a global state in the app.
* Create data models, it helps to manage global state.
* Organize project files and create a solid folder organization.
* Build a custom component library.
* I would use **Tailwind** if the requirements allow it, it helps to keep the css consistent.
* Decouple your logic from components with **hooks**.
* Keep up the testing coverage.
* Put in practices clean code and good practices for javascript (SOLID, DRY) and CSS.
* Avoid using thirds parties libraries unless they are justified.

## Test submission

Please, submit this test as a new repository (a fork or a new one) in any free platform you want (bitbucket, gitlab, github, ..)