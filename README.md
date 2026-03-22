# Amon Hogue

Network Engineering Manager and Architect focused on designing and leading automation first systems that make network deployments predictable, repeatable, and scalable.

I architect and guide the implementation of network staging, source of truth, configuration, deployment, and validation pipelines, turning intent (data) into safe, tested deployments while reducing variation and operational risk.

My role centers on system design, source of truth strategy, workflow standardization, and team alignment, ensuring automation improves flow, quality, and throughput rather than adding complexity.

My approach is influenced by the books *The Phoenix Project* and *The Goal*, focusing on flow, reducing bottlenecks, and improving end to end systems rather than optimizing tasks in isolation.

After years working in traditional network environments, I have come to appreciate the potential of network automation and software defined approaches to improve how systems are built, validated, and operated.

I operate across multi vendor environments, designing systems that integrate any platform capable of API driven control.

---

## What I Lead

* Network staging and deployment systems  
  End to end pipelines: structured input → source of truth → config generation → deployment → QA validation → shipment  

* System architecture and workflow design  
  Defining how data, source of truth, automation, and validation interact across the staging lifecycle  

* Source of truth strategy  
  Establishing NetBox and other API driven systems as the foundation for consistent builds, inventory, and IPAM  

* Automation strategy and enablement  
  Guiding how Python, Jinja, Ansible, and APIs are applied by engineering teams  

* QA and validation frameworks  
  Ensuring builds are tested, measurable, and validated before leaving staging  

* Operational guardrails  
  Standardizing safe change practices, rollback strategies, and repeatable workflows  

---

## What I Build

* Configuration drift detection (config_drift_detector)  
  Running configuration → structured data → comparison against intended state → actionable drift identification and reporting  

* Config parsing and normalization  
  Transforming raw configurations into structured, comparable data models  

* Change safety workflows  
  Dry run diffs, pre and post validation, and controlled rollout patterns  

* Inventory and data normalization  
  Aggregating data from multiple systems into a consistent, usable structure  

* Operational integrations  
  Lightweight automation and integrations to support visibility, coordination, and change tracking  

---

## Platform Agnostic Approach

Systems are designed to operate across any environment that exposes data and control through APIs.

Experience across:
* Cisco (Catalyst Center, Meraki APIs)  
* Ubiquiti (UniFi and UISP)  
* Juniper and other API capable platforms  

---

## Featured Work

🔧 network_staging_factory  
A reference architecture demonstrating a scalable network staging pipeline:

Structured Input → NetBox → Config Generation → Deployment → QA Validation → Ship  

🔍 config_drift_detector  
A working model for identifying and reporting configuration drift against intended state  

---

## Philosophy

Scale comes from reducing variation, not increasing effort.

---

## Tooling

Python · Ansible · Nornir · Netmiko/NAPALM · Jinja2  
Cisco Catalyst Center and Meraki APIs · Ubiquiti UniFi and UISP APIs · Webex REST and Webhooks  
GitHub Actions · pytest · pre commit · Wireshark  

🔗 GitHub Portfolio: https://github.com/amonhogue
