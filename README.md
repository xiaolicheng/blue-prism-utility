![Blue Prism Interactive Client](/img/blue-prism-ui.jpg)

# Blue Prism Utility

This asset contains a variety of Visual Business Objects (VBOs) and Processes that enable the automation of the Blue Prism  v6.5 interactive client itself.

![Blue Prism VBO](/img/blue-prism-vbo.jpg)

# Usage
This asset has been initially built in order to automatically interact with credentials stored in Blue Prism. The initial release contains VBOs and Processes designed around retrieving, updating, and deleting Blue Prism credentials.

Overall, the asset is designed with a generic approach so that it can be expanded to automate other components of the Blue Prism Interactive Client.

# Version Support
This asset is designed for Blue Prism v6.5.

# Installation
1. Download this repository from the Releases page: https://github.com/blue-prism/blue-prism-utility/releases
2. Launch Blue Prism and select `File > Import`
3. Select the downloaded .bprelease file and import it into Blue Prism

# Contribute
To contribute to the development of this asset, follow these steps:
1. Clone or fork this repository
2. Import the .bprelease file into Blue Prism
3. Add functionality to the asset
4. Create an updated .bprelease file
5. Update the User Integration Guide document to include the new functionality
5. Submit a pull request to this repository that includes all changed files

# Architecture
## Objects
This asset adheres to the best practice approach of "one VBO per screen."

![Asset VBO List](/img/blue-prism-list.jpg)

As additional Blue Prism screens are automated, it is important that each screen is fully contained in its own VBO. The naming convention for any VBO is: `<Application Name vx.x> - <Screen Name> Actions`. For example, a new VBO that interacts with the Analytics screen in Blue Prism would be titled `Blue Prism v6.5 - Analytics Actions`.

## Processes
The naming convention for a process is: `<Application Name vx.x> - <Process Name>`. The `<Process Name>` should begin with a verb or an action word and describe the activity that the process executes.

# Support
To report an issue with this asset, please submit a new issue on the Issues tab: https://github.com/blue-prism/blue-prism-utility/issues



