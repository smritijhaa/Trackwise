TrackWise - Asset Tracking Application
TrackWise is a Java-based asset tracking application developed for the Object Oriented Design class. The app allows users to manage and track assets across categories and locations, view assets based on various criteria (category, location, expiration), and maintain data on asset information.

Features
- Add New Categories: Allows users to define new asset categories.
- Add New Locations: Allows users to define new asset locations.
- Add New Assets: Users can input asset information such as name, category, location, etc.
- Search Assets: Provides functionality to search for assets based on various parameters.
- List Assets by Category/Location/Expiration: Allows users to view assets filtered by category, location, or expiration status.
- Manage Expired Assets: View assets with expired warranties.

Requirements
- Java 8 or higher (Recommended to run the application).
- JavaFX (For the GUI components)

Clone or download the repository:
git clone https://github.com/smritijhaa/Trackwise.git

Import the project into an IDE (like IntelliJ IDEA, Eclipse, or NetBeans) that supports JavaFX.

Add JavaFX library: If you don't have JavaFX installed, you'll need to configure it. Refer to the JavaFX installation guide to set it up in your IDE.

Compile and Run: After the setup, run the application through your IDE, or if you prefer the command line, compile and run it using the following commands:
- javac -d out --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml src/application/*.java
- java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxm

How to Use
1. Welcome Page
The Welcome Page serves as the main entry point. Users can choose which action to perform from the options provided.
2. Add New Category
Click on Enter Category to define a new category for your assets.
3. Add New Location
Click on Enter Location to define a new location for your assets.
4. Add New Asset
Click on Enter New Asset to input the asset details, including the category and location.
5. Search Assets
Click on Search to search for assets by specific parameters.
6. List Assets by Category
Click on List Asset by Category to view assets grouped by category.
7. List Assets by Location
Click on List Asset by Location to view assets grouped by location.
8. List Expired Assets
Click on Expired Warranties to view assets whose warranties have expired.

Example
Once you open the app, you will be greeted with the Welcome Page. From there, you can:
- Click Enter Category to add a new category (e.g., "Electronics", "Furniture").
- Click Enter Location to add a new location (e.g., "Office", "Warehouse").
- Click Enter New Asset to add a new asset (e.g., "Laptop", "Chair").
- The system will allow you to organize assets by these criteria, helping you track and manage your assets more efficiently.
