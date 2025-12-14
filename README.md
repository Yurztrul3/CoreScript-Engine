🚀 CoreScript Engine: Code-First Game Development
CoreScript Engine is a high-performance, open-source game development framework designed for developers who prefer programmatic control over visual interfaces. It offers a powerful foundation for 2D and 3D games by exposing the entire game world as accessible, scriptable objects, making it an ideal choice for rapid prototyping, simulation development, and creating highly customized game logic.

🔑 Key Features
Script-Driven Workflow: Unlike traditional game engines, CoreScript Engine provides no built-in graphical user interface (GUI). All objects, components, and scene structures are initialized, configured, and manipulated directly through your main game scripts.

Full Python Integration: The engine is built with native Python bindings, allowing developers to implement all game logic using the simplicity and power of Python. This includes creating objects, handling input, defining game loops, and attaching behavior scripts.

Hierarchical Workspace Model: Inspired by high-level engines, CoreScript utilizes a central engine.workspace variable, giving direct programmatic access to:

Scene Objects: A container for all active game entities.

Physics: Control over global properties like engine.workspace.gravity.

Game Time: Access to frame rate, delta time, and elapsed game duration.

Object-Attachment System: Behavior scripts can be cleanly attached to any game object. Simply define a class or function in Python and attach it to an object to control its update logic, rendering, and interaction behavior.

Minimalist Core: The small core runtime ensures fast compilation, rapid iteration times, and a low memory footprint, giving you maximum control over performance.

💡 Design Philosophy
CoreScript Engine is built on the philosophy that code is the best editor.

By stripping away the complex tooling, we offer developers an unhindered API (Application Programming Interface) that mirrors the structured simplicity of the file system and your IDE. This approach guarantees that the logic you write is precisely the logic the engine executes, simplifying debugging and deployment.

🌐 Open Source & Licensing
CoreScript Engine is proudly open-source under the MIT License. This allows you to use, modify, and distribute the engine freely. As the original creator and primary maintainer, I reserve the right to review and merge all changes into the official codebase, ensuring the core remains stable, focused, and true to its script-first design.
