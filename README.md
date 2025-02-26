# snhu-cs360

## App Summary

**Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**  
This app was designed to allow users to manage and keep track of items (such as inventory) and their quantities in a simple, user-friendly way. Users need a fast method to add items, update quantities, and delete items they no longer need. They also require the ability to log in or create a new account so only authorized users can manage the data.

**What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**  
I included a **Login Screen** to authenticate new and existing users and an **Inventory Screen** to display, add, edit, and delete items. By dividing each function into its own clear interface—login and inventory—users can easily understand where to perform each task. The UI design emphasized simplicity and clarity (for example, descriptive button labels like “Add,” “Edit,” and “Delete”). This helped users quickly locate and act on items, which made the design successful.

**How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?**  
The app was built using a **modular approach**: each feature (login, inventory, database CRUD) was developed in its own class or module. I used **SQLite** for data persistence and a **RecyclerView** with an **Adapter** for dynamic item display. In the future, this modular strategy will help keep code organized and more easily maintainable.

**How did you test to ensure your code was functional? Why is this process important, and what did it reveal?**  
I tested by running the app in the **Android Emulator** and performing each step (creating user accounts, logging in, adding items, updating items, and deleting items). This process is critical for catching bugs and ensuring a seamless user experience. It revealed minor layout misalignments and logical errors, which I then fixed before finalizing the app.

**Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?**  
One challenge was ensuring the **Edit** functionality was intuitive and functional. I innovated by using an alert dialog to handle new quantities, allowing changes to be made easily without moving to a new screen. This kept the user experience straightforward and efficient.

**In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**  
The **Inventory Adapter** and the **DatabaseHelper** demonstrated skill in connecting the UI to the database. This includes creating, reading, updating, and deleting data while keeping the user interface in sync with the underlying SQLite database—offering both a polished user experience and solid code organization.
