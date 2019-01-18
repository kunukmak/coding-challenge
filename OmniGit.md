# OmniGit

The objective of OmniGit is to allow an organization to migrate their codebase across different vendors (as for instance GitHub, BitBucket, GitLab, etc.).

## Terminology

- **Provider**: this is any third party service that hosts git repositories. An example could be GitHub, Bitbucket, GitLab, etc.

## User Stories

- As a user I want to select two providers among a list of supported ones, a "current" provider and a "target" provider (the two could potentially be the same). Then I can specify the repository name I want to migrate so that I can order the migration.
- As a user I want to be able to safely allow OmniGit to access both the "current" provider and the "target" provider (through oAuth2 or similar) so that the migration can be successfully performed.
- As a user I want to find in new repository hosted at the "target" provider all my code originally contained in the repository at the "current" provider so that I can safely continue develop on any branch that was remotely available at the "current" provider.
- **[Senior Level]**: As a user I want to find at the "target" provider all the issues originally filed at the "current" provider so that I can keep track of them at the new provider.
- **[Senior Level]**: As a user I want to find at the "target" provider all the wiki contents originally published at the "current" provider so that I do not have to copy/paste this content manually.
- **[Senior Level]**: As a user I am able to signup and signin to the OmniGit web application and/or APIs so that I can safely access my profile information, and I can get a status on the resources I am managing through OmniGit.
