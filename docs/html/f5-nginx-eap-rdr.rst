.. toctree::
   :titlesonly:
   :maxdepth: 4

================================================
Essential App Protect NGINX Redirect Example
================================================

Summary
------------------------------------------------

This document is a theoretical exercise in the consolidation of like Applications for different
environments that are generally seen across application stacks for the purpose of testing all 
stages of the application lifecycle, for example;

* *Non-Production Environments*

  * User Acceptance Testing (UAT)
  * Quality Acceptance Testing (QAT)
  * System Integration Testing (SIT)

* *Development Environments*

  * Development (dev)
  * Testing (tst)

* *Production Environments*

  * Blue/Green deployment stacks
  * production stacks

This paper will demostration, using the aforemented environment pattern, to demostrate how using
a combination of either NGINX or F5 BIG-IP to help consolidate in the aim of grouping like 
applications and reducation is Essental App Protect (EAP) endpoint configurations.

Deployment Example
------------------------------------------------
