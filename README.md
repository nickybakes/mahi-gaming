# Game and Tool Development at MahiGaming
While working at MahiGaming from 2024-2026, I shipped 8 games and developed multiple internal tools to aid with and speed up development. Because of my NDA, I cannot provide explicit details or screenshots.

# Game Mechanics and Features
- Developed in Typescript within an internal game engine
- Worked with lead game designers to implement in-game mechanics and features
- Logic needed to sync with online services across many different iGaming platforms
- Game Logic needed to be performant on a large variety of devices
- Developed automated testing for features for QA teams to utilize

# Internal Tools and Plug-Ins
While shipping games, I would take note of pain points in the development process, and in between projects I would take in feedback from our teams to develop tools that solved these issues and sped up our processes.

Advanced Search
-
- Users can quickly search through all game objects, logic nodes, assets, and resources based on object type, properties, and references
- The Search tool would automatically organize results based on their flowgraph, type, and search relevancy
- Users can select searched objects or instantly jump to where that object is created and referenced in the game logic for debugging
- Massively sped up our debugging process

Copy, Cut, and Paste for Flowgraphs
-
- We utilize an internally developed flowgraph system for game logic, though the UX was clunky and slow
- Based on other flowgraphs and editors I have used, I implemented functionality such as Copy, Cut, and Paste
- Users can now select groups of nodes and copy, cut, and paste to more easily and more quickly create, duplicate, and organize game logic
- Massively sped up and eased our development process

Game Object Property Validation
- 
- Made the editor check for bad references and values in object properties and warn if there are any
- Was a necessary addition when implementing Copy/Paste as users could copy data between projects, which could result in broken references
- Helped make the editor UX more user-friendly and informative

Animation System for Complex Transformations
-
- Implemented a system for users to create multi-step paths/tracks that in-game objects can transform along
- When traveling along the path, the in-game object's transform properties would follow the path, meaning its position, rotation, and scale values were adjusted
- These paths/properties were designed to be easily created by artists in the editor/engine
- This lets artists see their work in real time in-engine rather than needing to import animations from an external tool
