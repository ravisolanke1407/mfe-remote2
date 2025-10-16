# MFE Webpack Demo – Remote2

## Overview

This is **Remote2**, a micro frontend exposed via Webpack Module Federation. It provides the `OrderLabel` component to the host app.

## Author

- **Ravindra Solanke** ([GitHub](https://github.com/ravisolanke1407))

## Live Demo

- Remote2: [https://mfe-remote1.vercel.app](https://mfe-remote1.vercel.app)

## Features

- Exposes React components for host consumption
- Shares React as singleton
- Manifest-driven remote loading

## Setup & Development

```sh
npm install
npm run start:local
```

App runs at [http://localhost:3002](http://localhost:3002)

## Deployment

- Push code to GitHub
- Import repo to Vercel and deploy (output dir: `dist`)

## Module Federation

- Exposes `./OrderLabel` in `remoteEntry.js`
- Shares React and ReactDOM as singleton

## License

MIT
