---
swagger: "2.0"
info:
  title: Yammer API
  description: 'TODO: Add Description'
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '{yamURI}/messages/liked_by.json':
    get:
      summary: Get Messages Liked By Current User
      description: Get Messages Liked By Current User
      operationId: Get_Messages Liked by Current User_
      parameters:
      - in: path
        name: yamURI
      responses:
        200:
          description: OK
      tags:
      - messages likedcurrent user
definitions:
  CreateMessagewithOpenGraphObjectJSONcopyRequest:
    properties:
      body:
        description: This is a default description.
        type: get
      og_url:
        description: This is a default description.
        type: get
      og_fetch:
        description: This is a default description.
        type: get
  CreateanActivityRequest:
    properties: []
  Activity:
    properties:
      action:
        description: This is a default description.
        type: get
      private:
        description: This is a default description.
        type: get
      message:
        description: This is a default description.
        type: get
      users:
        description: This is a default description.
        type: get
  Actor:
    properties:
      name:
        description: This is a default description.
        type: get
      email:
        description: This is a default description.
        type: get
  Object4:
    properties:
      url:
        description: This is a default description.
        type: get
      description:
        description: This is a default description.
        type: get
      type:
        description: This is a default description.
        type: get
      title:
        description: This is a default description.
        type: get
      image:
        description: This is a default description.
        type: get
  User:
    properties:
      name:
        description: This is a default description.
        type: get
      email:
        description: This is a default description.
        type: get
  UpdateaUserbyJSONRequest:
    properties:
      email:
        description: This is a default description.
        type: get
      full_name:
        description: This is a default description.
        type: get
      job_title:
        description: This is a default description.
        type: get
      department:
        description: This is a default description.
        type: get
      location:
        description: This is a default description.
        type: get
  CreateaUserbyJSONRequest:
    properties:
      email:
        description: This is a default description.
        type: get
      full_name:
        description: This is a default description.
        type: get
      job_title:
        description: This is a default description.
        type: get
      department:
        description: This is a default description.
        type: get
      location:
        description: This is a default description.
        type: get
  AddaRelationshipdRequest:
    properties:
      superior:
        description: This is a default description.
        type: get
  CreateMessageJSONRequest:
    properties:
      body:
        description: This is a default description.
        type: get
      group_id:
        description: This is a default description.
        type: get
      topic1:
        description: This is a default description.
        type: get
x-collection-name: Yammer
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