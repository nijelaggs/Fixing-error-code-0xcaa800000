<h1>Fixing error code 0xcaa800000 & Other Microsoft Login Issues</h1>

<h2>Description</h2>
This PowerShell script is designed to delete a specific folder associated with a user profile in Windows. <br> 

<br>Even if processes are locking the files within it. <br>

That folder is  'Microsoft.AAD.BrokerPlugin_cw5n1h2txyewy', when deleted it will disrupt/stop authentication services. <br>

Prompting you reauthenticate solving the error code you were reciving. <br>

Here’s how it works: <br>

<h2>Languages and Utilities Used</h2>

- <b>Powershell</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows 11<b>

<h2>Program walk-through:</h2>

<p align="center">
1. Prompt for Username: The script starts by prompting the user to enter a username. This is used to construct the path to the target folder: <br/>
<br>2. Define Folder Path: Using the entered username, the script defines the path to the folder that needs to be deleted. <br>
<br>3. Function to Stop Locking Processes: The script includes a function, Stop-LockingProcesses, which identifies and stops any processes that are locking files in the specified folder. This is done to ensure the folder can be deleted without errors. <br>

