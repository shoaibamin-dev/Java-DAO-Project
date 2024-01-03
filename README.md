# JSPCrud - Java DAO Project

Welcome to the JSPCrud project! This Java DAO project focuses on user onboarding and authentication using JavaServer Pages (JSP) and a Data Access Object (DAO) architecture.

## Project Structure

- **`WebContent/`**: The web content directory containing JSP files, HTML files, and the WEB-INF directory.
  - **`META-INF/`**: Contains the MANIFEST.MF file.
  - **`WEB-INF/`**: The directory containing the `lib` directory with external libraries.
    - **`lib/`**: The directory for external libraries.
  - JSP Files:
    - `adduser-success.jsp`: JSP file for successful user addition.
    - `deleteuser.jsp`: JSP file for deleting a user.
    - `index.jsp`: Main index JSP file.
    - `adduser.jsp`: JSP file for adding a user.
    - `editform.jsp`: JSP file for editing user information.
    - `userform.html`: HTML file for the user form.
    - `adduser-error.jsp`: JSP file for error in user addition.
    - `adduserform.jsp`: JSP file for the user addition form.
    - `edituser.jsp`: JSP file for editing a user.
    - `viewusers.jsp`: JSP file for viewing users.

- **`build/`**: The build directory.
  - **`classes/`**: The classes directory.
    - **`com/`**: The package directory.
      - **`javatpoint/`**: The project package.
        - **`bean/`**: The directory containing the `User.class` file.
        - **`dao/`**: The directory containing the `UserDao.class` file.

- **`src/`**: The source directory.
  - **`com/`**: The package directory.
    - **`javatpoint/`**: The project package.
      - **`bean/`**: The directory containing the `User.java` file.
      - **`dao/`**: The directory containing the `UserDao.java` file.

## Usage

1. Clone the repository.
2. Set up the project in your preferred Java development environment.
3. Explore the JSP files and Java classes for user onboarding and authentication logic.
4. Customize and extend the functionality as needed for your project.

Feel free to contribute, report issues, or make suggestions to improve this Java DAO project. Happy coding!
