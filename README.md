Project done in 2nd year. <br>
Subject - Software design using Design Patterns 

GeRuMap Mind Map Application
Overview

The GeRuMap is a comprehensive application for creating and managing mind maps, utilizing various design patterns to enhance functionality and user experience. It's structured in weekly tasks, each adding significant features and employing specific design patterns for robustness and scalability.
Design Patterns

    Singleton Pattern: Used in the main window implementation to ensure a single instance of the application.
    Composite Pattern: Applied in the MapRepository component to manage mind maps and their elements.
    Factory Method Pattern: Utilized for creating nodes in MapRepository, providing flexibility in node creation.
    Observer Pattern: Employed to synchronize the MapRepository with the UI components, ensuring real-time updates in the UI.
    Command Pattern: Implemented for undo/redo functionalities, allowing users to revert or reapply actions.
    State Pattern: Used for managing different states of the application, like adding concepts, creating links, and selecting elements.

Key Functionalities

    GUI Framework: Divided into panels for tree structure and workspace, with JSplitPane and JScrollPane for enhanced interaction.
    CRUD Operations: Support for creating, reading, updating, and deleting mind map elements.
    Interactive Mind Map Editor: Features for adding, editing, and linking concepts in a visually engaging manner.
    Zoom in/out.
    Undo/Redo.
    

Additional Features

    JSON Serialization: For saving and loading projects, with custom Serializer components.
    Logging: ConsoleLogger and FileLogger for system messages and error handling.
