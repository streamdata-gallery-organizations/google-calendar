---
swagger: "2.0"
x-collection-name: Google Calendar
x-complete: 0
info:
  title: Google Calendar Get Calendar ACL
  description: Returns an access control rule.
  contact:
    name: Google
    url: https://google.com
  version: v3/
host: www.googleapis.com
basePath: /calendar/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /calendars:
    post:
      summary: Create Calendar
      description: Creates a secondary calendar.
      operationId: calendar.calendars.insert
      x-api-path-slug: calendars-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /calendars/{calendarId}:
    delete:
      summary: CreaDeletete Calendar
      description: Deletes a secondary calendar. Use calendars.clear for clearing
        all events on primary calendars.
      operationId: calendar.calendars.delete
      x-api-path-slug: calendarscalendarid-delete
      parameters:
      - in: path
        name: calendarId
        description: Calendar identifier
      responses:
        200:
          description: OK
      tags:
      - Calendar
    get:
      summary: Get Calendar
      description: Returns metadata for a calendar.
      operationId: calendar.calendars.get
      x-api-path-slug: calendarscalendarid-get
      parameters:
      - in: path
        name: calendarId
        description: Calendar identifier
      responses:
        200:
          description: OK
      tags:
      - Calendar
    patch:
      summary: Update Calendar
      description: Updates metadata for a calendar. This method supports patch semantics.
      operationId: calendar.calendars.patch
      x-api-path-slug: calendarscalendarid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: calendarId
        description: Calendar identifier
      responses:
        200:
          description: OK
      tags:
      - Calendar
    put:
      summary: Update Calendar
      description: Updates metadata for a calendar.
      operationId: calendar.calendars.update
      x-api-path-slug: calendarscalendarid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: calendarId
        description: Calendar identifier
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /calendars/{calendarId}/acl:
    get:
      summary: Get Calendar ACL
      description: Returns the rules in the access control list for the calendar.
      operationId: calendar.acl.list
      x-api-path-slug: calendarscalendaridacl-get
      parameters:
      - in: path
        name: calendarId
        description: Calendar identifier
      - in: query
        name: maxResults
        description: Maximum number of entries returned on one result page
      - in: query
        name: pageToken
        description: Token specifying which result page to return
      - in: query
        name: showDeleted
        description: Whether to include deleted ACLs in the result
      - in: query
        name: syncToken
        description: Token obtained from the nextSyncToken field returned on the last
          page of results from the previous list request
      responses:
        200:
          description: OK
      tags:
      - Calendar ACL
    post:
      summary: Create Calendar ACL
      description: Creates an access control rule.
      operationId: calendar.acl.insert
      x-api-path-slug: calendarscalendaridacl-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: calendarId
        description: Calendar identifier
      responses:
        200:
          description: OK
      tags:
      - Calendar ACL
  /calendars/{calendarId}/acl/watch:
    post:
      summary: Watch Calendar ACL
      description: Watch for changes to ACL resources.
      operationId: calendar.acl.watch
      x-api-path-slug: calendarscalendaridaclwatch-post
      parameters:
      - in: path
        name: calendarId
        description: Calendar identifier
      - in: query
        name: maxResults
        description: Maximum number of entries returned on one result page
      - in: query
        name: pageToken
        description: Token specifying which result page to return
      - in: body
        name: resource
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: showDeleted
        description: Whether to include deleted ACLs in the result
      - in: query
        name: syncToken
        description: Token obtained from the nextSyncToken field returned on the last
          page of results from the previous list request
      responses:
        200:
          description: OK
      tags:
      - Calendar ACL
  /calendars/{calendarId}/acl/{ruleId}:
    delete:
      summary: Delete Calendar ACL
      description: Deletes an access control rule.
      operationId: calendar.acl.delete
      x-api-path-slug: calendarscalendaridaclruleid-delete
      parameters:
      - in: path
        name: calendarId
        description: Calendar identifier
      - in: path
        name: ruleId
        description: ACL rule identifier
      responses:
        200:
          description: OK
      tags:
      - Calendar ACL
    get:
      summary: Get Calendar ACL
      description: Returns an access control rule.
      operationId: calendar.acl.get
      x-api-path-slug: calendarscalendaridaclruleid-get
      parameters:
      - in: path
        name: calendarId
        description: Calendar identifier
      - in: path
        name: ruleId
        description: ACL rule identifier
      responses:
        200:
          description: OK
      tags:
      - Calendar ACL
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