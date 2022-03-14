# Features and RoadMap
<!-- Eric Sandbling, https://github.com/ericsandbling -->

This document establishes a baseline for all features defined within the scope of the _openApiary_ project.


Here goes the project backlog. Each top level heading represents a feature in the project, and the priority is determined by the order of the headings.

When a feature has been implemented, documented and incorporated in the main branch of the project the feature will be removed from the backlog.

<!-- Short descriptive summary of the feature
Benefit hypothesis – The proposed measurable benefit to the end user or business -->

## Hive Design

Thorough design specifications for the hive, including construction details, part lists, assembly instructions and drawings.

Open detailed designs promote feedback and better understanding of the design, leading to improvements in terms of:

* Sustainability
* Cost
* Efficiency of use
* etc.

## Remote Monitoring

Remote monitoring of the bee hive using self sustained power sources, e.g. solar panels.

The added value of having a remote monitoring system for the hive would include benefits such as:

* Reduce the need for physical inspections, as they can be done remotely.
* Reduced time before a problem with a colony or hive is detected.
* Increase accuracy and understanding of colony and hive health.

**Resources:**

* [osbeehives](https://www.osbeehives.com)

### Solution Proposals

Main solution should consist of three main subsystems; *hiveClient*, *hiveCloud* and *userClient*.

Multiple setups of the system should be considered, i.e.:

* *hiveClient* and *userClient* only
* *hiveClient* and *hiveCloud* only
* all subsustems
* etc.

Each subsystem should be able to talk to another without the need for the complete system.

**hiveClient:**
The system in the hive responsible for monitoring and publishing data from the hive.

The *hiveClient* should be self-sustained with power, using e.g. solar panels on the roof of the hive.

Multiple connectivity options should be available to publish data to the *hiveCloud*.

**hiveCloud:**

The cloud system responsible for collecting and processing data from the *hiveClient*, and providing to the *userClient*.

**userClient:**

End-user interface, e.g. smartphone or web-app, used to manage, monitor and setup *hiveClients*.
