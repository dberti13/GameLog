# GameLog 🎮

A personal game backlog app for iOS, built with Swift and SwiftUI as a learning and portfolio project.

> **Status:** under development through incremental learning. The features below are planned; this README does not confirm that they have been implemented. Technical details and available features will be updated as the project evolves.

## Overview

GameLog aims to help organize a personal game library: record titles, track games waiting to be played, and keep up with games in progress or already completed.

This repository is for the **GameLog iOS app**. It is a separate project from the **Swift Learning Roadmap** macOS app.

## Goals

- Strengthen Swift and SwiftUI fundamentals by building a real app.
- Gradually practice interface development and state management.
- Learn persistence, API communication, and testing after studying the necessary foundations.
- Document decisions and project progress as part of an iOS development portfolio.
- Prioritize understanding and independence, keeping the scope appropriate for each learning stage.

## Planned Features

The items in this section describe development intentions, **not available features**. Their order and scope may change during the learning process.

- [ ] Add games manually.
- [ ] List saved games.
- [ ] Organize games by status, such as “Want to Play,” “Playing,” and “Completed.”
- [ ] Record each game's platform.
- [ ] Add personal ratings.
- [ ] Track playtime.
- [ ] Search and filter the library.
- [ ] View and edit game details.
- [ ] Save data locally between sessions.
- [ ] Explore integration with an external games API at a later stage.

## Current and Planned Stack

| Technology or Tool | Role | Status |
| --- | --- | --- |
| Swift | Development language | Selected for the project; version to be confirmed |
| SwiftUI | iOS user interface | Selected for the project |
| Xcode | Development and execution environment | Version to be confirmed |
| Local persistence | Library storage | Planned; technology to be chosen after study |
| API integration | Future game information lookup | Planned; service and implementation to be determined |
| Automated tests | Verification of relevant behaviors | Planned for a later stage |

The project currently sets its minimum deployment target to iOS 27.0. Listing a persistence framework, external library, or API service in a plan does not mean it has been adopted.

## Learning Approach

The primary learning resource is Apple's official documentation, with a focus on [Develop in Swift](https://developer.apple.com/tutorials/develop-in-swift).

Development will proceed in small increments, connecting each change to the concepts being studied. Before adding a feature, the aim is to understand its foundations, try an implementation, and review the result.

When used, AI assistance will serve as a mentor and reviewer: clarifying concepts, helping investigate errors, and offering hints while leaving implementation and reasoning to the developer.

## Roadmap Summary

These phases describe a learning sequence. They have no fixed deadlines and do not indicate completed milestones.

| Phase | Learning Focus | Planned Application |
| --- | --- | --- |
| 1 — Fundamentals | Swift types, control flow, functions, structures, collections, and optionals | Model a game's basic data |
| 2 — Initial Interface | SwiftUI views, composition, layouts, lists, and navigation | Build the library and game details interfaces |
| 3 — Interaction and State | State, data flow, forms, and validation | Add, edit, and organize games in memory |
| 4 — Persistence | Local storage and model evolution | Preserve the library between launches |
| 5 — Quality | Code organization, accessibility, and testing | Review behavior and improve the experience |
| 6 — Expansion | Concurrency, networking, and error handling | Evaluate integration with an external API |

## Running the App

1. Clone or download this repository on a Mac.
2. Open `GameLog.xcodeproj` in an Xcode version compatible with the project. The project records Xcode 27.0 as its creation version.
3. Select the `GameLog` scheme and an iPhone or iPad simulator running iOS 27.0 or later. Install the required simulator runtime through Xcode if needed.
4. Choose **Product > Run** or press **⌘R**.

The current app displays the initial “Hello, world!” screen. These instructions reflect the project files; a successful build and simulator run have not yet been verified as part of this repository review.

## Usage and Contributions

GameLog is a personal learning and portfolio project. Suggestions and bug reports are welcome through the channels available in the repository, such as Issues, if enabled.

Contributions should respect the project's educational purpose: explain the problem, justify the proposal, and keep changes small and understandable. Discuss the scope with the project maintainer before proposing larger features.

GameLog is licensed under the [MIT License](LICENSE).

## Development Status

**Under development, with a focus on learning.** The repository currently contains the app entry point, an initial SwiftUI screen, and an asset catalog. The backlog features listed above have not yet been implemented. This document does not declare a stable release or an expected launch date.

This README will be updated to reflect verified features, technical decisions, and actual execution instructions as GameLog evolves.
