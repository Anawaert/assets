## Server
Just as the name suggests, the directory is used to store some resources used by Anawaert Server. The server runs on Microsoft Windows Server 2019 Datacenter, so the directory mainly contains some automated scripts and utilities. The details are as follows:

-   `automation/`: Automated scripts and webhook executables.
    -   `webhook/`: Webhook executable files.
    -   `websites-update/`: Windows PowerShell scripts used to update the website after a `git push` to the remote repository triggers the associated webhook.

-   `windows-services/win-sw/`: Windows service wrapper executable files.
