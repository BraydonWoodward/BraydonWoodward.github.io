## Project One Algorithms and Data Structures:
#### Original: 
https://github.com/BraydonWoodward/CS300Submission

#### Enhanced: 
https://github.com/BraydonWoodward/CourseTreeRBT
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
#### Original: 
https://github.com/BraydonWoodward/CS340

#### Enhanced: 
https://github.com/BraydonWoodward/AnimalShelterDashboard_Updated

#### Narrative:
I chose the Animal Shelter Dashboard as a key artifact for my ePortfolio because it shows how I turned a simple Python prototype into a full‑stack JavaScript application. It now features a Node.js and Express backend connected to a MongoDB database, a React and Vite frontend, and Docker Compose for easy, repeatable deployment. Users can filter and search animal records by name, breed, or type, click a row to view details in a modal overlay with an interactive Leaflet map, and add new records through a “Create Animal” form that enforces required fields and unique identifiers.

I included this project because it highlights many skills I developed throughout the course. On the backend, I designed RESTful endpoints with async/await, set up Mongoose schemas with unique indexes for rec_num and animal_id, and handled duplicate‑key errors gracefully. On the frontend, I built responsive table and form components, managed global state with React Context, and learned to import Leaflet’s marker icons so they bundle correctly under Vite and Nginx. I also defined global CSS for consistency across multiple devices.

During development, I faced challenges like wiring up the form submit handler correctly, debugging container port bindings, and configuring persistent Docker volumes for MongoDB storage. I solved these by adding console logs, inspecting network requests in DevTools, and adjusting my Docker Compose file to use named volumes. 

There are still a few updates I would like to add to make it a robust and all‑around better application. First, I plan to implement user authentication and role‑based access control so that only authorized staff can add or modify records. Next, I want to expand the search interface with multi‑field filtering, autocomplete suggestions, and fuzzy matching to help users find animals more quickly. Finally, I’ll polish the UI by adding responsive layout refinements, accessible form labels and keyboard navigation, and a refined theme design. These enhancements will not only improve security and usability but also elevate the overall user experience.

#### Course outcomes met:
- Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science
- Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts
- Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals
- Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources

### Screen Shots
#### Animal Dashboard Webpage
![Animal Dashboard](/docs/assets/AnimalDashboard.png)
#### Animal Modal
![Animal Modal](/docs/assets/AnimalModal.png)
#### Create Animal Modal
![Create Animal Modal](/docs/assets/CreateModal.png)

## SNHU CS Capstone Code Review
Youtube Link: [SNHU CS Capstone Code Review](https://www.youtube.com/watch?v=pOqaEoRmagc)

## Professional Self-Assesment 
As I near the completion of my Computer Science program, I reflect on how the coursework and personal projects have significantly shaped my professional goals and technical abilities. The development of this ePortfolio has allowed me to showcase a range of skills and experiences, demonstrating both my technical expertise and my growth as a professional.

#### Strengths and Professional Growth
One of the most significant challenges I encountered during my projects was time estimation. When migrating the animal shelter dashboard from Python to Node.js, I struggled to gauge how much of the dashboard I could realistically recreate within the given time constraints. I had to balance work, life, and school responsibilities, which made it difficult to add the level of functionality and refinement I initially envisioned. This project taught me the importance of prioritizing features and focusing on core functionality first, which is a valuable lesson in both software development and time management.

Additionally, my work on enhancing the Course Tree project—by transitioning from a binary search tree to a Red-Black Tree—allowed me to deepen my understanding of algorithms and data structures. The Red-Black Tree improvement optimized performance, and my addition of smart pointers and error handling demonstrated my focus on writing robust, maintainable code. These enhancements were not just technical improvements but also key learning moments in memory management and ensuring the stability of the application.

#### Collaborating and Communicating in a Team Environment
In addition to the technical challenges, I also faced personal growth moments in collaboration and communication. One of the most impactful experiences was my role as the social media ambassador for the Computer Science club. While I was passionate about the club's mission, I found it difficult to align with the president, who lacked the same level of enthusiasm. This created challenges in motivating the team, but I did my best to stay engaged and focused on the club’s goals. This experience reinforced the importance of communication and maintaining energy, even in less-than-ideal circumstances. It also highlighted the value of team alignment and the challenges that come with working in diverse team environments.

#### Learning from Agile Development
A major turning point in my development process was learning about agile development. I used to believe that I needed to design and build an entire program before starting the development process. However, through the agile methodology, I learned that an iterative approach—building in small, manageable stages and refining as you go—is far more efficient. This realization has changed how I approach software development, particularly when working on large, complex projects. It also gave me confidence in rapid prototyping and allowed me to adapt more quickly to changing requirements.

#### Full-Stack Development and Real-World Application
My work on the animal shelter dashboard migration to Node.js and React has significantly improved my full-stack development skills. Beyond this project, I plan to adapt the dashboard into a tool for breeding dogs and puppies, which will help streamline tracking for my wife’s business. This transition aligns with my professional goal of creating AI-powered solutions that simplify complex tasks and free up time for people to focus on what they love. This project not only allowed me to hone my technical skills but also gave me the opportunity to solve a real-world problem, bridging my technical knowledge with tangible benefits for others.

#### Professional Aspirations
As I approach the end of my program, my goal is to gain as much practical experience as possible. I aim to create software or start a company that delivers advanced AI solutions to everyday users. I believe that AI has the power to make life easier and more fulfilling, and my vision is to simplify and make these technologies more accessible. The experience I’ve gained through my coursework and projects has provided a solid foundation for pursuing this goal, and I am excited to apply these skills in a professional setting.

#### Artifacts in the Portfolio
The artifacts included in this portfolio reflect the full spectrum of my development as a computer scientist. My work with data structures like the Red-Black Tree, along with my full-stack development of the animal shelter dashboard, demonstrate my ability to handle both the foundational and modern aspects of software engineering. Each project shows my attention to detail, my ability to adapt and refine my work, and my commitment to building scalable, secure, and efficient applications.

The combination of these technical projects, paired with the lessons I’ve learned about collaboration, time management, and iterative development, has prepared me to step into the next phase of my career with confidence. I look forward to leveraging these skills in the real world and continuing to grow as a software developer and innovator.

# Education
- Southern New Hampshire University

# Workplace
- 52 Creative (Audio, Visual, Lighting Integrations)
- Remax Reinvented


