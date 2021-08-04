# Dynamics 365 Project Operations solution for timeghost.io

Initial stab at creating a Solution for sync Clients, Projects and Tasks out of Project Operations into [timeghost.io](https://timeghost.io), and equally getting time entries back into Project Operations.

## Overview

Needed a way to sync data into timeghost.io from projects in Dynamics 365, and as the timeghost.io guys provide a fairly usable Connector for Power Automate thought I'd have a go using it to get data between the two systems. The Solution here is the result of that work.

## Requirements

At this time, the Solution was developed using a Dynamics 365 Project Operations environment, however I suspect it would work for Project on the Web as well where the environment has the Common Data Model (as it uses Account for Clients).

Repo is unpacked so probably requires packing before importing as an unmanaged solution into a relevant Power Platform Environment. Not suggested for direct deployment to a production environment.

### Additional Deployemnt Notes

* Environment variables required to hardcode Timeghost Workspace ID and the ID of a user that Projects get created with Manager level.
* Contains Cloud Flows that run on a recurring schedule.

## License

Unless otherwise stated, licensed under [MIT License](LICENSE).
