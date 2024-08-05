# Configuration

> [!NOTE]
> Store configuration files here. This includes configuration files for the data processing pipeline, models, and other
> code used in the project.
>
> Typical configuration files include a primary `config.yml`, cloud `credentials.json`, tool-specific configuration files (i.e. `slack.yml`),
> and other configuration files specific to the client or client project(s).

## Configuration Files

- [config.template.yml](config.template.yml): A template configuration file that can be used to create a `config.yml` file.
- [config.encrypted.yml](config.encrypted.yml): An encrypted configuration file that can be used to store sensitive information.
- [config.yml](config.yml): The primary (unencrypted) configuration file for the project. This file should be created from the `config.template.yml` file and should be git-ignored.

## Environment

- [.env.example](.env.example): An example environment file that can be used to create a `.env` file.
- [.env](.env): The primary environment file for the project. This file should be created from the `.env.example` file and should be git-ignored.

## Credentials

- [credentials.json](credentials.json): Cloud credentials file for the project. This file should be git-ignored.

## Tools

> [!NOTE]
> *Depends on the tools used in the project.*

Examples of common tool configurations include:

- Slack: (i.e. `slack.yml`) for Slack API Access, Slack Application Manifests, Webhook URLs, etc.
- Google Drive: (i.e. `gdrive.yml`) for Google Drive API Access, Folder Paths and IDs, etc.
- Google Sheets: (i.e. `gsheets.yml`) for Google Sheets API Access, Spreadsheet IDs, etc.
- Database Connections: (i.e. `db.yml` or `connections.dcf`) for Database Connection Strings, Hosts, Ports, Usernames, Passwords, etc.
- Email: (i.e. `email.yml`) for Email API Access, SMTP Server Information, etc.
- AWS: (i.e. `aws.yml`) for AWS API Access, S3 Bucket Names, IAM Roles, etc.
- Azure: (i.e. `azure.yml`) for Azure API Access, Blob Storage, etc.
- GCP: (i.e. `gcp.yml`) for GCP API Access, GCS Bucket Names, etc.
