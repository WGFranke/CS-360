# CS-360

**1. Requirements and Goals of the App**
   
Summary: The primary requirement of the Android Inventory Management application was to provide a robust, user-centric mobile solution for tracking inventory items, managing stock levels, and streamlining administrative workflows.

Goals & User Needs: The app was designed to address core user needs around efficiency, accuracy, and accessibility in data management. It solves the common pain points of manual tracking—such as human error, lack of real-time visibility, and cumbersome data entry—by offering persistent local storage, intuitive UI navigation, and automated alert capabilities (such as SMS notifications for critical stock changes).

**2. Screens, Features, and User-Centered UI Design**
   
Screens & Features: The application features a streamlined multi-screen workflow, including a secure authentication/login interface, a primary dashboard utilizing RecyclerView card layouts for smooth scrolling and efficient data rendering, and dedicated views for adding, updating, and deleting inventory items.

User-Centered Design: The UI design prioritized simplicity, consistency, and accessibility, adopting Material Design guidelines via ConstraintLayout to ensure responsive layouts across various screen sizes. By minimizing cognitive load, reducing unnecessary taps, and utilizing clear visual hierarchy, the design ensured that users could perform critical inventory tasks rapidly and with minimal friction.

**3. Approach to Coding and Future Application**
   
Development Strategy: The coding process followed a modular, test-driven engineering approach. Using Android Studio, Java, and the Room persistence library, the architecture was separated into clear layers (UI controllers, data access objects, and local database management) to maintain high cohesion and low coupling.

Future Application: Techniques such as robust parameter validation, defensive exception handling, and clean database schema migrations will be invaluable in future software engineering projects. These practices ensure maintainable, scalable codebases capable of handling complex business logic safely.

**4. Testing Methodology and Importance**
   
Testing Process: Code functionality was verified through comprehensive local unit testing and instrumentation testing within Android Studio, validating database transactions, UI responsiveness, and background service triggers (such as SMS notifications).

Importance & Insights: Rigorous testing is critical because it catches edge cases, prevents regressions, and guarantees application stability under real-world usage conditions. The testing phase verified that data integrity was maintained across asynchronous database queries and UI state changes, ensuring a crash-free user experience.

**5. Overcoming Challenges Through Innovation**
   
Challenge & Innovation: A notable challenge during the development process involved orchestrating seamless local persistence updates and background permission handling (such as sending SMS notifications) without blocking the main UI thread.

Resolution: This was successfully navigated by leveraging asynchronous execution patterns, properly configuring ConstraintLayout hierarchies for fluid rendering, and implementing structured Room database observer patterns to keep the UI synchronized with underlying data changes in real time.

**6. Areas of Particular Success**
   
Demonstrated Expertise: The project was particularly successful in demonstrating proficiency in native Android mobile architecture, specifically through the implementation of the Room persistence library for structured local data storage and the utilization of RecyclerView adapters to deliver high-performance, dynamic lists. This project effectively showcases the ability to synthesize front-end UI design with reliable back-end data management into a cohesive, professional-grade mobile application.
