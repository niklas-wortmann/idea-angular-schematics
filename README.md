# IDEA Angular Schematics
This repository contains three distinct JetBrains IDE run configurations, designed to simplify and automate different types of migration processes within your Angular projects. These configurations can be easily integrated into any Angular project using a JetBrains IDE.

## Configurations

### Standalone Migration in Current File
#### Description
This configuration applies standalone migration to the currently open file in the IDE. It's useful for targeted migrations on a file by file basis.
#### How to Use
Copy the configuration settings into your project's run configurations. When you want to run a standalone migration, simply open the target file and execute this configuration.

### Standalone Migration in Current Directory
#### Description
This configuration extends the standalone migration to the entire directory of the currently selected file. It's ideal for comprehensive directory-based migrations.
#### How to Use
Ensure the file in the target directory is selected. Copy the configuration into your project's run configurations and execute to apply migration across all files in the directory.

### Control Flow Migration in Current File
#### Description
Specifically focused on control flow migrations, this configuration applies the process to the file currently open in the IDE.
#### How to Use
Open the file that requires control flow migration. Copy this run configuration into your project and execute it.

## Integration
To integrate these configurations into your project:

1. Clone this repository.
2. Copy the desired run configuration files from the repository to your project's .idea/runConfigurations directory.
3. Restart your JetBrains IDE if it's already running.
4. The new run configurations should now appear in your run configuration dropdown.

## Contributing
Contributions to enhance these configurations are welcome. Feel free to fork this repository, make your changes, and submit a pull request.

## Acknowledgements
Special thanks to Enea Jahollari (@Enea_Jahollari) for the innovative idea of creating these dedicated run configurations.
