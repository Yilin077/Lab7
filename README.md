1)Within a GitHub action that runs whenever code is pushed


Because running automated tests within a GitHub Action on every push ensures that the code is continuously tested during development. This catches bugs early, prevents broken code from being merged into main branches, and helps maintain code quality and stability throughout the development cycle. It also helps teams work more confidently and collaboratively by automatically verifying each contribution before it's deployed or reviewed.

2)No. End-to-end (E2E) tests are designed to simulate user interactions with the application and test the system as a whole. If check whether a specific function returns the correct output, that is better done with unit tests
3)Navigation Mode: This mode simulates a full page load, including navigation to the URL, running scripts, and measuring performance metrics like load time, interactivity, and layout stability. It's ideal for testing the user’s first visit experience.

Snapshot Mode: This captures the current state of a page without reloading it. It’s useful for testing specific views or components of a page (like a modal or a dynamically rendered section) for things like accessibility, SEO, and best practices, but not performance.
