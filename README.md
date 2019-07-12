# Web Design

This is a random collection of notes on web design. It will contain most everything that I think is worth being able to link to.

## URLs

Do not make routes which are not supposed to be directly accessible by a URL / bookmarkable a URL.
Create a page for `/item/new` if accessing it allows you to create a resource. Do not create it if it depends on a user journey.
Do not make routes for things which could be modal windows / pages.

Do not use routes with the logged in user ID in them unless they should work from the perspective of other users (incognito).
Instead use `/me` or `/mine` if it's protected routes which are only validly accessed by the logged in user.
Use IDs for things where if me I see editable page and if someone else they see a viewable page.

## Lists

- In lists with clickable elements, when updating the underlying data set, hold the hovered-over item pinned to prevent misclicks

## React

- Do not abuse React components (and their lifecycle methods) to make them non-visual and use just say `componentDidMount`
