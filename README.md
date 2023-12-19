To fulfill the requirements outlined in the scenario, you'll need to create a custom Linux command named internsctl with version v0.1.0. The command should have the following functionalities:

Section A
Manual Page:

Create a manual page for the internsctl command. This manual page should include documentation on the command's usage, options, and any other relevant information. This can be achieved by creating a man page file (e.g., internsctl.1) with the necessary content.
Help Option:

Implement the --help option to provide users with usage guidelines and examples for the internsctl command.
Version Option:

Implement the --version option to display the version of the internsctl command.
Section B
Part 1 | Level Easy
CPU Information:

Create a subcommand cpu with the action getinfo to retrieve CPU information. The output should be similar to the lscpu command.
Memory Information:

Create a subcommand memory with the action getinfo to retrieve memory information. The output should be similar to the free command.
Part 2 | Level Intermediate
Create User:

Implement a subcommand user with the action create <username> to create a new user on the server. Ensure that the new user can log in and has access to their home directory.
List Users:

Implement a subcommand user with the action list to list all regular users on the server.
List Users with Sudo Permissions:

Extend the user list command to include an option --sudo-only that lists users with sudo permissions.
Part 3 | Advanced Level
File Information:

Create a subcommand file with the action getinfo <file-name> to retrieve information about a file. The output should include details such as file permissions, size, owner, and last modified time.
File Information Options:

Allow users to specify options when using the file getinfo command to obtain specific information:
--size or -s to print the file size.
--permissions or -p to print file permissions.
--owner or -o to print file owner.
--last-modified or -m to print the last modified time.
Implementation and Documentation
Git Repository:

Create a private Git repository to track the development of your internsctl command. Push all configurations and code to this repository.
Documentation:

Ensure that your code is well-documented. Provide comments within the script to explain the purpose and functionality of each section. Also, update the manual page with any additional information.
Diagrams
Draw.io Diagrams:
Create workflow and application architecture diagrams using Draw.io to visually represent the structure and flow of your internsctl command.
Note on Privacy
Confidentiality:
Emphasize the importance of confidentiality and ensure that the documentation and code are not shared with anyone, including colleagues.
By following these detailed instructions, you will create a robust and well-documented internsctl command with various functionalities, meeting the requirements outlined in the scenario.
