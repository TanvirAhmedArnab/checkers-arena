# Checkers Arena

A full-stack, browser-based multiplayer checkers game built with C#, ASP.NET Core, Blazor, and modern web technologies.

## Project Overview

Checkers Arena is an online strategy gaming platform where players can create accounts, compete in checkers matches, track their performance, and participate in leaderboards.

The project is being developed as a portfolio application to demonstrate full-stack web development, software engineering principles, real-time communication, database management, authentication, testing, and deployment.

## Target Users

- Casual players who enjoy browser-based strategy games.
- Players who want to compete against friends online.
- Competitive players interested in rankings and match statistics.

## Planned Features

- User registration, login, and authentication.
- Interactive checkers board.
- Rule-based move validation.
- Multiplayer game rooms.
- Real-time communication between players.
- Match history and player profiles.
- Win/loss statistics.
- Online leaderboards.
- Responsive user interface for desktop and mobile devices.

## Technology Stack

| Layer | Technology |
|---|---|
| Front End | Blazor, HTML, CSS |
| Back End | ASP.NET Core, C# |
| Real-Time Communication | SignalR |
| Authentication | ASP.NET Core Identity |
| Database | SQL Server LocalDB for initial development; PostgreSQL planned |
| Data Access | Entity Framework Core |
| Development Environment | Visual Studio Community |
| Version Control | Git and GitHub |
| Deployment | Docker and cloud hosting (planned) |

## Architecture

The application will use a client-server architecture.

**Front End:** Handles rendering, navigation, user interactions, and the interactive checkers board.

**Back End:** Manages authentication, validates moves, coordinates matches, calculates results, and provides game-related services.

**Database:** Stores user accounts, game records, player statistics, and leaderboard information.

**Real-Time Communication:** Uses SignalR to synchronize live multiplayer game events.

## Development Roadmap

### Phase 1 — Foundation

- [x] Define the project scope and requirements.
- [x] Create the initial Blazor application.
- [x] Initialize version control with Git.
- [ ] Publish the repository to GitHub.
- [x] Establish the initial project architecture.

### Phase 2 — Core Game

- [ ] Build the checkers board.
- [ ] Implement piece movement.
- [ ] Implement game rules and move validation.
- [ ] Add win/loss detection.
- [ ] Implement local two-player gameplay.

### Phase 3 — Multiplayer

- [ ] Add multiplayer rooms.
- [ ] Integrate SignalR.
- [ ] Synchronize player moves.
- [ ] Handle disconnections and reconnections.
- [ ] Save completed matches.

### Phase 4 — Player Features

- [ ] Implement player profiles.
- [ ] Add match history.
- [ ] Add player statistics.
- [ ] Implement leaderboards.

### Phase 5 — Quality and Deployment

- [ ] Add unit and integration tests.
- [ ] Improve accessibility and responsive design.
- [ ] Configure continuous integration.
- [ ] Containerize the application.
- [ ] Deploy the application.
- [ ] Document the final architecture.

## Getting Started

The application is currently in its initial development stage.

### Prerequisites

- Visual Studio Community with the ASP.NET and web development workload.
- .NET 10 SDK.
- Git.

### Running Locally

1. Clone this repository.
2. Open the CheckersArena solution in Visual Studio Community.
3. Restore NuGet packages if required.
4. Build the solution.
5. Run using the HTTPS launch profile.

Additional setup instructions will be added as development progresses.

## Project Status

**Status:** Initial development.

Core gameplay, online multiplayer, ranking systems, and production deployment are planned and not yet implemented.

## Development Goals

This project is intended to provide practical experience across the complete software development lifecycle, including requirements analysis, architecture, implementation, testing, version control, security, deployment, and maintenance.
