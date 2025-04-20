## Project One Algorithms and Data Structures:
#### Original: https://github.com/BraydonWoodward/CS300Submission
#### Enhanced: https://github.com/BraydonWoodward/CourseTreeRBT
#### Narrative:
This artifact is my enhanced Course Tree application, a self-balancing Red–Black Tree designed to manage an academic course catalog for ABCU's Computer Science department. Originally created in December 2023, I revisited and significantly improved the project in March 2025. In this updated version, I replaced the prior binary search tree implementation, which was prone to degeneration and stack overflows when handling sorted data, with a robust Red–Black Tree that leverages modern C++ smart pointers for safe memory management. I chose to include this project in my ePortfolio because it not only showcases my abilities in implementing advanced data structures and algorithms, but it also demonstrates a concrete understanding of object-oriented design, resource management, and performance optimization. Key components, such as tree rotations, insertion fixup, and efficient in-order traversal, show my competency in utilizing complex logic to maintain the tree’s balanced properties. The enhancements significantly improved the artifact by ensuring worst-case logarithmic performance, even with large datasets, and by mitigating common pitfalls like deep recursion errors.

The process of enhancing this artifact was both challenging and enriching. I began by examining the weaknesses of the original design. Specifically, the susceptibility to degeneration due to sorted input—and identified the Red–Black Tree algorithm as the optimal solution. Implementing smart pointers introduced a modern approach to memory safety in C++; however, it also required a careful adjustment of pointer semantics, particularly when managing parent-child relationships using std::weak_ptr for parent pointers to avoid cyclic references. Through iterative testing and incorporating feedback from my instructors, I refined the design, added thorough error handling for file I/O and user input, and ensured that each component functioned as intended. Although I feel confident in the improvements made, I recognize that further work could be done to extend the project's functionality, such as adding deletion operations to the tree. Overall, this project reflects my growth in software development and my ability to take feedback, iteratively improve my design, and implement sophisticated solutions in modern C++.
#### Course outcomes met:
- Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices
- Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals
- Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

### Screen Shots
#### Original BST (750 records)
![original BST (750 records)](/docs/assets/OriginalTestingResults750Records.png)
#### Enhanced RBT (750 records)
![enhanced RBT (750 records)](/docs/assets/EnhancedTestingResults750Records.png)
#### Enhanced RBT (2000 records)
![enhanced RBT  2000 records)](/docs/assets/EnhancedTestingResults2000Records.png)

## Project Two Software Design/Engineering and Databases: 
#### Original: https://github.com/BraydonWoodward/CS340
#### Enhanced: https://github.com/BraydonWoodward/AnimalShelterDashboard_Updated

#### Narrative:
I chose the Animal Shelter Dashboard as a key artifact for my ePortfolio because it shows how I turned a simple Python prototype into a full‑stack JavaScript application at the start of 2025. It now features a Node.js and Express backend connected to a MongoDB database, a React and Vite frontend, and Docker Compose for easy, repeatable deployment. Users can filter and search animal records by name, breed, or type, click a row to view details in a modal overlay with an interactive Leaflet map, and add new records through a “Create Animal” form that enforces required fields and unique identifiers.

I included this project because it highlights many skills I developed throughout the course. On the backend, I designed RESTful endpoints with async/await, set up Mongoose schemas with unique indexes for rec_num and animal_id, and handled duplicate‑key errors gracefully. On the frontend, I built responsive table and form components, managed global state with React Context, and learned to import Leaflet’s marker icons so they bundle correctly under Vite and Nginx. I also refined CSS for modal sizing and centering, and ensured numeric inputs convert to real numbers to avoid subtle bugs in filtering and calculations.

During development, I faced challenges like wiring up the form submit handler correctly, debugging container port bindings, and configuring persistent Docker volumes for MongoDB storage. I solved these by adding console logs, inspecting network requests in DevTools, and adjusting my Docker Compose file to use named volumes. This artifact fully meets course outcomes in full‑stack web development, database modeling, and containerization. In future iterations, I plan to add automated testing and performance optimizations to continue improving my skills.

# Education
- Southern New Hampshire University

# Workplace
- Workplace 1: 52 Creative (Audio, Visual, Lighting Integrations)
- Workplace 2: Remax Reinvented

## SNHU CS Capstone Code Review
Youtube Link: [SNHU CS Capstone Code Review](https://www.youtube.com/watch?v=pOqaEoRmagc)
