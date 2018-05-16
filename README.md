# GreenHub Project Roadmap

## Core

### Phase 1 (current)
**Planned release:** End of May 2018
- [ ] Release batteryhub 1.2.0
- [ ] Finish the GreenHub REST API
- [ ] Upgrade lumberjack 
- [ ] Write full [documentation](https://docs.greenhubproject.org)
- [ ] Refactor dataset generator script (see [issue](https://github.com/greenhub-project/farmer/issues/4))
- [x] Launch *status.greenhubproject.org* to monitor all the other project services
- [ ] Update privacy policy for GDPR compliance

### Phase 2
**Planned release:** Not scheduled
- [ ] Create a migration helper scripts for the database
- [ ] Release batteryhub 2.0.0
- [ ] Release fisherman 1.0.0

*Note:* Adopt [https://conventionalcommits.org/](https://conventionalcommits.org/) for all modules

### Backlog
- [ ] Draft new module beekeeper (desktop GUI for fisherman)
- [ ] Redesign [https://greenhubproject.org](https://greenhubproject.org)
- [ ] Move snapshot of dataset dump to a mirror location (e.g. *static.greenhubproject.org*)

## Modules

### batteryhub
#### 1.2
- Status: beta
- Goal: offer a final stable release for the current version of the Android app
#### 2.x
- Status: under discussion
- Goal: rewrite core components + add a recommendations channel and benchmark util

### farmer
- Status: in development
- Goal: offer a web dashboard to visualize the data from the GreenHub database and provide REST API

### lumberjack
- Status: in development
- Goal: upgrade `greenhub-cli` to be compatible with the complete REST API

### fisherman
- Status: under discussion
- Goal: provide a API/CLI for data analysis utils
