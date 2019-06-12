# Web Design

This is a random collection of notes on web design. It will contain most everything that I think is worth being able to link to.

## URLs

- Use `/resource/mine` over `/resource/${myId}` for protected resources unless it is valid to see someone else's resource by their ID

## Lists

- In lists with clickable elements, when updating the underlying data set, hold the hovered-over item pinned to prevent misclicks

## React

- Do not abuse React components (and their lifecycle methods) to make them non-visual and use just say `componentDidMount`
