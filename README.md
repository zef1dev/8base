Here are the points that can be improved in my opinion.
Based on the instructions, it was difficult for me to configure the server side of the application. As a result, it did not work out.

1) 2.3 Building a Data Model
Automatically generated fields look a little strange, you want to select parameters, but this is not possible. It may be better to display them in a different form. Just a list, for example.

It would be great to save draft fields in a table so that you can jump to a previously created field at any time. In this case, the draft field needs to be marked somehow that it has not yet been saved.

2) Add user to Notes

Options
Allow multiple Notes per User=True
Allow multiple Users per Note=False

3) API Explorer - a link to the api section is expected here, but the redirect leads to the dashboard with workspaces

4) 2.2. Roles and Permissions 
The screenshot is misleading. Most likely preserved from the old version. Now the roles are set not in the settings, but in App Services > Roles

5) 2.3. Authentication Profiles
When filling in the fields in the authentication profile, it will be better to warn that some fields will not be edited after saving. For example the TYPE field.

6) 3. Setting up the Client
It is better to split the list of commands for creating the structure of the application into several lines, so it's easier to understand.
mkdir 8base-starter-app 8base-starter-app/client 8base-starter-app/server - about this line
It would be super to add an icon for copying for each line of code.

7) touch readme.md command didn't work for me. I've understood. Script execution is disabled on my system. 
Probably it is worth writing in the documentation that this can happen.

8) It was not possible to call the help. Issue a command to invoke help on every error.

9) 3.2 Deploy a Serverless Function
8base init . --functions=resolver:myCustomResolver 

error: Invalid project name: name cannot be undefined.
error: Time: 5 ms.

It is not clear which name you had to enter.