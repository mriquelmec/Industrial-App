# Industrial Equipment Management System

This project is a web application developed to manage industrial equipment, both active and obsolete. The application allows users to track equipment, manage maintenance records, and handle equipment registrations and disposals. Additionally, it includes custom authentication and a role-based system that defines permissions for different user types.

## Features

- **Authentication and Authorization:** Enables user registration and custom login.
- **Active and Obsolete Equipment Management:** Allows detailed management of equipment, including viewing active equipment, registering obsolete equipment, and listing equipment with their status.
- **Equipment Modification:** Functionality to update information for existing equipment.
- **Maintenance Records:** Access to a maintenance log for each piece of equipment, where users can record and consult the maintenance history.
- **Detailed Equipment View:** Provides a detailed description of specific equipment.

## Technologies Used

- **Frontend:** React
- **Styling:** Bootstrap
- **API:** Axios for HTTP requests to the server
- **Routing:** React Router DOM

## Installation

1. Clone the repository.
```bash
git clone https://github.com/mriquelmec/Industrial-App.git
```
2. Install the dependencies.
```bash
 npm install
 ```
 3.Start the development server
 ```bash
 npm start
```


## Usage
Once the development server is running, you can access the application in your browser at http://localhost:3000.

-To register a new user, navigate to the login page and click on the "Register" button.

-To log in, enter your credentials on the login page.

-To manage equipment, navigate to the equipment management page and perform the desired actions.

-To view detailed information about a specific piece of equipment, click on the equipment card in the equipment management page.

-To record maintenance records, navigate to the maintenance log page and perform the desired actions.


## Report
The application provides a reporting feature that allows users to generate reports on equipment status, maintenance history, and other relevant data. The report section includes the following features:

**Equipment Status Report:** Generates a report on the current status of all equipment, including active and obsolete equipment.

**Maintenance History Report:** Generates a report on the maintenance history of a specific piece of equipment or all equipment.

**Equipment Registration Report:** Generates a report on all equipment registrations, including date, time, and registration details.

To access the report section, navigate to the report page and select the desired report type. The report will be generated in a downloadable PDF format.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.



##### This project was originally developed by:

*Jose Osorio, Patricia Pereira, Macarena Riquelme.*