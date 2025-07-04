# Raspberry Pi SFTP Server

This project sets up a secure, isolated SFTP environment on a Linux server.

## What it does

- Configures an SFTP-only area for file uploads and downloads
- Users in the `sftpusers` group can:
  - Connect using SFTP only (no SSH shell access)
  - Access only `/home/shared/files`

## Why it matters

- Protects the rest of the server from unauthorized access
- Provides a clean, restricted area for partners or students to exchange files
- Simple user management by adding users to the `sftpusers` group
