# Development Checkpoint

Introduction
------------
To provide overall project status and to have a place to identify all critical issues and identify action, owners and review timelines.

Schedule
--------
[Schedule and Sprint Cadence](https://github.com/zowe/community/blob/master/Project%20Management/PI%20Planning/20PI3%20Planning/Zowe%20PI%20%26%20Sprint%20Cadence.md)


Agenda Items
------------
1. Start Recording
2. ZLC Updates
3. Current Release and Build Status (Steve)
4. Plan
     - Discuss 1.16.0 Release (GA Oct 2, 2020)
     - System Demo (Sept 29, 2020) Sept 28 is State Holiday in Czech Rep. Moving out 1 day to Sept 29 at 11:00 a.m. EDT
     - PI Planning Preparation
       - Agenda (https://ibm.ent.box.com/notes/713879742265)
       - Squad Input Objectives (https://ibm.ent.box.com/notes/712189314183)
5. Squad Status:
    - Onboarding (JoeW/Rose)
    - Core/Web/Editor (JPL/Nolan/James)
      - ZSS logger formatting & control
      - Make Docker work with certificate verification on
      - Statically Register ZSS Into the Mediation Layer
      - File Abilities - Changing Permissions
    - API Mediation Layer & Security (Elliot/Michal S/Petr P)
      - ZSS implementation for x509 in progress
      - Improved API ML's Single Sign-On documentation (#677)
      - Additional objective for 20PI4: Metrics Dashboard for ML Services #820
    - Performance & High Availability (HA) (Jack)
      - Performance test case now supports non-GET http requests (POST/PUT/DELETE etc).
      - Performance test pipeline is setup can be started with customized parameters, also scheduler is added to run idle test case every day (no traffic workload send to server).
      - More discussion on HA, redis vs other state sharing method, dynamic registration, etc.
      - Working on collecting SMF30 records.
    - Documentation (Brandon/Ashley/Jim/Jason)

6. Legal Requirements
    - None

7. Community Backlog
    - TBD
8. Roundtable
    - None

Action Items
------------
- None
