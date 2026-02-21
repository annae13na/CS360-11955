**Project Summary:**  The Inventory Management App was developed to help individuals and small businesses track inventory and prevent stock shortages. The primary goal was to create a secure, user-friendly application that allows users to log in, manage inventory items, and receive optional SMS alerts when stock reaches zero. The app was designed to address the user need for organization, efficiency, and reliability in inventory tracking.

**UI Design and User-Centered Features:** The application includes several screens and features to support user needs:

Login and account creation screen

Inventory grid display

Add item functionality

Update and delete item options

**SMS settings screen:** The UI was designed to keep users in mind by organizing actions logically and reducing unnecessary complexity. Clear labeling, structured layouts, and minimal permission requests helped create a straightforward experience. The design was successful because it prioritized usability and accessibility while maintaining functionality.

**Development Approach:** I approached coding in a structured and incremental way. I implemented login functionality first, then database persistence using SQLite, followed by CRUD operations and SMS permissions. I tested frequently using the Android Emulator to validate functionality and catch errors early. This step-by-step method reduced debugging complexity and improved overall stability.

These techniques—building incrementally and testing frequently—can be applied in future development projects to maintain quality and reliability.

**Testing Process:**  Testing included validating login credentials, database persistence after closing the app, and ensuring CRUD operations functioned correctly. I also tested SMS permission granted and denied scenarios to ensure the app continued to function without crashing. This process is important because it reveals edge cases and prevents runtime failures in real-world usage.

**Innovation and Challenges:**   One challenge involved implementing SMS functionality in a way that complied with permission handling while ensuring the app continued working if permission was denied. I addressed this by using conditional checks and safe error handling to prevent crashes. This required thoughtful integration between user settings and system permissions.

**Demonstrated Skills:** The component I was most successful in was integrating database persistence with a RecyclerView interface. This demonstrated my understanding of structured data management, UI binding, and real-time updates. The SMS permission logic also reflects my ability to implement Android best practices related to user privacy and runtime permissions.

The component I was most successful in was integrating database persistence with a RecyclerView interface. This demonstrated my understanding of structured data management, UI binding, and real-time updates. The SMS permission logic also reflects my ability to implement Android best practices related to user privacy and runtime permissions.
