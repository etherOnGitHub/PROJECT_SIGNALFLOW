# Project Charter

*A guiding document on the goals of the project.*

---
## Signalflow

---
### Objective

Develop a Java-based market data visualisation application
that retrieves, parses, caches, and stores financial time-series data,
transforming it into readable graphical representations for analysis.

---
## Success Criteria

- Users can search for a stock symbol.
- The system retrieves financial market data from an external API.
- The system parses and normalises API response data.
- Users can view data in a time-series graph.
- Retrieved datasets are cached to reduce repeated API calls.
- Market data is stored within a database for persistence.
- API failures do not result in total application failure.

---
## Target Users

### Primary Target Users

- Traders and brokers requiring rapid access to market trends
  to support informed trading decisions.

### Secondary Target Users

- Data analysts seeking to observe and analyse historical
  financial trends across time-series datasets.

### Tertiary Target Users

- Educational institutions and learners requiring a simplified
  environment for understanding market behaviour and financial datasets.

---
## Project Scope

### In Scope

- Market data retrieval from external APIs.
- JSON parsing and transformation.
- Local caching of retrieved datasets.
- Database persistence using PostgreSQL.
- Time-series data visualisation.
- Comparative graph analysis.
- Basic analytical indicators.

### Out of Scope

- Real-time high-frequency trading.
- Automated trading execution.
- User authenticated systems.
- Cloud-scale distributed systems.
- Financial advice generation.

---
## Development Approach

The project will follow a phased Agile methodological incremental approach,
beginning with minimum viable product focused on data retrieval, cache and visualisation.

Additional analytical & comparative features will be introduced iteratively in the second phase.

The third phase will be evaluated closer to the time but will mainly focus on UX & creating a bespoke,
 complete package.

---
## Key Risks

- API rate limits.
- Large dataset accumulation + storage impacts.
- Inconsistent external API response formats.
- Performance degradation with large historical datasets.
- Network dependency on external API assets.

---
## High-Level Deliverables

- Functional Java application.
- Market data API integration.
- PostgreSQL persistence layer.
- Data caching systems.
- Time-series graph visualisation.
- Technical documentation.
- UML & architectural diagrams.
- GitHub repository with version control.
- Maven build pipeline.
- Automated test suite.
- Continuous Integration workflow.

---

*For more information see the 
[Feasibility Study](https://github.com/etherOnGitHub/PROJECT_SIGNALFLOW/tree/main/docs/planning/feasibility-study.pdf)*