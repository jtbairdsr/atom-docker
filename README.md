# docker package

Docker integration for Atom

## Compose

![Compose Panel Screenshot](https://raw.githubusercontent.com/alanzanattadev/atom-docker/master/screenshot-compose-panel.png)

Be productive while working on dockerized project with the Compose Panel for Atom

Features:
  - Selection of compose file to work with with docker:select-compose-file
  - Compose commands UI for up, build, restart, stop, rm on all or specific service
  - Colored Logs Panel with auto attachment
  - Service list with color depending on state
  - On the fly Log Filters with service selection and compose specific logs
  - Tag and push compose services (requires image and build attributs on service definition)

## TO-DO:
  - [x] Build compose services with UI
  - [ ] Build and tags docker images
  - [x] Tag and Push to Docker Registry
  - [ ] Command in progress status
  - [x] Change service name color if running or exited (green / red)
