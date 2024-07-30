# Quickstart Guide for Mehanix-Arcada

This guide outlines the steps to set up and run the Mehanix-Arcada application.

## Steps to Set Up Your Development Environment with Docker

1. **Clone the Original Repository**:
   - Clone the repository using the following command:
     ```bash
     git clone https://github.com/perguth/arcada-setup
     ```

2. **Update the Submodule Configuration**:
   - Update the `.gitmodules` file to point to your own GitHub repository:
     ```plaintext
     [submodule "mehanix-arcada"]
         path = path/to/mehanix-arcada
         url = https://github.com/user9237590463948/mehanix-arcada
     ```

3. **Fork the Repository**:
   - Create a private fork of the original repository from GitHub:
     - Original: `https://github.com/perguth/arcada-setup`
     - Your Fork: `https://github.com/user92375904639498/mehanix-arcada-setup`

4. **Run the Application**:
   - Navigate to your local version of the forked repository and execute the following command to start the application:
     ```bash
     npm start
     ```
   - Since you didn't have `docker-compose`, run the following command to start the services defined in the `docker-compose.yml` file:
     ```bash
     docker compose up
     ```

---