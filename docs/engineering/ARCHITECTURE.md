# Architecture

## System Overview

### Questions
- Is this a web app, mobile app, PWA, desktop app, API, or hybrid?
- What are the major parts of the system?
- What runs in the browser?
- What runs on the server?
- What runs locally/offline?

## Recommended Diagram

```txt
User Device
  ↓
Frontend App
  ↓
API / Server Actions
  ↓
Database / Storage
  ↓
External Services
```

## Frontend

### Questions
- What framework is used?
- What pages/screens exist?
- What state is local?
- What state comes from the server?
- What should be cached?

## Backend

### Questions
- Is there a backend?
- What handles business logic?
- What APIs or server functions exist?
- What background jobs exist?

## Database

### Questions
- What database is used?
- What tables/collections exist?
- What relationships exist?
- What data should be indexed?

## Offline / Sync

### Questions
- Does the app need offline mode?
- What data must be available offline?
- What actions can be queued offline?
- What happens when sync fails?
- What wins during conflicts: local data, server data, or user choice?

## External Services

### Questions
- What third-party APIs are used?
- What services require API keys?
- What services are optional?
- What happens if an external service is down?
