# React Basketball Player Cards

This project displays basketball player cards using a React component called `BasketballPlayerCard`. The cards show the player's image, name, position, and various stats.

## Project Structure

- `src/`
  - `components/`
    - `BasketballPlayerCard.js`
    - `BasketballPlayerCard.css`
  - `App.js`
  - `App.module.css`
  - `index.js`
- `public/`
  - `index.html`
- `README.md`
- `package.json`
- `.gitignore`

## Component Details

### `BasketballPlayerCard`

This component displays information about a basketball player, including their image, name, position, and stats.

#### Props

- `name` (string): The player's name.
- `image` (string): URL to the player's image.
- `position` (string): The player's position.
- `stats` (object): An object containing the player's stats (e.g., `{ pointsPerGame: 25.4, assistsPerGame: 7.1, reboundsPerGame: 10.5 }`).

### Example Usage

```jsx
<BasketballPlayerCard
  name="LeBron James"
  image="https://example.com/lebron.jpg"
  position="Forward"
  stats={{
    pointsPerGame: 25.4,
    assistsPerGame: 7.1,
    reboundsPerGame: 10.5,
  }}
/>
