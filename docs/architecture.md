# Architecture

## Current implementation

A buildless static application serves HTML, CSS, and JavaScript. Curriculum data, scenario state, and interactive workspaces execute in the browser. localStorage retains progress on that browser profile. A Node.js smoke check exercises scenario progression, negative gates, independent module access, and persistence behavior.

There is no backend, identity provider, VM orchestrator, or shared progress database. Browser-side checks are learning feedback, not tamper-resistant grading. A private source repository contains the application and deployment notes.

## Planned lab platform

A future service would authenticate students, allocate a separate lab environment per student, expose controlled remote access, validate evidence from the lab, and retain progress. Reset and expiration would apply to each student's environment. Windows licensing, infrastructure cost, access controls, and capacity must be designed before live VM labs can be offered.

This future architecture is a roadmap, not an existing capability.
