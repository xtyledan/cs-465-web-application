# CS-465 — Full-Stack Web Development Reflection

**Coursework reflection on the MEAN-stack application development process.**

This repository currently contains **only this written reflection**. It does not contain the Express application, Angular frontend, MongoDB schema, API handlers, test suite, or deployment configuration. The discussion below describes course experience rather than software that can be run from this repository.

## Architecture explored

- Express and server-rendered HTML for delivering pages.
- JavaScript and SPA patterns for interactive client interfaces.
- MongoDB documents and JSON exchange for API-driven data.
- Reusable components and validation logic to reduce repeated code.

## Testing and security topics

Coursework covered API requests, client/server interactions, administrator authentication, password handling, and negative test cases. No automated test scripts, test outputs, or authentication implementation are included here, so there are **no independently verifiable test results** in this repository.

## Technical tradeoffs

**MongoDB vs SQL:** Document models support flexible schemas, but still require indexing, validation, and data consistency decisions.

**SPA vs server templates:** A SPA can reduce page reloads, but adds client-side state management and build/deployment complexity.

**API testing:** Unit, integration, and end-to-end tests provide distinct evidence. Those layers should be added alongside the actual source in a future release.

## How to review

Read this README as a technical reflection. There is no installation or hosted demo URL for this repository. For runnable, tested code, see [TkForge](https://github.com/xtyledan/TkForge-Visual-Tkinter-GUI-Builder) or [Animal Rescue Explorer](https://github.com/xtyledan/Animal-Rescue-Explorer-Local-Data-Dashboard).
