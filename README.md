# SIGNALFLOW 📶

A Java-based market data visualisation system designed to retrieve,
process, cache, and visualise financial time-series data.

The project focuses on scalable data handling, structured software
architecture, and clear graphical representation of market behaviour
to support analysis and decision-making.

---

# Project Overview

SIGNALFLOW is being developed as a software engineering capstone project
following Software Development Life Cycle (SDLC) principles and an
Agile-inspired phased delivery approach.

The system aims to:

- Retrieve financial market data from external APIs
- Parse and transform JSON datasets
- Cache API responses efficiently
- Persist structured market data
- Display market behaviour through time-series visualisation
- Support comparative and analytical tooling

Future stretch goals include alternative data representations such as
audio-based market sonification using Digital Signal Processing (DSP).

---

# Current Project Status

## Phase: Planning & System Design

Current work includes:

- Feasibility study
- Project charter
- Requirements planning
- Architectural planning
- Jira project workflow setup
- SDLC documentation

Implementation has intentionally not yet begun in order to establish
clear project scope, architecture, and delivery planning.

---

# Core Objectives

- Build a reliable market data visualisation system
- Design a clean layered architecture
- Explore time-series data handling
- Implement robust caching strategies
- Demonstrate SDLC and Agile workflows
- Create a portfolio-grade engineering project

---

# Planned Features

## MVP Features

- Search for stock symbols
- Retrieve market data from external APIs
- Parse JSON financial datasets
- Cache API responses locally
- Store transformed market data
- Display financial time-series graphs

## Planned Enhancements

- Comparative dataset analysis
- Analytical indicators
- Multiple graph overlays
- Improved visualisation tooling
- Advanced data interpretation
- Audio representation of market behaviour

---

# Planned Architecture

```text
[External API]
        ↓
[API Client Layer]
        ↓
[Processing / Transformation Layer]
        ↓
[Caching Layer]
        ↓
[Persistence Layer]
        ↓
[Visualisation Layer]
````

The project is being designed using layered architectural principles
to separate:

* API communication
* business logic
* persistence
* processing
* visualisation

---

# Technology Stack

| Area               | Technology                 |
|--------------------|----------------------------|
| Language           | Java 25                    |
| Build Tool         | Maven                      |
| API Communication  | Java HTTP Client           |
| Data Format        | JSON                       |
| Database           | PostgreSQL                 |
| Caching            | Local API response caching |
| Visualisation      | JavaFX / JFreeChart        |
| Testing            | JUnit / Mockito            |
| Version Control    | Git / GitHub               |
| Project Management | Jira                       |
| Documentation      | Confluence                 |

---

# Development Workflow

The project follows an Agile-inspired workflow with phased delivery.

Development planning and task management are handled through Jira,
with source control and version history maintained through GitHub.

## Workflow Stages

* Planning
* Requirements Analysis
* System Design
* Implementation
* Testing
* Evaluation

---

# Repository Structure

```text
/docs
/src
/tests
```

Additional structure will evolve alongside implementation.

---

# Documentation

Project documentation includes:

* Feasibility study
* Project charter
* Requirements analysis
* Architecture planning
* UML diagrams
* Database design
* Testing strategy
* Sprint planning

---

# Risks & Considerations

Current technical considerations include:

* API rate limiting
* Large dataset accumulation
* Efficient caching strategies
* Time-series query performance
* Scalable persistence design

---

# Future Direction

Potential future expansion areas include:

* Web-based deployment
* Advanced analytical tooling
* DSP-driven market sonification
* Time-series database optimisation
* Comparative financial analysis systems

---

# Project Links
## [GitHub](https://github.com/etherOnGitHub/PROJECT_SIGNALFLOW)
## [Jira](https://calrichards.atlassian.net/jira/software/projects/SCRUM/boards/1)
## [Confluence](https://calrichards.atlassian.net/wiki/home)

---

# Author

Callum Richards

Junior Full-Stack Developer
Focused on software engineering, data systems, and scalable application architecture.

