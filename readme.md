# Documentation

Central documentation for the BCX19 [#3 Hack Challenge Buildings](https://bosch-connected-world.com/hackathon/connectedbuildings/).

## :mega: Communication

During the hackathon we have for the hack challenge an own slack channel:
<https://bcx19buildings.slack.com>

## :construction_worker: Bosch ID

To use the developer portal or connected building the precondition is to have a Bosch ID. Therefore register your [Bosch ID here](https://myaccount.bosch.com/BeaPUssWeb/registration)

## :wrench: Setup

Please find here a high-level overview of the equipment and software stacks, which you might want to use in your hack. For each of this tools find bellow more details.

[![Setup](assets/bcx19_cb_overview.png)](https://bcx19-buildings.github.io/documentation/assets/bcx19_cb_overview.png)

## :blue_book: Connected Building

Connected Building is a cloud based collection of services to implement use-cases for commercial buildings. The diagram below gives a overview of the solution architecture landscape and the services.

![Connected Building Overview](assets/connectedbuilding_overview.png)

**Credentials cockpit / REST API**
If you want to use the Connected Building Services e.g. cockpit you require:

- [Bosch ID](https://myaccount.bosch.com/BeaPUssWeb/registration)
- Invitation connected building services.

For the invitation to the connected building services please send a message to slack channel: `#cb-invitation`.

**Credentials ingest data**
To send data to the connected building a `system-id` and `token` is required. Ask the connected building for your credentials.

**Connected Building REST APIs**
The APIs are based on common REST concepts. Authentication oAuth 2.0 `Client Credentials Grant Type` and `Authorization Code Grant Type` are supported to get a access token for the API.

API | Description | Swagger
-- | -- | --
**External System Connector** | API to ingest data from external building systems. Data is ingested as events (create and update event body based on [Haystack](https://project-haystack.org/doc/Json) JSON) . | [docs](https://eu-dev.bosch-connectedbuilding.com/documentation/swagger/swagger-ui.html?urls.primaryName=system-connector-app)
**Equipment State** | API to query the actual state of the equipment and the building equipment | [docs](https://eu-dev.bosch-connectedbuilding.com/documentation/swagger/swagger-ui.html?urls.primaryName=state-app)
**Dashboard Management** | API to mange the resources for the dashboard (cockpit) e.g. heat-map or simple times series data. | [docs](https://eu-dev.bosch-connectedbuilding.com/documentation/swagger/swagger-ui.html?urls.primaryName=dashboard-app)

**Starters**
Please find here a list of starter to get starters with the connected building services.
Starter | Description | Link
-- | -- | --
**Equipment tracking starter** | Starter with examples how to ingest data via the REST API. Shows also how to assign a equipment to an existing space. |  https://github.com/bcx19-buildings/equipment-tracking-starter

## :blue_book: HERE Navigation & Routing

TBD

## :blue_book: Bosch Asset Tracing Solution

TBD

## :blue_book: RefineMysite & TrackMyTools

TBD

## :blue_book: Bosch IoT Suite

TBD

http://ec2-54-93-194-192.eu-central-1.compute.amazonaws.com/bc/x/devices

## :blue_book: Microsoft Azure

TBD

## :blue_book: InnoHub

TBD

## :blue_book: Bosch Securities Cameras

TBD

## :blue_book: SAST

TBD

## :blue_book: Bosch Connected Devices and Solutions

TBD

## :blue_book: Zumtobel 

TBD

## :blue_book: Bosch B/S/H/ Home Connect

TBD

## :blue_book: Bosch B/S/H/ PAI

TBD

## :blue_book: Bosch Common Gateway

TBD

## :blue_book: Bosch IIOT Gateway

TBD

## :blue_book: Bosch Thermo-technology EasyControl

TBD
