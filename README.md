# Travel Booking Client Microfrontend

This repository contains the client-facing microfrontend for the Travel Booking application, built with Solid.js.

## Installation

```bash
npm install
```

## Development

```bash
npm run dev
```

## Build

```bash
npm run build
```

## Features

- Homepage with featured tours
- Tour discovery and search
- Booking process
- User account management
- Responsive design for all devices

## Architecture

This is part of a microfrontend architecture using:
- Solid.js as the framework
- Single-spa for microfrontend integration

## CI/CD

This repository uses GitHub Actions for CI/CD pipeline, which will:
- Build and test the code on every PR and push to main
- Collect build metrics
- Deploy to GitHub Pages on push to main