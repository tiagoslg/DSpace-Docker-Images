# DSpace-Docker-Images
Repository for developing and managing published Docker images (https://hub.docker.com/u/dspace/) for DSpace development

__This project is under development__

__Note: These images are intended for DSpace development purposes and are not appropriate for production use.__

## Planned Images

- [dspace-postgres-pgcrypto](dspace-postgres-pgcrypto)
  - [dspace/dspace-postgres-pgcrypto](https://hub.docker.com/r/dspace/dspace-postgres-pgcrypto/)
- dspace-oracle
- [dspace-tomcat](dspace-tomcat)
  - [dspace/dspace-tomcat](https://hub.docker.com/r/dspace/dspace-tomcat/)
  - built on image with java, maven, tomcat
  - ant is added
  - has assumptions based on env DSPACE_INSTALL
- dspace-dev
  - Optimized for rapid build/test
- dspace-angular

## Tutorial

See [DSpace Docker Tutorial](tutorial.md)

### Demo Runtime Images (Experimental)
- dspace-runtime
  - a version of dpsace-tomcat with DSPACE_INSTALL already built and populated

### Service Specific Images
- [dspace-codenvy-tomcat](dspace-codenvy-tomcat)
  - [dspace/dspace-codenvy-tomcat](https://hub.docker.com/r/dspace/dspace-codenvy-tomcat/)
- [dspace-janitor-angular](dspace-janitor-angular)

## Planned Docker Compose Configurations
_The management of docker compose images is TBD_
- dspace6-postgres
- dspace6-oracle
- dspace7-postgres

## Other Ideas

## More information
For more information, join our [#dspace-docker Slack channel](https://dspace-org.slack.com/messages/C9YD42PV3).
