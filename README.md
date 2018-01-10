# BPC Interact Customer Portal
Source code repository for the BPC Interact customer portal application

## Scope
The BPC Interact customer portal will provide a central point of contact and collaboration for participating institutions, the biorepository team, and the cancer research community at large.  The scope of the Interact portal includes tooling for collaboration on case-level issues as well as workflow automation to speed processes and ensure a consistent experience for those reliant on services from the biorepository.
 - **Investigator Services** will leverage a business intelligence platform to provide near real-time statistics and status of biospecimens collected on their clinical trial(s) as well as project details related to how the specimens are used/tested (as well as other utilization data)
 - **CRA Services** will include issue/resolution management to streamline communication as well as resources for specimen preparation/submission, kit ordering, etc. 
 - **Sponsor Group Services** will allow sponsors to view detailed biospecimen aggregate data as well as relevant operational project statistics and statuses.

## Project Architecture
Architecture and design activities to support the BPC Interact customer portal are currently underway.  Key components of the project underpinnings include:
 - Unified user account creation/authentication/management (partnered with [Auth0](https://auth0.com/))
 - Workflow engineering and automation (partnered with [Joget Workflow](http://www.joget.org))
 - Document imaging and management (partnered with [SeedDMS](http://www.seeddms.org/index.php))
 - Web application UI framework (partnered with [Vaadin](https://vaadin.com/))
 - User-driven analytics (partnered with [ReportServer](https://reportserver.net/en/))
 - Deployment/runtime architecture ([Docker](https://www.docker.com/))
 - Messaging and Integration ([Apache Kafka](https://kafka.apache.org/), [RabbitMQ](https://www.rabbitmq.com/), [Apache Camel](https://camel.apache.org/))
 - Data Extraction/Transformation ([Pentaho Data Integration](http://www.pentaho.com/product/data-integration))
 - Programming tooling (Java, Spring Boot, Groovy, Gradle, Maven, Nexus)
 
## Implementation
The Bank Customer Portal will be designed and hosted by the Biopathology Center Informatics Department at the Research Center of Nationwide Children’s Hospital.  A key goal of the Portal will be the modernization of the various systems which supports inclusion of newer NCTN resources into the biospecimen tracking data pipeline, including the Clinical Trials EDC (Medidata RAVE) and the centralized distribution request system (NCTN Navigator). 

## Implementation Partners
 - ![JWT Auth for open source projects](https://cdn.auth0.com/oss/badges/a0-badge-dark.png)
 - ![ReportServer Enterprise](https://user-images.githubusercontent.com/10222432/34792864-742045ca-f617-11e7-82cd-29aa1ff4f8f9.png)
 - ![Joget Workflow](https://user-images.githubusercontent.com/10222432/34792432-faa32330-f615-11e7-8cd3-c17ecf20e610.png)