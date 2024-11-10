# WhatChats (whatchats)

Bot Multi-atendimento para whatsapp

## Install the dependencies
```bash
npm install
```

### Start the app in development mode (hot-code reloading, error reporting, etc.)
```bash
quasar dev
```

Fix for node new version (>16)

Add script for npm
```
"dev": "SET NODE_OPTIONS=--openssl-legacy-provider && quasar dev",
"build": "SET NODE_OPTIONS=--openssl-legacy-provider && quasar build"
```

### Lint the files
```bash
npm run lint
```

### Build the app for production
```bash
quasar build
```

### Customize the configuration
See [Configuring quasar.conf.js](https://quasar.dev/quasar-cli/quasar-conf-js).
