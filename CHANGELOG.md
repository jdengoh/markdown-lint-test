# Changelog

## 29 April 2025 (v0.2.1)

- Added guide for [Reviewers](./docs/REVIEWERS_STEP_BY_STEP.md) and [Contributors](./docs/CONTRIBUTORS_STEP_BY_STEP.md)
- Updated Redis Host and Redis Port to initialise only when semantic caching is enabled
- Updated `ServiceURI` to a more appropriate name
- Fixed premature closing of Key Vault client which previously used asynchronous context manager

## 17 April 2025 (v0.2.0)

- Implemented JWT token for session ID with expiry time
- Frontend pop-up modal to inform user session expired
- Compress HTTP Content-Length response data size

## 17 April 2025 (v0.1.0)

- Set up [GitHooks](.githooks/), automation with [GitHub workflows](.github/workflows/) and [Contributing](CONTRIBUTING.md) guide
- Consolidated events before serving application
- Updated `NoSourcesError` standard responses in Malay and Tamil (reviewed by Health Hub)
- Show scrollbar on the chat page
- Removed GIFs from User Guide due to large file size
