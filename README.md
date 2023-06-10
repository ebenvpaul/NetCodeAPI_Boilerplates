# NetCodeAPI_Boilerplates
# NetCodeAPI Setup

This repository contains a script to set up a .NET API solution with multiple projects using the command-line interface (CLI). The script creates a directory called `NetCodeAPI` and sets up the necessary projects and dependencies within it.

## Prerequisites

Before running the setup script, ensure that you have the following prerequisites installed on your system:

- [dotnet CLI](https://dotnet.microsoft.com/download)

## Usage

To use the setup script, follow these steps:

1. Clone this repository or download the `setup.sh` file.
2. Open a terminal or command prompt or powershell.
3. Navigate to the directory where the create-projects-osx.sh or create-projects-win.ps1 file is located.
4. Run the following command to make the script executable:

   ```bash
   chmod +x setup.sh
   ```
   In mac OS ,In Terminal run : this will enable write permission for file create-projects-osx.sh 
   ```
   chmod +x create-projects-osx.sh 
   ```
   
   To verify the permissions try running this
   
   ```
   ls -l create-projects-osx.sh
   ```
   
5. Execute the script using the following command:

   ```bash
   ./setup.sh
   ```
   
   In Mac, Run this
   ```
   ./create-projects-osx.sh
   ```
   

   The script will perform the following actions:

   - Create a directory called `NetCodeAPI`.
   - Create a new solution and projects within the `NetCodeAPI` directory.
   - Add the projects to the solution.
   - Set up project dependencies.
   - Restore the project dependencies.

6. Once the script finishes executing, your .NET API solution will be set up and ready for development.

## Project Structure

After running the setup script, the `NetCodeAPI` directory will contain the following projects:

- `API`: The main web API project.
- `Application`: The application layer project.
- `Domain`: The domain layer project.
- `Persistence`: The persistence layer project.

These projects are structured to follow a typical layered architecture for building .NET APIs.

## Contributing

If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## Images
### Solution Folder
![image](https://github.com/ebenvpaul/NetCodeAPI_Boilerplates/assets/24457351/c9a7a2fd-a263-44ba-a96d-7e8414a3b789)
### Project Structure
![image](https://github.com/ebenvpaul/NetCodeAPI_Boilerplates/assets/24457351/7405c7a8-1afc-4626-8279-4ac6748d4dd2)

