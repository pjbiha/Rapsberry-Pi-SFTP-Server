What this project does:
Sets up a **safe SFTP drop-zone** on a Linux server.
Users in the group **sftpusers** can:
  – log in with SFTP only (no SSH shell)  
  – see only **/home/shared** and work in **/home/shared/files**

Why it matters:
Keeps the rest of the server hidden and safe.  
Gives partners/students a clean place to upload and download files.  
Easy to manage: add a user to **sftpusers** and they’re ready.
