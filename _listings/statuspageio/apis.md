---
name: StatusPage.io
x-slug: statuspageio
description: StatusPage.io is the best way for web infrastructure, developer API,
  and SaaS companies to get set up with their very own status page in minutes
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
x-kinRank: "8"
x-alexaRank: "34645"
tags: StatusPage.io
created: "2018-05-22"
modified: "2018-05-22"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/apis.md
specificationVersion: "0.14"
apis:
- name: StatusPage.io Get your page profile
  x-api-slug: statuspageio
  description: Get your page profile
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id].json
  tags: Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idjson-get-openapi.md
- name: StatusPage.io Update your page profile
  x-api-slug: statuspageio
  description: Update your page profile
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id].json
  tags: Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idjson-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idjson-patch-openapi.md
- name: StatusPage.io Get a list of all components
  x-api-slug: statuspageio
  description: Get a list of all components
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components.json
  tags: Components
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentsjson-get-openapi.md
- name: StatusPage.io Create a component
  x-api-slug: statuspageio
  description: Create a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components.json
  tags: Components
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentsjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentsjson-post-openapi.md
- name: StatusPage.io Update a component
  x-api-slug: statuspageio
  description: Update a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id].json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idjson-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idjson-patch-openapi.md
- name: StatusPage.io Delete a component
  x-api-slug: statuspageio
  description: Delete a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id].json
  tags: Components
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idjson-delete-openapi.md
- name: StatusPage.io Get a list of all incidents
  x-api-slug: statuspageio
  description: Get a list of all incidents
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents.json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsjson-get-openapi.md
- name: StatusPage.io Unresolved Only
  x-api-slug: statuspageio
  description: Unresolved Only
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/unresolved.json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsunresolvedjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsunresolvedjson-get-openapi.md
- name: StatusPage.io Scheduled Only
  x-api-slug: statuspageio
  description: Scheduled Only
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/scheduled.json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsscheduledjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsscheduledjson-get-openapi.md
- name: StatusPage.io Create a realtime incident
  x-api-slug: statuspageio
  description: Create a realtime incident
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents.json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsjson-post-openapi.md
- name: StatusPage.io Update an incident (only applies to realtime and scheduled incidents)
  x-api-slug: statuspageio
  description: Update an incident (only applies to realtime and scheduled incidents)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/[incident_id].json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsincident-idjson-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsincident-idjson-patch-openapi.md
- name: StatusPage.io Delete an incident
  x-api-slug: statuspageio
  description: Delete an incident
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/[incident_id].json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsincident-idjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsincident-idjson-delete-openapi.md
- name: StatusPage.io Tune an Incident Update
  x-api-slug: statuspageio
  description: Tune an Incident Update
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/[incident_id]/incident_updates/[incident_update_id].json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsincident-idincident-updatesincident-update-idjson-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idincidentsincident-idincident-updatesincident-update-idjson-patch-openapi.md
- name: StatusPage.io Delete a subscriber
  x-api-slug: statuspageio
  description: Delete a subscriber
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/subscribers/[subscriber_id].json
  tags: Subscribers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idsubscriberssubscriber-idjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idsubscriberssubscriber-idjson-delete-openapi.md
- name: StatusPage.io Get a list of available public metric providers
  x-api-slug: statuspageio
  description: Get a list of available public metric providers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///metrics_providers.json
  tags: Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/metrics-providersjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/metrics-providersjson-get-openapi.md
- name: StatusPage.io Get a list of metric providers linked to your page
  x-api-slug: statuspageio
  description: Get a list of metric providers linked to your page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics_providers.json
  tags: Metric Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetrics-providersjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetrics-providersjson-get-openapi.md
- name: StatusPage.io Get a list of metrics created for a linked metrics provider
  x-api-slug: statuspageio
  description: Get a list of metrics created for a linked metrics provider
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics_providers/[metrics_provider_id]/metrics.json
  tags: Metric Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetrics-providersmetrics-provider-idmetricsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetrics-providersmetrics-provider-idmetricsjson-get-openapi.md
- name: StatusPage.io Create a custom metric
  x-api-slug: statuspageio
  description: Create a custom metric
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics_providers/[metrics_provider_id]/metrics.json
  tags: Metric Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetrics-providersmetrics-provider-idmetricsjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetrics-providersmetrics-provider-idmetricsjson-post-openapi.md
- name: StatusPage.io Submit data for a custom metric
  x-api-slug: statuspageio
  description: Submit data for a custom metric
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics/[metric_id]/data.json
  tags: Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetricsmetric-iddatajson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetricsmetric-iddatajson-post-openapi.md
- name: StatusPage.io Delete all data for a custom metric
  x-api-slug: statuspageio
  description: Delete all data for a custom metric
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics/[metric_id]/data.json
  tags: Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetricsmetric-iddatajson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idmetricsmetric-iddatajson-delete-openapi.md
- name: StatusPage.io List users
  x-api-slug: statuspageio
  description: List users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///organizations/[organization_id]/users.json
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/organizationsorganization-idusersjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/organizationsorganization-idusersjson-get-openapi.md
- name: StatusPage.io Create a user
  x-api-slug: statuspageio
  description: Create a user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///organizations/[organization_id]/users.json
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/organizationsorganization-idusersjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/organizationsorganization-idusersjson-post-openapi.md
- name: StatusPage.io Delete a user
  x-api-slug: statuspageio
  description: Delete a user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///organizations/[organization_id]/users/[user_id].json
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/organizationsorganization-idusersuser-idjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/organizationsorganization-idusersuser-idjson-delete-openapi.md
- name: StatusPage.io Retrieve a list of users
  x-api-slug: statuspageio
  description: Retrieve a list of users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-usersjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-usersjson-get-openapi.md
- name: StatusPage.io Create a user who can view your status page
  x-api-slug: statuspageio
  description: Create a user who can view your status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-usersjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-usersjson-post-openapi.md
- name: StatusPage.io Change information for a user who can view your status page
  x-api-slug: statuspageio
  description: Change information for a user who can view your status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id].json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idjson-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idjson-patch-openapi.md
- name: StatusPage.io Delete a user who could access your status page
  x-api-slug: statuspageio
  description: Delete a user who could access your status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id].json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idjson-delete-openapi.md
- name: StatusPage.io Assign components to a page access user (overwrites existing
    components)
  x-api-slug: statuspageio
  description: Assign components to a page access user (overwrites existing components)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id]/components.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idcomponentsjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idcomponentsjson-post-openapi.md
- name: StatusPage.io Assign components to a page access user (adds new components
    to a user)
  x-api-slug: statuspageio
  description: Assign components to a page access user (adds new components to a user)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id]/components.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idcomponentsjson-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idcomponentsjson-patch-openapi.md
- name: StatusPage.io Remove all components from a page access user
  x-api-slug: statuspageio
  description: Remove all components from a page access user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id]/components.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idcomponentsjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-userspage-access-user-idcomponentsjson-delete-openapi.md
- name: StatusPage.io Assign page access users to a component
  x-api-slug: statuspageio
  description: Assign page access users to a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idpage-access-usersjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idpage-access-usersjson-post-openapi.md
- name: StatusPage.io Remove a component from all page access users
  x-api-slug: statuspageio
  description: Remove a component from all page access users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idpage-access-usersjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idpage-access-usersjson-delete-openapi.md
- name: StatusPage.io Retrieve a list of groups
  x-api-slug: statuspageio
  description: Retrieve a list of groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupsjson-get-openapi.md
- name: StatusPage.io Create a group that will define what and who can view elements
    of your status page
  x-api-slug: statuspageio
  description: Create a group that will define what and who can view elements of your
    status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupsjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupsjson-post-openapi.md
- name: StatusPage.io Change information for a group
  x-api-slug: statuspageio
  description: Change information for a group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id].json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idjson-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idjson-patch-openapi.md
- name: StatusPage.io Delete a group
  x-api-slug: statuspageio
  description: Delete a group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id].json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idjson-delete-openapi.md
- name: StatusPage.io Assign components to a page access group (overwrites existing
    components)
  x-api-slug: statuspageio
  description: Assign components to a page access group (overwrites existing components)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id]/components.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idcomponentsjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idcomponentsjson-post-openapi.md
- name: StatusPage.io Assign components to a page access group (adds new components
    to a group)
  x-api-slug: statuspageio
  description: Assign components to a page access group (adds new components to a
    group)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id]/components.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idcomponentsjson-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idcomponentsjson-patch-openapi.md
- name: StatusPage.io Remove all components from a page access group
  x-api-slug: statuspageio
  description: Remove all components from a page access group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id]/components.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idcomponentsjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idpage-access-groupspage-access-group-idcomponentsjson-delete-openapi.md
- name: StatusPage.io Assign page access groups to a component
  x-api-slug: statuspageio
  description: Assign page access groups to a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_groups.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idpage-access-groupsjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idpage-access-groupsjson-post-openapi.md
- name: StatusPage.io Remove a component from all page access groups
  x-api-slug: statuspageio
  description: Remove a component from all page access groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_groups.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idpage-access-groupsjson-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/pagespage-idcomponentscomponent-idpage-access-groupsjson-delete-openapi.md
- name: StatusPage.io
  x-api-slug: statuspageio
  description: StatusPage.io is the best way for web infrastructure, developer API,
    and SaaS companies to get set up with their very own status page in minutes
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https:///
  tags: StatusPage.io
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage.io/master/_listings/statuspageio/openapi.md
x-common:
- type: x-authentication
  url: http://doers.statuspage.io/api/authentication/
- type: x-blog
  url: http://blog.statuspage.io
- type: x-blog-rss
  url: http://blog.statuspage.io/posts.rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/statuspage
- type: x-developer
  url: http://doers.statuspage.io/
- type: x-email
  url: hi@statuspage.io
- type: x-github
  url: https://github.com/statuspage
- type: x-pricing
  url: https://www.statuspage.io/pricing
- type: x-privacy
  url: https://www.statuspage.io/privacy-policy
- type: x-security
  url: https://www.statuspage.io/security
- type: x-status
  url: http://metastatuspage.com/
- type: x-terms-of-service
  url: https://www.statuspage.io/terms-of-service
- type: x-twitter
  url: https://twitter.com/statuspageio
- type: x-website
  url: https://www.statuspage.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---