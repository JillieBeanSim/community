# Zowe API ML & Security Squad - 21PI2 Objectives (May 2021 to July 2021)


## High-availability support implementation

* [API ML Squad Issue: Support for high availability / sysplex distributor in API Mediation Layer #705](https://github.com/zowe/api-layer/issues/705)  
Validate high availability for the API ML in time for Zowe 1.22. Explore Redis as an alternative to VSAM as an on-z persistent solution for the caching service.

API ML Squad Plan:  
[HA: Caching API - POC of Redis - On-platform #1192](https://github.com/zowe/api-layer/issues/1192)  
[Spike: Deploy API ML in HA setup in external environment #1360](https://github.com/zowe/api-layer/issues/1360)  
[Integrate the HA setup in our Integration Testing procedure #1361](https://github.com/zowe/api-layer/issues/1361)  
[Properly handle redis reconnect error #1363](https://github.com/zowe/api-layer/issues/1363)  
  
  
## Support Mainframe Password change

* [Support Mainframe Password change #1377](https://github.com/zowe/api-layer/issues/1377)  
Facilitation and support for mainframe password changes originating from clients. Password change facility that can scale regardless of the security provider in place (z/OSMF, SAF Direct, etc).  

API ML Squad Plan:  
[Add possibility to change passwords via SAF #815](https://github.com/zowe/api-layer/issues/815)  
[Add support to change password via zOSMF #1418](https://github.com/zowe/api-layer/issues/1418)  
[Add support for changing the password using ZSS #1419](https://github.com/zowe/api-layer/issues/1419)

  
## Configurable deterministic routing

* [Configurable deterministic routing #1378](https://github.com/zowe/api-layer/issues/1378)  
Currently, the API ML gateway balances workloads in a round robin fashion. However, some services want to handle user requests from the same instance of that service. Deterministic routing for user requests, where each request with a user ID goes to the same service instance to which it was originally routed. Additionally, there should be a configurable limit for the number of users each instance can handle.

API ML Squad Plan:  
[Implement deterministic routing for one Gateway instance #1420](https://github.com/zowe/api-layer/issues/1420)  
[Add instance user limits for deterministic routing #1421](https://github.com/zowe/api-layer/issues/1421)  
[Support deterministic routing in HA setup #1412](https://github.com/zowe/api-layer/issues/1412)  
[Spike: Investigate and document performance of deterministic routing in HA setup #1413](https://github.com/zowe/api-layer/issues/1413)  
[Configurable user limitation behaviour for deterministic routing #1422](https://github.com/zowe/api-layer/issues/1422)  
[Make deterministic routing load balancing behaviour configurable.#1423](https://github.com/zowe/api-layer/issues/1423)


## Improve testing for the API Mediation Layer both on & off platform

* [Improve testing for the API Mediation Layer both on & off platform #1341](https://github.com/zowe/api-layer/issues/1341)  
Increase confidence in the API ML by improving: build stability, developer experience, reliability of codebase  

API ML Squad Plan:  
[Integration test cleanup #1417](https://github.com/zowe/api-layer/issues/1417)  
[Enhance our higher order test suites #1332](https://github.com/zowe/api-layer/issues/1332)  
[Faster startup of services for testing #1415](https://github.com/zowe/api-layer/issues/1415)  
[Test parallelization #1416](https://github.com/zowe/api-layer/issues/1416)  
[Isolate platform dependent code into library #1424](https://github.com/zowe/api-layer/issues/1424)  
[Flaky test ApiCatalogEndpointIntegrationTest #1342](https://github.com/zowe/api-layer/issues/1342)  
[move e2e tests on stable environment #1187](https://github.com/zowe/api-layer/issues/1187)  


## SPIKE Zowe API ML to adopt and surface ESM's consolidated SAF Identity tokens

* [Zowe API ML to adopt and surface ESM's consolidated SAF Identity tokens #1390](https://github.com/zowe/api-layer/issues/1390)  
RESEARCH how to provide access to Zowe Conformant APIs via Zowe API ML using SAF Identity JWTs that are issued, validated, and managed directly by z/OS (ESM SAF).  
  - presents an opportunity to unify the authentication mechanism southbound of the API ML Gateway  
  - for use cases that combine API ML and standalone routed services so SAF IDT is an immediate solution for this 

API ML Squad Plan:  
[Zowe API ML to adopt and surface ESM's consolidated SAF Identity tokens #1390](https://github.com/zowe/api-layer/issues/1390)  


## Implement and Release AT-TLS aware Zowe API ML

* [API ML AT-TLS aware implementation #1345](https://github.com/zowe/api-layer/issues/1345)  
Our objective is to integrate with the z/OS native AT-TLS component to better fulfill TLS security requirements coming from users. Following the research undertaken in 21PI1, this objective will see the implementation and release.  

API ML Squad Plan:  
[Possibility to switch between AT-TLS and application TLS #1346](https://github.com/zowe/api-layer/issues/1346)  
[AT_TLS aware Gateway #1347](https://github.com/zowe/api-layer/issues/1347)  
[AT-TLS aware Discovery service #1348](https://github.com/zowe/api-layer/issues/1348)  


## Metrics for Zowe API ML

* [Metrics Dashboard for ML Services #820](https://github.com/zowe/api-layer/issues/820)  
Onboard intern(s) so they can get started building the Metrics service in 21PI3.  

API ML Squad Plan:  
[Create Metrics Service #1098](https://github.com/zowe/api-layer/issues/1098)  


## Zowe / api-layer backlog management

* [Focus on priority / high impact issues in Github](https://github.com/zowe/api-layer/labels/21PI2)
