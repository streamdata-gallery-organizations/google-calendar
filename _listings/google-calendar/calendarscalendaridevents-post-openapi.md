---
swagger: "2.0"
x-collection-name: Google Calendar
x-complete: 0
info:
  title: Google Calendar Create Event
  description: Creates an event.
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
    patch:
      summary: Update Calendar ACL
      description: Updates an access control rule. This method supports patch semantics.
      operationId: calendar.acl.patch
      x-api-path-slug: calendarscalendaridaclruleid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
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
    put:
      summary: Update Calendar ACL
      description: Updates an access control rule.
      operationId: calendar.acl.update
      x-api-path-slug: calendarscalendaridaclruleid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
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
  /calendars/{calendarId}/clear:
    post:
      summary: Clear Primary Calendar
      description: Clears a primary calendar. This operation deletes all events associated
        with the primary calendar of an account.
      operationId: calendar.calendars.clear
      x-api-path-slug: calendarscalendaridclear-post
      parameters:
      - in: path
        name: calendarId
        description: Calendar identifier
      responses:
        200:
          description: OK
      tags:
      - Calendar
  /calendars/{calendarId}/events:
    get:
      summary: Get Events
      description: Returns events on the specified calendar.
      operationId: calendar.events.list
      x-api-path-slug: calendarscalendaridevents-get
      parameters:
      - in: query
        name: alwaysIncludeEmail
        description: Whether to always include a value in the email field for the
          organizer, creator and attendees, even if no real email is available (i
      - in: path
        name: calendarId
        description: Calendar identifier
      - in: query
        name: iCalUID
        description: Specifies event ID in the iCalendar format to be included in
          the response
      - in: query
        name: maxAttendees
        description: The maximum number of attendees to include in the response
      - in: query
        name: maxResults
        description: Maximum number of events returned on one result page
      - in: query
        name: orderBy
        description: The order of the events returned in the result
      - in: query
        name: pageToken
        description: Token specifying which result page to return
      - in: query
        name: privateExtendedProperty
        description: Extended properties constraint specified as propertyName=value
      - in: query
        name: q
        description: Free text search terms to find events that match these terms
          in any field, except for extended properties
      - in: query
        name: sharedExtendedProperty
        description: Extended properties constraint specified as propertyName=value
      - in: query
        name: showDeleted
        description: Whether to include deleted events (with status equals cancelled)
          in the result
      - in: query
        name: showHiddenInvitations
        description: Whether to include hidden invitations in the result
      - in: query
        name: singleEvents
        description: Whether to expand recurring events into instances and only return
          single one-off events and instances of recurring events, but not the underlying
          recurring events themselves
      - in: query
        name: syncToken
        description: Token obtained from the nextSyncToken field returned on the last
          page of results from the previous list request
      - in: query
        name: timeMax
        description: Upper bound (exclusive) for an events start time to filter by
      - in: query
        name: timeMin
        description: Lower bound (inclusive) for an events end time to filter by
      - in: query
        name: timeZone
        description: Time zone used in the response
      - in: query
        name: updatedMin
        description: Lower bound for an events last modification time (as a RFC3339
          timestamp) to filter by
      responses:
        200:
          description: OK
      tags:
      - Event
    post:
      summary: Create Event
      description: Creates an event.
      operationId: calendar.events.insert
      x-api-path-slug: calendarscalendaridevents-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: calendarId
        description: Calendar identifier
      - in: query
        name: maxAttendees
        description: The maximum number of attendees to include in the response
      - in: query
        name: sendNotifications
        description: Whether to send notifications about the creation of the new event
      - in: query
        name: supportsAttachments
        description: Whether API client performing operation supports event attachments
      responses:
        200:
          description: OK
      tags:
      - Event
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