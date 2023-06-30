---
datetime: 2023-06-28T12:00:00+02:00
location: Online, Discord (https://bit.ly/UnikraftDiscord), the `#monkey-business` voice channel
teams:
 - app-compat
participants:
- Andra Paraschiv
- Cosmin Vancea
- Florin Postolache
- Stefan Jumarea
- Teodor Teugea
- Tianyi Liu
- Marco Schlumpp
- Simon Kuenzer
---

### Agenda

* Updates in general
* Reviews

## Discussions

Stefan: Finished getdents64 problem. I need to clean up the code.

Teodor: Working on upstreaming redis. Waiting for a response on benchmark spike on redis.

Tianyi: Need reviewer for VDSO design

### TODOs and Decisions

Stefan: Clean up code for getdents64 fix code and do PR

Teodor: Work on upstreaming redis

Teodor: Investigate benchmark spike on redis

Cosmin Vancea: Find a way to run the openjdk tests

Simon Kuenzer: Do a high level review on Tianyi's VDSO design

Simon Kuenzer: Finish posix-netlink

Simon Kuenzer: Finish shutdown on app-elfloader
