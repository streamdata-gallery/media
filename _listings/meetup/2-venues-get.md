---
swagger: "2.0"
info:
  title: Meetup
  description: 'The Meetup API provides simple RESTful HTTP and streaming interfaces
    for exploring and interacting Meetup platform from your own apps. The API is a
    set of core methods and a common request format. These are combined to form a
    URL that returns the information you want. '
  version: 1.0.0
host: api.meetup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /2/venues:
    get:
      summary: Venues
      description: Search for Meetup venues by one of your groups, events, or venue
        identifiers
      operationId: venues
      parameters:
      - in: query
        name: '*event_id'
        description: multiple ids may be separated with commas
        type: string
      - in: query
        name: '*group_id'
        description: multiple ids may be separated with commas
        type: string
      - in: query
        name: '*group_urlname'
        description: path to group from meetup
        type: string
      - in: query
        name: '*venue_id'
        description: multiple ids may be separated with commas
        type: string
      - in: query
        name: fields
        description: Request that additional fields (separated by commas) be included
          in the output
        type: string
      responses:
        200:
          description: OK
      tags:
      - events
      - venues
definitions: []
x-collection-name: Meetup
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