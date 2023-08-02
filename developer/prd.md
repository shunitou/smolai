# Product Requirement Document

## Project Overview
This project involves creating a web-based classic Snake game, where the player controls a line (the snake) that grows longer with each point they obtain. The game is over when the snake hits its own body or the wall. 

## Scope
The implementation of this web app should be done using basic web technologies like HTML, CSS, and JavaScript. All of the code will be contained in a single file, named index.html.

## User Stories
1. As a user, I should be able to see the game on my web browser.
2. As a user, I should be able to control the direction of the snake using arrow keys on my keyboard.
3. As a user, when the snake eats the food, the length of the snake should increase by one block.
4. As a user, I should be able to see my score update in real-time as the snake eats food.
5. As a user, if the snake hits the wall or its own body, the game should end.
6. As a user, I should be able to restart the game after it ends.

## Game Logic
- The game is played on a grid-based map.
- The snake starts with a length of one block and grows by one block each time it eats food.
- Food appears at random locations.
- The snake cannot move in the opposite direction of its current movement.
- If the snake's head hits the wall or any part of its body, the game ends.

## Visual Design
- The game area should be a square grid, distinguishable from the rest of the page.
- The snake could be a different color than the game area background to be clearly visible.
- The food should also be distinguishable by having a different color than both the snake and the game area.
- There should be a score display area.

## Technical Requirements
1. The game area can be an HTML div element.
2. The snake can be represented as a series of div elements.
3. The movement of the snake can be achieved by adding or removing div elements and changing their position.
4. Collision detection for the walls and the snake's own body will be necessary.
5. An event listener will be needed to listen to the arrow keys on the keyboard to control the snake.
6. A mechanism for random food generation on the grid, not on the existing snake's body, is required.
7. A way to keep score and display it to the user is necessary.

## Limitations
- Since this will be a single-page, JavaScript based game, it cannot maintain its state if the page is refreshed.
- The game does not currently support mobile devices, since it is based on keyboard inputs.

## Future Considerations
- Mobile controls could be added for broader accessibility.
- High scores could be saved using local storage or a backend database.
- A settings page could be added to adjust game difficulty or aesthetics.
  
## Success Metrics
- The game starts when the webpage is opened.
- The snake responds accurately to keyboard inputs.
- The snake grows when it consumes food.
- The game ends and can be restarted when the snake hits its own body or the game boundary.

This is a basic outline for the product requirement document. Each section may need more detail based on the context and the requirements of the project.