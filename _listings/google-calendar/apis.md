---
name: Google Calendar
x-slug: google-calendar
description: The Calendar API lets you display, create and modify calendar events
  as well as work with many other calendar-related objects, such as calendars or access
  controls. This document describes how to use RESTful calls and client libraries
  for various programming languages (Java, PHP, .NET, JavaScript, NodeJs, Ruby, Python,
  Go, Android, iOS).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Calendar
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/apis.md
specificationVersion: "0.14"
apis:
- name: Google Calendar - Create Calendar
  x-api-slug: calendars-post
  description: Creates a secondary calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendars-post-openapi.md
- name: Google Calendar - CreaDeletete Calendar
  x-api-slug: calendarscalendarid-delete
  description: Deletes a secondary calendar. Use calendars.clear for clearing all
    events on primary calendars.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarid-delete-openapi.md
- name: Google Calendar - Get Calendar
  x-api-slug: calendarscalendarid-get
  description: Returns metadata for a calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarid-get-openapi.md
- name: Google Calendar - Update Calendar
  x-api-slug: calendarscalendarid-patch
  description: Updates metadata for a calendar. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarid-patch-openapi.md
- name: Google Calendar - Update Calendar
  x-api-slug: calendarscalendarid-put
  description: Updates metadata for a calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarid-put-openapi.md
- name: Google Calendar - Get Calendar ACL
  x-api-slug: calendarscalendaridacl-get
  description: Returns the rules in the access control list for the calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridacl-get-openapi.md
- name: Google Calendar - Create Calendar ACL
  x-api-slug: calendarscalendaridacl-post
  description: Creates an access control rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridacl-post-openapi.md
- name: Google Calendar - Watch Calendar ACL
  x-api-slug: calendarscalendaridaclwatch-post
  description: Watch for changes to ACL resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridaclwatch-post-openapi.md
- name: Google Calendar - Delete Calendar ACL
  x-api-slug: calendarscalendaridaclruleid-delete
  description: Deletes an access control rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridaclruleid-delete-openapi.md
- name: Google Calendar - Get Calendar ACL
  x-api-slug: calendarscalendaridaclruleid-get
  description: Returns an access control rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridaclruleid-get-openapi.md
- name: Google Calendar - Update Calendar ACL
  x-api-slug: calendarscalendaridaclruleid-patch
  description: Updates an access control rule. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridaclruleid-patch-openapi.md
- name: Google Calendar - Update Calendar ACL
  x-api-slug: calendarscalendaridaclruleid-put
  description: Updates an access control rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridaclruleid-put-openapi.md
- name: Google Calendar - Clear Primary Calendar
  x-api-slug: calendarscalendaridclear-post
  description: Clears a primary calendar. This operation deletes all events associated
    with the primary calendar of an account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridclear-post-openapi.md
- name: Google Calendar - Get Events
  x-api-slug: calendarscalendaridevents-get
  description: Returns events on the specified calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridevents-get-openapi.md
- name: Google Calendar - Create Event
  x-api-slug: calendarscalendaridevents-post
  description: Creates an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendaridevents-post-openapi.md
- name: Google Calendar - Import Event
  x-api-slug: calendarscalendarideventsimport-post
  description: Imports an event. This operation is used to add a private copy of an
    existing event to a calendar.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarideventsimport-post-openapi.md
- name: Google Calendar - Create Event
  x-api-slug: calendarscalendarideventsquickadd-post
  description: Creates an event based on a simple text string.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarideventsquickadd-post-openapi.md
- name: Google Calendar - Watch Event
  x-api-slug: calendarscalendarideventswatch-post
  description: Watch for changes to Events resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarideventswatch-post-openapi.md
- name: Google Calendar - Delete Event
  x-api-slug: calendarscalendarideventseventid-delete
  description: Deletes an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarideventseventid-delete-openapi.md
- name: Google Calendar - Get Event
  x-api-slug: calendarscalendarideventseventid-get
  description: Returns an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarideventseventid-get-openapi.md
- name: Google Calendar - Update Event
  x-api-slug: calendarscalendarideventseventid-patch
  description: Updates an event. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarideventseventid-patch-openapi.md
- name: Google Calendar - Update Event
  x-api-slug: calendarscalendarideventseventid-put
  description: Updates an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarideventseventid-put-openapi.md
- name: Google Calendar - Get Event Instance
  x-api-slug: calendarscalendarideventseventidinstances-get
  description: Returns instances of the specified recurring event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarideventseventidinstances-get-openapi.md
- name: Google Calendar - Move Event
  x-api-slug: calendarscalendarideventseventidmove-post
  description: Moves an event to another calendar, i.e. changes an event's organizer.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/calendarscalendarideventseventidmove-post-openapi.md
- name: Google Calendar - Stop Watching Resource
  x-api-slug: channelsstop-post
  description: Stop watching resources through this channel
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/channelsstop-post-openapi.md
- name: Google Calendar - Get Colors
  x-api-slug: colors-get
  description: Returns the color definitions for calendars and events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/colors-get-openapi.md
- name: Google Calendar - Return Free/Busy Information
  x-api-slug: freebusy-post
  description: Returns free/busy information for a set of calendars.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/freebusy-post-openapi.md
- name: Google Calendar - Return Entries
  x-api-slug: usersmecalendarlist-get
  description: Returns entries on the user's calendar list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmecalendarlist-get-openapi.md
- name: Google Calendar - Add Entry
  x-api-slug: usersmecalendarlist-post
  description: Adds an entry to the user's calendar list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmecalendarlist-post-openapi.md
- name: Google Calendar - Watch Entry
  x-api-slug: usersmecalendarlistwatch-post
  description: Watch for changes to CalendarList resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmecalendarlistwatch-post-openapi.md
- name: Google Calendar - Delete Entry
  x-api-slug: usersmecalendarlistcalendarid-delete
  description: Deletes an entry on the user's calendar list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmecalendarlistcalendarid-delete-openapi.md
- name: Google Calendar - Get Entry
  x-api-slug: usersmecalendarlistcalendarid-get
  description: Returns an entry on the user's calendar list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmecalendarlistcalendarid-get-openapi.md
- name: Google Calendar - Update Entry
  x-api-slug: usersmecalendarlistcalendarid-patch
  description: Updates an entry on the user's calendar list. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmecalendarlistcalendarid-patch-openapi.md
- name: Google Calendar - Update Entry
  x-api-slug: usersmecalendarlistcalendarid-put
  description: Updates an entry on the user's calendar list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmecalendarlistcalendarid-put-openapi.md
- name: Google Calendar - Get Settings
  x-api-slug: usersmesettings-get
  description: Returns all user settings for the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmesettings-get-openapi.md
- name: Google Calendar - Watch Settings
  x-api-slug: usersmesettingswatch-post
  description: Watch for changes to Settings resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmesettingswatch-post-openapi.md
- name: Google Calendar - Get Setting
  x-api-slug: usersmesettingssetting-get
  description: Returns a single user setting.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-calendar-icon-66527.png
  humanURL: https://developers.google.com/google-apps/calendar/
  baseURL: https://www.googleapis.com//calendar/v3
  tags: Calendar, Google APIs, Stack Network, Stack, Productivity, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-calendar/master/_listings/google-calendar/usersmesettingssetting-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.books.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.calendar.stack.network
- type: x-code
  url: https://developers.google.com/google-apps/calendar/downloads
- type: x-documentation
  url: https://developers.google.com/google-apps/calendar/v3/reference/
- type: x-website
  url: https://developers.google.com/google-apps/calendar/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---