# Senior Portfolio

## Portfolio Overview
Welcome to my Senior Portfolio! I put this repository together to wrap up the "Writing in the Discipline" and "Signature Work" requirements for my time at St. Thomas. 

Instead of just picking a few random assignments, I chose three projects that I'm genuinely proud of and that really show how much I've grown as a developer. Inside, you'll find a mix of different technologies—from a React-based task manager to a full-stack fitness tracker, and even a webcam-controlled 3D swimming simulation. 

I feel like these projects do a great job of capturing the St. Thomas mission of using what we learn to build things that are actually useful and positive for others—whether that means helping someone stay organized, helping them hit their fitness goals, or just creating a fun, interactive experience.

## Swim Sim
**Repository:** https://github.com/dsnyder8/SwimSim-main/tree/main/SwimSim-main  
**Live link:** https://dsnyder8.github.io/SwimSim-main/  

**Overview:**  
Swim Sim drops the player into a stylized underwater environment rendered in 3D. The scene is built from a custom Blender-modeled ocean floor (exported as .glb) that tiles seamlessly in a 3x3 grid around the player, creating the illusion of an endless seabed. The world is populated with animated seaweed, schools of fish, and rising bubbles — all generated procedurally at runtime.
What sets Swim Sim apart is its control scheme: the default input method uses ml5.js HandPose and FaceMesh models to track the player's hands and head through their webcam. Players swim forward by bringing their hands together (thumbs down) and then spreading them apart, mimicking a breaststroke motion. Head turning is mapped to camera rotation via facial landmark analysis, so looking left or right in real life steers the camera in-game. A keyboard/mouse mode is also available as a fallback.

---

## React Task Manager
**Repository:** https://github.com/dsnyder8/IntroductionToReact  

**Overview:**  
Built for CISC 375, this task manager serves as a practical exploration of React's core features. Using React 19.2 and Vite, the application provides a clean, responsive interface where users can add, view, complete, and delete their daily tasks. 

Beyond the basic functionality, the project was an exercise in modern React architecture. It focuses on breaking down the UI into modular JSX components (like the Header and Body) and managing form data through controlled inputs. Under the hood, it relies heavily on `useState` hooks for managing the task list, enforcing best practices like immutable state updates and using stable keys for efficient list rendering.

---

## Fitness API
**Repository:** https://github.com/dsnyder8/WebDevAssignment4  

**Overview:**  
The first part of this project involved building a Fitness API using a RESTful backend built with Node.js, Express, and MongoDB. This API provides a system for managing a user's fitness data, focusing on individual exercises and daily/weekly routines for a more personalized workout experience. This backend served as the foundation for the second part of the project. The second part involved making the Fitness API full-stack by building a working web application centered around exercise management and weekly workout scheduling. The application allows users to register and log in securely using JWT-based authentication, and once authenticated, users can create, edit, delete, and view their workout exercises. Along with these CRUD features, a search bar allows users to find specific exercises by description, and a filter dropdown allows users to sort exercises by day of the week or exercise category. Overall, the application supports all three backend models and uses JavaScript and HTML to display everything on the front end.
