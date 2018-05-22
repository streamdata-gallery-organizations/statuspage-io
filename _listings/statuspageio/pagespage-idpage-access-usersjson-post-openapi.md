---
swagger: "2.0"
x-collection-name: StatusPage.io
x-complete: 0
info:
  title: StatusPage.io Create a user who can view your status page
  version: 1.0.0
  description: Create a user who can view your status page
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pages/[page_id].json:
    get:
      summary: Get your page profile
      description: Get your page profile
      operationId: get-your-page-profile
      x-api-path-slug: pagespage-idjson-get
      responses:
        200:
          description: OK
      tags:
      - Pages
    patch:
      summary: Update your page profile
      description: Update your page profile
      operationId: update-your-page-profile
      x-api-path-slug: pagespage-idjson-patch
      parameters:
      - in: query
        name: basic layout only, 170x45 or 340x90 is best
        type: string
      - in: query
        name: page[allow_email_subscribers]
        description: allow users to subscribe for email updates (t or f)
        type: string
      - in: query
        name: page[allow_incident_subscribers]
        description: allow users to subscribe to a single incident (t or f)
        type: string
      - in: query
        name: page[allow_page_subscribers]
        description: allow users to auto
        type: string
      - in: query
        name: page[allow_sms_subscribers]
        description: allow users to subscribe for sms updates (t or f)
        type: string
      - in: query
        name: page[city]
        description: city in which your page is headquartered
        type: string
      - in: query
        name: page[country]
        description: country in which your page is headquartered
        type: string
      - in: query
        name: page[css_body_background_color]
        description: custom css color for your status page body background
        type: string
      - in: query
        name: page[css_font_color]
        description: custom css color for your status page font
        type: string
      - in: query
        name: page[css_greens]
        description: custom css color for your status page greens
        type: string
      - in: query
        name: page[css_light_font_color]
        description: custom css color for your status page light font
        type: string
      - in: query
        name: page[css_oranges]
        description: custom css color for your status page oranges
        type: string
      - in: query
        name: page[css_reds]
        description: custom css color for your status page reds
        type: string
      - in: query
        name: page[css_yellows]
        description: custom css color for your status page yellows
        type: string
      - in: query
        name: page[domain]
        description: CNAME alias for your status page (point DNS record to hosted
        type: string
      - in: query
        name: page[hero_cover_url]
        description: url of a hero cover image to be placed on your status page
        type: string
      - in: query
        name: page[layout]
        description: which layout format to use for your status page
        type: string
      - in: query
        name: page[name]
        description: name of your page to be displayed
        type: string
      - in: query
        name: page[notifications_from_email]
        description: if users reply to the incident notifications we send
        type: string
      - in: query
        name: page[state]
        description: state in which your page is headquartered
        type: string
      - in: query
        name: page[subdomain]
        description: subdomain at which to access your status page (your_subdomain
        type: string
      - in: query
        name: page[time_zone]
        description: time zone to use for your status page display (must be a rails
          time zone)
        type: string
      - in: query
        name: page[transactional_logo_url]
        description: url of a transactional logo to be placed on your status page
        type: string
      - in: query
        name: page[url]
        description: the website of your page
        type: string
      - in: query
        name: premium layout only, 850x315 or 1700x630 is best
        type: string
      responses:
        200:
          description: OK
      tags:
      - Pages
  /pages/[page_id]/components.json:
    get:
      summary: Get a list of all components
      description: Get a list of all components
      operationId: get-a-list-of-all-components
      x-api-path-slug: pagespage-idcomponentsjson-get
      responses:
        200:
          description: OK
      tags:
      - Components
    post:
      summary: Create a component
      description: Create a component
      operationId: create-a-component
      x-api-path-slug: pagespage-idcomponentsjson-post
      parameters:
      - in: query
        name: component[description]
        description: The description of the component
        type: string
      - in: query
        name: component[group_id]
        description: The id of the parent component (optional, only 1 level of nesting)
        type: string
      - in: query
        name: component[name]
        description: The name of the component
        type: string
      responses:
        200:
          description: OK
      tags:
      - Components
  /pages/[page_id]/components/[component_id].json:
    patch:
      summary: Update a component
      description: Update a component
      operationId: update-a-component
      x-api-path-slug: pagespage-idcomponentscomponent-idjson-patch
      parameters:
      - in: query
        name: component[description]
        description: The description of the component
        type: string
      - in: query
        name: component[name]
        description: The name of the component
        type: string
      - in: query
        name: component[status]
        description: The status, one of operational|degraded_performance|partial_outage|major_outage
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Group
    delete:
      summary: Delete a component
      description: Delete a component
      operationId: delete-a-component
      x-api-path-slug: pagespage-idcomponentscomponent-idjson-delete
      responses:
        200:
          description: OK
      tags:
      - Components
  /pages/[page_id]/incidents.json:
    get:
      summary: Get a list of all incidents
      description: Get a list of all incidents
      operationId: get-a-list-of-all-incidents
      x-api-path-slug: pagespage-idincidentsjson-get
      responses:
        200:
          description: OK
      tags:
      - Incidents
    post:
      summary: Create a realtime incident
      description: Create a realtime incident
      operationId: create-a-realtime-incident
      x-api-path-slug: pagespage-idincidentsjson-post
      parameters:
      - in: query
        name: incident[backfilled]
        description: Must be set to t
        type: string
      - in: query
        name: incident[backfill_date]
        description: Date of incident in YYYY
        type: string
      - in: query
        name: incident[component_ids]
        description: List of components whose subscribers should be notified (only
          applicable for pages with component subscriptions enabled)
        type: string
      - in: query
        name: incident[impact_override]
        description: Override calculated impact value, one of none|minor|major|critical
          (optional)
        type: string
      - in: query
        name: incident[message]
        description: The initial message, created as the first incident update (optional)
        type: string
      - in: query
        name: incident[name]
        description: The name of the incident
        type: string
      - in: query
        name: incident[scheduled_auto_completed]
        description: Automatically transition incident to Completed at end (optional,
          t or f, defaults to f)
        type: string
      - in: query
        name: incident[scheduled_auto_in_progress]
        description: Automatically transition incident to In Progress at start (optional,
          t or f, defaults to f)
        type: string
      - in: query
        name: incident[scheduled_for]
        description: time the scheduled maintenance should begin (ISO8601 format)
        type: string
      - in: query
        name: incident[scheduled_remind_prior]
        description: Remind subscribers 60 minutes before scheduled start (optional,
          t or f, defaults to f)
        type: string
      - in: query
        name: incident[scheduled_until]
        description: time the scheduled maintenance should end (ISO8601 format)
        type: string
      - in: query
        name: incident[status]
        description: The status, one of investigating|identified|monitoring|resolved
          (optional, defaults to investigating if left blank)
        type: string
      - in: query
        name: incident[wants_twitter_update]
        description: Post the new incident to twitter (t or f, defaults to f)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Incidents
  /pages/[page_id]/incidents/unresolved.json:
    get:
      summary: Unresolved Only
      description: Unresolved Only
      operationId: unresolved-only
      x-api-path-slug: pagespage-idincidentsunresolvedjson-get
      responses:
        200:
          description: OK
      tags:
      - Incidents
  /pages/[page_id]/incidents/scheduled.json:
    get:
      summary: Scheduled Only
      description: Scheduled Only
      operationId: scheduled-only
      x-api-path-slug: pagespage-idincidentsscheduledjson-get
      responses:
        200:
          description: OK
      tags:
      - Incidents
  /pages/[page_id]/incidents/[incident_id].json:
    patch:
      summary: Update an incident (only applies to realtime and scheduled incidents)
      description: Update an incident (only applies to realtime and scheduled incidents)
      operationId: update-an-incident-only-applies-to-realtime-and-scheduled-incidents
      x-api-path-slug: pagespage-idincidentsincident-idjson-patch
      parameters:
      - in: query
        name: at the same time to avoid two separate incident updates being generated.
        type: string
      - in: query
        name: ENDPOINT
        type: string
      - in: query
        name: incident[component_ids]
        description: List of components whose subscribers should be notified (only
          applicable for pages with component subscriptions enabled)
        type: string
      - in: query
        name: incident[impact_override]
        description: Override calculated impact value, one of none|minor|major|critical
          (optional)
        type: string
      - in: query
        name: incident[message]
        description: The body of the new incident update that will be created (optional)
        type: string
      - in: query
        name: incident[name]
        description: The name of the incident
        type: string
      - in: query
        name: incident[status]
        description: The status, one of investigating|identified|monitoring|resolved
          (if realtime) or scheduled|in_progress|verifying|completed (if scheduled)
        type: string
      - in: query
        name: incident[wants_twitter_update]
        description: Post the new incident update to twitter (t or f, defaults to
          f)
        type: string
      - in: query
        name: MUTABLE
        type: string
      - in: query
        name: PATCH /pages/[page_id]/incidents/[incident_id].json
        type: string
      responses:
        200:
          description: OK
      tags:
      - Incidents
    delete:
      summary: Delete an incident
      description: Delete an incident
      operationId: delete-an-incident
      x-api-path-slug: pagespage-idincidentsincident-idjson-delete
      responses:
        200:
          description: OK
      tags:
      - Incidents
  /pages/[page_id]/incidents/[incident_id]/incident_updates/[incident_update_id].json:
    patch:
      summary: Tune an Incident Update
      description: Tune an Incident Update
      operationId: tune-an-incident-update
      x-api-path-slug: pagespage-idincidentsincident-idincident-updatesincident-update-idjson-patch
      parameters:
      - in: query
        name: incident_update[body]
        description: The body of the incident update (optional)
        type: string
      - in: query
        name: incident_update[display_at]
        description: The timestamp by which to display the incident update (optional)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Incidents
  /pages/[page_id]/subscribers/[subscriber_id].json:
    delete:
      summary: Delete a subscriber
      description: Delete a subscriber
      operationId: delete-a-subscriber
      x-api-path-slug: pagespage-idsubscriberssubscriber-idjson-delete
      responses:
        200:
          description: OK
      tags:
      - Subscribers
  /metrics_providers.json:
    get:
      summary: Get a list of available public metric providers
      description: Get a list of available public metric providers
      operationId: get-a-list-of-available-public-metric-providers
      x-api-path-slug: metrics-providersjson-get
      responses:
        200:
          description: OK
      tags:
      - Metrics
  /pages/[page_id]/metrics_providers.json:
    get:
      summary: Get a list of metric providers linked to your page
      description: Get a list of metric providers linked to your page
      operationId: get-a-list-of-metric-providers-linked-to-your-page
      x-api-path-slug: pagespage-idmetrics-providersjson-get
      responses:
        200:
          description: OK
      tags:
      - Metric Providers
  /pages/[page_id]/metrics_providers/[metrics_provider_id]/metrics.json:
    get:
      summary: Get a list of metrics created for a linked metrics provider
      description: Get a list of metrics created for a linked metrics provider
      operationId: get-a-list-of-metrics-created-for-a-linked-metrics-provider
      x-api-path-slug: pagespage-idmetrics-providersmetrics-provider-idmetricsjson-get
      responses:
        200:
          description: OK
      tags:
      - Metric Providers
    post:
      summary: Create a custom metric
      description: Create a custom metric
      operationId: create-a-custom-metric
      x-api-path-slug: pagespage-idmetrics-providersmetrics-provider-idmetricsjson-post
      responses:
        200:
          description: OK
      tags:
      - Metric Providers
  /pages/[page_id]/metrics/[metric_id]/data.json:
    post:
      summary: Submit data for a custom metric
      description: Submit data for a custom metric
      operationId: submit-data-for-a-custom-metric
      x-api-path-slug: pagespage-idmetricsmetric-iddatajson-post
      responses:
        200:
          description: OK
      tags:
      - Metrics
    delete:
      summary: Delete all data for a custom metric
      description: Delete all data for a custom metric
      operationId: delete-all-data-for-a-custom-metric
      x-api-path-slug: pagespage-idmetricsmetric-iddatajson-delete
      responses:
        200:
          description: OK
      tags:
      - Metrics
  /organizations/[organization_id]/users.json:
    get:
      summary: List users
      description: List users
      operationId: list-users
      x-api-path-slug: organizationsorganization-idusersjson-get
      responses:
        200:
          description: OK
      tags:
      - Organizations
    post:
      summary: Create a user
      description: Create a user
      operationId: create-a-user
      x-api-path-slug: organizationsorganization-idusersjson-post
      responses:
        200:
          description: OK
      tags:
      - Organizations
  /organizations/[organization_id]/users/[user_id].json:
    delete:
      summary: Delete a user
      description: Delete a user
      operationId: delete-a-user
      x-api-path-slug: organizationsorganization-idusersuser-idjson-delete
      responses:
        200:
          description: OK
      tags:
      - Organizations
  /pages/[page_id]/page_access_users.json:
    get:
      summary: Retrieve a list of users
      description: Retrieve a list of users
      operationId: retrieve-a-list-of-users
      x-api-path-slug: pagespage-idpage-access-usersjson-get
      parameters:
      - in: query
        name: email
        description: Filter the returned list of users by email address (users must
          have assigned email addresses)
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
    post:
      summary: Create a user who can view your status page
      description: Create a user who can view your status page
      operationId: create-a-user-who-can-view-your-status-page
      x-api-path-slug: pagespage-idpage-access-usersjson-post
      parameters:
      - in: query
        name: page_access_user[component_ids][]
        description: Array of component ids that the created user will ba able to
          view
        type: string
      - in: query
        name: page_access_user[email]
        description: The email for StatusPage to use to communicate with the user
          (required if StatusPage manages passwords for you)
        type: string
      - in: query
        name: page_access_user[external_login]
        description: A concatenated (and possibly hashed) string of login parameters,
          organized alphabetically by field name
        type: string
      - in: query
        name: page_access_user[metric_ids][]
        description: Array of metric ids that the created user will ba able to view
        type: string
      - in: query
        name: page_access_user[page_access_group_ids][]
        description: Array of PageAccessGroups (identified by code) that the created
          user will be a member of
        type: string
      - in: query
        name: page_access_user[subscribe_to_components]
        description: A value of true will subscribe the user to notifications for
          incidents associated with components they can see, this value is optional
          and defaults to false
        type: string
      responses:
        200:
          description: OK
      tags:
      - Page Access Users
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---