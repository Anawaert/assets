## Server
Just as the name suggests, the directory is used to store some resources used by Anawaert Server. The server runs on Microsoft Windows Server 2019 Datacenter, so the directory mainly contains some automated scripts and utilities. The details are as follows:

-   `Automation/`: Automated scripts and webhook executables.
    -   `Webhook/`: Webhook executable files.
    -   `WebsitesUpdate/`: Windows PowerShell scripts used to update the website after a `git push` to the remote repository triggers the associated webhook.

-   `WindowsServices/WinSW/`: Windows service wrapper executable files.
