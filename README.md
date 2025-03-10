**Carbon Emission Records Manager & Document Management System**
Overview
This project is a Python-based application designed to manage carbon emission records and associated documents. It provides functionalities to save and load emission records, 
perform calculations, and manage document uploads with automatically generated unique codes. The application uses JSON for data persistence, Python’s logging module for event tracking, 
and Tkinter for a simple GUI interface.

**Features**
*Emission Records Management:*
Save and load carbon emission records to/from a JSON file.

*Logging:*
Logs important events and errors in an app.log file for debugging and auditing.

*Document Management System (DMS):*
Upload documents via a GUI. Documents are stored in a structured folder hierarchy (by unit, year, and month) under a base directory named CarbonData.

*User Role Management:*
Differentiate between managers and employees based on the uploader’s email.

*Build Configuration:*
A main.spec file is provided for building a standalone executable using PyInstaller.


**Building an Executable**
This project includes a PyInstaller specification file (main.spec) to build a standalone executable. To create an executable:


.gitignore
The repository includes a .gitignore file to exclude unnecessary files such as log files, generated data, virtual environments, and build artifacts. This ensures a clean and focused repository.

Contributing
Contributions are welcome! If you would like to improve this project or fix bugs, please fork the repository and submit a pull request with your changes.

License
This project is licensed under the MIT License.

Contact
For questions, support, or further information, please contact or open an issue in the repository.
