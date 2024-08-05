# Favicons

> [!NOTE]
> Store client favicon assets here. This includes all favicon images and associated files.

## Contents

A typical favicon *package* is derived from the primary client logo and includes multiple sizes and formats.

The following is a typical favicon package structure/layout:

```plaintext
favicons/
├── favicon-16x16.png
├── favicon-32x32.png
├── favicon-48x48.png
├── favicon-64x64.png
├── favicon-96x96.png
├── favicon-128x128.png
├── favicon-192x192.png
├── favicon-256x256.png
├── favicon-384x384.png
├── favicon-512x512.png
├── favicon.ico
├── browserconfig.xml
└── manifest.json
```

- The `favicon.ico` file is a special file that is used by some browsers to display the favicon.

- The `browserconfig.xml` file is used by Internet Explorer to provide metadata about the web application (e.g. name, author, description, etc.) and is used by some browsers to display the favicon.

- The `manifest.json` file is used to provide metadata about the web application (e.g. name, author, description, etc.) and is used by some browsers to display the favicon.
