Prompts Log - Sprint 05: Task Management Board

To accelerate the development process, understand state-driven architecture, and ensure my component logic met the engineering requirements, I utilized AI (Gemini) during this sprint. Below is the log of the prompts used:

Prompt 1

Tool Used: Gemini
Prompt: "In React, if I am building a Kanban board with To-Do, In-Progress, and Done columns, is it better to use 3 separate useState arrays or one single array of objects?"
Help Received: Learned the importance of the Single Source of Truth principle. Understood how managing a single master array of objects and filtering them dynamically by a `status` property is far more efficient than maintaining and syncing three separate state arrays.

Prompt 2

Tool Used: Gemini
Prompt: "I have an array of task objects in React state. How can I write a function to change the 'status' property of a specific task (by ID) from 'todo' to 'inProg' using the map() function?"
Help Received: Understood how to safely mutate state in React without directly manipulating the DOM or mutating the original array. Learned to use the `.map()` function to create a fresh array with the updated task object, ensuring React triggers a proper re-render.

Prompt 3

Tool Used: Gemini
Prompt: "Can you give me a simple code snippet showing how to pass a delete function from a parent App component down to a child TaskCard component using prop drilling?"
Help Received: Grasped the core concept of component architecture and prop drilling. Learned the correct syntax for extracting UI into a reusable child component and passing mutator functions (like delete or move) from the parent state down via props.

Prompt 4

Tool Used: Gemini
Prompt: "What is the best way to create a 3-column layout using CSS flexbox where each column takes up equal width and has a little gap in between?"
Help Received: Resolved UI architecture blockers by utilizing modern CSS Flexbox. Learned how to easily create a responsive, evenly spaced 3-column layout for the To Do, In Progress, and Done sections without using complex grid systems.
