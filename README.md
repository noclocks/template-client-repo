# Template Client Repository

> [!NOTE]
> This is a template repository for a high-level *client repository* meant to store all client-related files and assets as well as any potential
> projects and/or source code in the form of a git-submoduled mono-repo.

> [!WARNING]
> This repository is meant to be used as a template for creating a new client repository and should not be used as a client repository itself.

***

## Structure

Below is an example repository structure for a client:

```plaintext
client-acme/
├── .github/               # GitHub Configuration, Copilot Instructions, and Workflows
├── admin/                 # -> Linked to Google Drive Administrative Folder
├── brand/                 # Symlinks to Drive Brand Assets
├── config/                # Client Configs; Infrastructure-as-Code (Terraform/GCP)
├── data/                  # Processed Client Data (Raw in Google Drive) 
├── docs/                  # Technical Documentation (API specs, etc.)
└── src/                   # Source Code / Git Modules to Client Repos
```

## Folders

- [admin/](admin/): Administrative Files
- [brand/](brand/): Client Brand Assets
- [config/](config/): Configuration Files
- [data/](data/): Data Files
- [docs/](docs/): Documentation
- [src/](src/): Client Project Source Code
- [tools/](tools/): Tools

plus,

- [.github/](.github/): GitHub Configuration Files
- [.vscode/](.vscode/): VSCode Configuration Files

## Usage

`#TODO`
