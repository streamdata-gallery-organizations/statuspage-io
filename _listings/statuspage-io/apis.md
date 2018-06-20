---
name: StatusPage.io
x-slug: statuspage-io
description: StatusPage.io is the best way for web infrastructure, developer API,
  and SaaS companies to get set up with their very own status page in minutes
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
x-kinRank: "8"
x-alexaRank: "34645"
tags: StatusPage.io
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/apis.md
specificationVersion: "0.14"
apis:
- name: StatusPage.io Get your page profile
  x-api-slug: statuspage-io
  description: Get your page profile
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id].json
  tags: Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-id-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-id-json-get-openapi.md
- name: StatusPage.io Update your page profile
  x-api-slug: statuspage-io
  description: Update your page profile
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id].json
  tags: Pages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-id-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-id-json-patch-openapi.md
- name: StatusPage.io Get a list of all components
  x-api-slug: statuspage-io
  description: Get a list of all components
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components.json
  tags: Components
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponents-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponents-json-get-openapi.md
- name: StatusPage.io Create a component
  x-api-slug: statuspage-io
  description: Create a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components.json
  tags: Components
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponents-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponents-json-post-openapi.md
- name: StatusPage.io Update a component
  x-api-slug: statuspage-io
  description: Update a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id].json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-id-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-id-json-patch-openapi.md
- name: StatusPage.io Delete a component
  x-api-slug: statuspage-io
  description: Delete a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id].json
  tags: Components
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-id-json-delete-openapi.md
- name: StatusPage.io Get a list of all incidents
  x-api-slug: statuspage-io
  description: Get a list of all incidents
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents.json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidents-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidents-json-get-openapi.md
- name: StatusPage.io Unresolved Only
  x-api-slug: statuspage-io
  description: Unresolved Only
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/unresolved.json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsunresolved-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsunresolved-json-get-openapi.md
- name: StatusPage.io Scheduled Only
  x-api-slug: statuspage-io
  description: Scheduled Only
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/scheduled.json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsscheduled-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsscheduled-json-get-openapi.md
- name: StatusPage.io Create a realtime incident
  x-api-slug: statuspage-io
  description: Create a realtime incident
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents.json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidents-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidents-json-post-openapi.md
- name: StatusPage.io Update an incident (only applies to realtime and scheduled incidents)
  x-api-slug: statuspage-io
  description: Update an incident (only applies to realtime and scheduled incidents)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/[incident_id].json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsincident-id-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsincident-id-json-patch-openapi.md
- name: StatusPage.io Delete an incident
  x-api-slug: statuspage-io
  description: Delete an incident
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/[incident_id].json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsincident-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsincident-id-json-delete-openapi.md
- name: StatusPage.io Tune an Incident Update
  x-api-slug: statuspage-io
  description: Tune an Incident Update
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/incidents/[incident_id]/incident_updates/[incident_update_id].json
  tags: Incidents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsincident-idincident-updatesincident-update-id-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idincidentsincident-idincident-updatesincident-update-id-json-patch-openapi.md
- name: StatusPage.io Delete a subscriber
  x-api-slug: statuspage-io
  description: Delete a subscriber
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/subscribers/[subscriber_id].json
  tags: Subscribers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idsubscriberssubscriber-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idsubscriberssubscriber-id-json-delete-openapi.md
- name: StatusPage.io Get a list of available public metric providers
  x-api-slug: statuspage-io
  description: Get a list of available public metric providers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///metrics_providers.json
  tags: Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/metrics-providers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/metrics-providers-json-get-openapi.md
- name: StatusPage.io Get a list of metric providers linked to your page
  x-api-slug: statuspage-io
  description: Get a list of metric providers linked to your page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics_providers.json
  tags: Metric Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetrics-providers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetrics-providers-json-get-openapi.md
- name: StatusPage.io Get a list of metrics created for a linked metrics provider
  x-api-slug: statuspage-io
  description: Get a list of metrics created for a linked metrics provider
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics_providers/[metrics_provider_id]/metrics.json
  tags: Metric Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetrics-providersmetrics-provider-idmetrics-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetrics-providersmetrics-provider-idmetrics-json-get-openapi.md
- name: StatusPage.io Create a custom metric
  x-api-slug: statuspage-io
  description: Create a custom metric
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics_providers/[metrics_provider_id]/metrics.json
  tags: Metric Providers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetrics-providersmetrics-provider-idmetrics-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetrics-providersmetrics-provider-idmetrics-json-post-openapi.md
- name: StatusPage.io Submit data for a custom metric
  x-api-slug: statuspage-io
  description: Submit data for a custom metric
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics/[metric_id]/data.json
  tags: Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetricsmetric-iddata-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetricsmetric-iddata-json-post-openapi.md
- name: StatusPage.io Delete all data for a custom metric
  x-api-slug: statuspage-io
  description: Delete all data for a custom metric
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/metrics/[metric_id]/data.json
  tags: Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetricsmetric-iddata-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idmetricsmetric-iddata-json-delete-openapi.md
- name: StatusPage.io List users
  x-api-slug: statuspage-io
  description: List users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///organizations/[organization_id]/users.json
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/organizationsorganization-idusers-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/organizationsorganization-idusers-json-get-openapi.md
- name: StatusPage.io Create a user
  x-api-slug: statuspage-io
  description: Create a user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///organizations/[organization_id]/users.json
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/organizationsorganization-idusers-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/organizationsorganization-idusers-json-post-openapi.md
- name: StatusPage.io Delete a user
  x-api-slug: statuspage-io
  description: Delete a user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///organizations/[organization_id]/users/[user_id].json
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/organizationsorganization-idusersuser-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/organizationsorganization-idusersuser-id-json-delete-openapi.md
- name: StatusPage.io Retrieve a list of users
  x-api-slug: statuspage-io
  description: Retrieve a list of users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-users-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-users-json-get-openapi.md
- name: StatusPage.io Create a user who can view your status page
  x-api-slug: statuspage-io
  description: Create a user who can view your status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-users-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-users-json-post-openapi.md
- name: StatusPage.io Change information for a user who can view your status page
  x-api-slug: statuspage-io
  description: Change information for a user who can view your status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id].json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-id-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-id-json-patch-openapi.md
- name: StatusPage.io Delete a user who could access your status page
  x-api-slug: statuspage-io
  description: Delete a user who could access your status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id].json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-id-json-delete-openapi.md
- name: StatusPage.io Assign components to a page access user (overwrites existing
    components)
  x-api-slug: statuspage-io
  description: Assign components to a page access user (overwrites existing components)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id]/components.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-post-openapi.md
- name: StatusPage.io Assign components to a page access user (adds new components
    to a user)
  x-api-slug: statuspage-io
  description: Assign components to a page access user (adds new components to a user)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id]/components.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-patch-openapi.md
- name: StatusPage.io Remove all components from a page access user
  x-api-slug: statuspage-io
  description: Remove all components from a page access user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_users/[page_access_user_id]/components.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-userspage-access-user-idcomponents-json-delete-openapi.md
- name: StatusPage.io Assign page access users to a component
  x-api-slug: statuspage-io
  description: Assign page access users to a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-users-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-users-json-post-openapi.md
- name: StatusPage.io Remove a component from all page access users
  x-api-slug: statuspage-io
  description: Remove a component from all page access users
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_users.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-users-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-users-json-delete-openapi.md
- name: StatusPage.io Retrieve a list of groups
  x-api-slug: statuspage-io
  description: Retrieve a list of groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groups-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groups-json-get-openapi.md
- name: StatusPage.io Create a group that will define what and who can view elements
    of your status page
  x-api-slug: statuspage-io
  description: Create a group that will define what and who can view elements of your
    status page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groups-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groups-json-post-openapi.md
- name: StatusPage.io Change information for a group
  x-api-slug: statuspage-io
  description: Change information for a group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id].json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-id-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-id-json-patch-openapi.md
- name: StatusPage.io Delete a group
  x-api-slug: statuspage-io
  description: Delete a group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id].json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-id-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-id-json-delete-openapi.md
- name: StatusPage.io Assign components to a page access group (overwrites existing
    components)
  x-api-slug: statuspage-io
  description: Assign components to a page access group (overwrites existing components)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id]/components.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-post-openapi.md
- name: StatusPage.io Assign components to a page access group (adds new components
    to a group)
  x-api-slug: statuspage-io
  description: Assign components to a page access group (adds new components to a
    group)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id]/components.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-patch-openapi.md
- name: StatusPage.io Remove all components from a page access group
  x-api-slug: statuspage-io
  description: Remove all components from a page access group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/page_access_groups/[page_access_group_id]/components.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idpage-access-groupspage-access-group-idcomponents-json-delete-openapi.md
- name: StatusPage.io Assign page access groups to a component
  x-api-slug: statuspage-io
  description: Assign page access groups to a component
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_groups.json
  tags: Page Access Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-groups-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-groups-json-post-openapi.md
- name: StatusPage.io Remove a component from all page access groups
  x-api-slug: statuspage-io
  description: Remove a component from all page access groups
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https://///pages/[page_id]/components/[component_id]/page_access_groups.json
  tags: Page Access Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-groups-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/pagespage-idcomponentscomponent-idpage-access-groups-json-delete-openapi.md
- name: StatusPage.io
  x-api-slug: statuspage-io
  description: StatusPage.io is the best way for web infrastructure, developer API,
    and SaaS companies to get set up with their very own status page in minutes
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/18898-statuspage-io.jpg
  humanURL: https://www.statuspage.io/
  baseURL: https:///
  tags: StatusPage.io
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/statuspage-io/master/_listings/statuspage-io/openapi.md
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