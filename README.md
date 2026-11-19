# project-fa-ios

The iOS app for Project FA, a made-up delivery company. The backend, the design and the experiments live in [project-fa](https://github.com/citrusunshiu/project-fa); this repository will hold only the iOS app's code.

## Status

Empty until Phase 10 of the [roadmap](https://github.com/citrusunshiu/project-fa/blob/main/docs/charter.md#roadmap). Nothing is built here before the backend it calls exists.

## What it will be

- Customer and courier modes, in Swift with SwiftUI (`ios-app` in the [catalog](https://github.com/citrusunshiu/project-fa/blob/main/catalog/components.yaml)), following the same client behaviour spec as the Android app.
- It calls only the mobile backend-for-frontend, `mobile-bff`, which lives in the main repository with the rest of the backend.
- Push notifications and share links.
- Phase 10 is done when both apps pass the same behaviour-spec tests, and the reconnect storm has been rerun with a mix of clients.

The design doc for the clients, `docs/design/clients.md` in the main repository, is still to be written.

## Issues

Issues for this repository are filed in [project-fa](https://github.com/citrusunshiu/project-fa/issues), together with the other repositories' issues. Pull requests here link them as `Closes citrusunshiu/project-fa#N`.

## How it's made

The maintainer drafts docs and code with AI coding agents. Commits that an agent helped write say so in trailers naming the agent, its model and its effort level, as the main repository's [AGENTS.md](https://github.com/citrusunshiu/project-fa/blob/main/AGENTS.md) describes.

## Licence

[Apache-2.0](LICENSE).
