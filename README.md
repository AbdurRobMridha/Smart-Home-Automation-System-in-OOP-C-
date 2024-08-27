# Smart-Home-Automation-System-in-OOP-C-
This is my second group project in my department<br>
Here I include the features and short description in my project <br>
<br><br>
•  Device Class:
<br>
•	A parent class that includes common attributes like name, brand, model, and is_powered_on.<br>
•	Provides methods to input data, display details, save to a file, and read from a file.<br><br>
•  Derived Classes:<br>
•	Specific devices like Television, Refrigerator, AirConditioner, LightBulb, VacuumCleaner, WindowCurtains, and SecurityCamera inherit from the Device class.<br>
•	Each derived class includes additional attributes relevant to the device type, along with methods to handle device-specific actions (e.g., setting the temperature for an air conditioner, or adjusting the channel on a television).<br><br>
•  Main Functions:<br>
•	save_devices(): Saves the current list of devices to a file.<br>
•	add_device(): Allows the user to add a new device, selecting from different types.<br>
•	show_devices(): Displays a list of devices and provides options to update them.<br>
•	remove_device(): Allows the user to remove a device from the list.<br>
•	main_menu(): The main function to interact with the user, providing options to add, display, or remove devices.<br><br>
•  File Handling:<br>
•	The save_to_file() and read_from_file() methods in each class handle saving device data to a file and loading it back when the program starts, ensuring persistence between sessions.
<br><br>

