# Development Checkpoint

Introduction
------------
To provide overall project status and to have a place to identify all critical issues and identify action, owners and review timelines.

Schedule
--------
[Schedule and Sprint Cadence](https://github.com/zowe/community/blob/master/Project%20Management/Schedule/Zowe%20PI%20%26%20Sprint%20Cadence.md)

Meeting Recordings for Architecture Call and System Demos
-----------------
https://github.com/zowe/community/tree/master/Project%20Management

Agenda Items
------------
1. Start Recording
2. TSC Updates (Jakub)
3. Current Release and Build Status (Tom/Jack)
4. Plan
     - Discuss the next PI Planning Agenda
5. Squad Status:
    - Onboarding (Rose)
    - Core/Web/Editor (Nolan/James/Lenny)
      - Enhance app server storage API w/ destination parameter
      - Use getProfileNameForRequest to check SAF query access internally
      - Implement RBAC in ZSS
    - API Mediation Layer & Security (Elliot)  
      - SaveZosmfPublicKeyConsoleApplication may fail with self-signed z/OSMF certificate #1334
      - Upgrade Spring Boot to supported version #1352  
    - CLI (MikeB)
      - Zowe CLI - [JCL Symbolic Substitution Support](https://github.com/zowe/zowe-cli/pull/993)
      - Reviewing use of profiles in Zowe Plug-ins
    - Explorer (Jelly)
    - Systems
      - CI/CD (Tom)
        * Setup IP Explorer pipeline
        * Enabled verify certificates test case (Jack)
      - Performance & HA (Jack)
        * Ready to merge YAML config, launcher, setup component certificates changes
        * Continue testing and identify issues in HA deployment
    - Documentation (Michael Aimino)
      - Preparing for v1.21.0 docs 
      - Finalizing design of new Zowe doc site - [see the live prototype](https://zowe-docs.netlify.app/)
      - Preparing a demo of Zowe Slack bot on next Architecture call (by an IBM contributor)  
      - Reviewing and closing PRs 

6. Legal Requirements
    - None
7. Community Backlog
    - TBD
8. Roundtable
    - None

Action Items
------------
- None
