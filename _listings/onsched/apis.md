---
name: OnSched
x-slug: onsched
description: Build secure and scalable custom apps for Online Booking. Our flexible
  API provides many options for availability and booking. OnSched is an API first
  booking software that allows you to bring your design to life by creating your own
  booking flow. Using our robust API you can customize the interaction between your
  consumers and vendors while we do all the leg work behind the scenes. Want to offer
  online booking to your vendors? Ask about our white labelling solutions and rebrand
  our software as your own.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
x-kinRank: "7"
x-alexaRank: ""
tags: Appointments
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/apis.md
specificationVersion: "0.14"
apis:
- name: OnSched API - Returns a list of appointments.
  x-api-slug: consumerv1appointments-get
  description: "The results are returned in pages. Use the offset and limit parameters
    to control the page start and size. Default offset is 0, and limit is 20.\r\nUse
    the other query parameters to optionally filter the results list."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointments-get-openapi.md
- name: OnSched API - Returns an appointment object
  x-api-slug: consumerv1appointments-post
  description: "This end point creates a new appointment in an Initial \"IN\" status.
    \r\n\r\nA valid serviceId is required. Use GET consumer/v1/services to retrieve
    a list of your services.\r\n\r\nA valid resourceId is required if your calendar
    is a resource based calendar. Use consumer/v1/resources to retrieve a list of
    your resources.\r\n\r\nStartDateTime and EndDateTime are required. Use the ISO
    8601 format for DateTime Timezone. e.g. 2016-10-30T9:00:00-5:00"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointments-post-openapi.md
- name: OnSched API - Returns an appointment object.
  x-api-slug: consumerv1appointmentsid-get
  description: "The result returned is a single appointment object. A valid id is
    required to find the appointment. \r\n\r\nFind appointment id's using the GET
    consumer/v1/appointments end point."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointmentsid-get-openapi.md
- name: OnSched API - Returns an appointment object
  x-api-slug: consumerv1appointmentsid-delete
  description: "This end point deletes a booking. Only appointments in a \"IN\" initial
    status can be deleted.\r\nPast dated appointments cannot be cancelled.\r\n\r\nA
    valid appointment id is required. Use the appointmentId returned from GET /consumer/v1/appointments"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointmentsid-delete-openapi.md
- name: OnSched API - Returns an appointment object
  x-api-slug: consumerv1appointmentsidbook-put
  description: "This end point completes a new booking. Only appointments in the \"IN\"
    initial status can be booked.\r\nby saving all the relevant details of the booking.\r\n\r\nA
    valid appointment id is required. Use the appointmentId returned from POST /consumer/v1/appointments\r\n\r\nTo
    update appointment custom field values, use the GET /consumer/v1/appointments/customfields
    information\r\nto understand your definitions of custom fields and what key and
    values to update."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointmentsidbook-put-openapi.md
- name: OnSched API - Returns an appointment object
  x-api-slug: consumerv1appointmentsidcancel-put
  description: "This end point cancels a booking or reservation. Only appointments
    in a \"BK\" booked, or \"RS\" reserved status can be cancelled.\r\nPast dated
    appointments cannot be cancelled.\r\n\r\nA valid appointment id is required. Use
    the appointmentId returned from POST /consumer/v1/appointments"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointmentsidcancel-put-openapi.md
- name: OnSched API - Returns an appointment object
  x-api-slug: consumerv1appointmentsidreschedule-put
  description: "This end point reschedules a booking. Only appointments in a \"BK\"
    booked status can be rescheduled.\r\nPast dated appointments cannot be cancelled.\r\n\r\nA
    valid appointment id is required. Use the appointmentId returned from GET /consumer/v1/appointments.\r\n\r\nThe
    serviceId and resourceId are optional. If you want your users to change the resource
    or service on a reschedule\r\nyou will have to use the regular availability endpoint
    rather than the reschedule availability end point.\r\n\r\nUse the GET /consumer/v1/availability/{id}/reschedule
    endpoint to display a list of available times\r\nfor the end user to choose from
    to reschedule the original appointment."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointmentsidreschedule-put-openapi.md
- name: OnSched API - Returns a list of appointment custom field definitions
  x-api-slug: consumerv1appointmentscustomfields-get
  description: "This end point returns your Appointment custom field definitions.\r\n\r\nAppointment
    custom fields are different than Customer custom fields. Appointment custom fields
    are\r\nstored with each appointment. They are used when the information collected
    during the booking is specific\r\nto a particular visit.\r\n\r\nUse the field,
    and type to determine how to update field values\r\nin PUT /consumer/v1/appointments/{id}/book"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointmentscustomfields-get-openapi.md
- name: 'OnSched API - '
  x-api-slug: consumerv1appointmentsbookingfields-get
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1appointmentsbookingfields-get-openapi.md
- name: OnSched API - Returns a list of available times.
  x-api-slug: consumerv1availabilityappointmentidreschedule-get
  description: "This end point is used to find availability for the purpose of rescheduling
    an appointment.\r\nAvailability defaults to the serviceId, resourceId and timezone
    from the original appointment.\r\nAfter choosing from the availability, you can
    call the appointment reschedule endpoint."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1availabilityappointmentidreschedule-get-openapi.md
- name: OnSched API - Returns a list of available times.
  x-api-slug: consumerv1availabilityappointmentidreschedule-get
  description: "This end point is used to find availability for the purpose of rescheduling
    an appointment.\r\nAvailability defaults to the serviceId, resourceId and timezone
    from the original appointment.\r\nAfter choosing from the availability, you can
    call the appointment reschedule endpoint."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1availabilityappointmentidreschedule-get-openapi.md
- name: OnSched API - Returns a list of available times.
  x-api-slug: consumerv1availabilityappointmentidreschedule-get
  description: "This end point is used to find availability for the purpose of rescheduling
    an appointment.\r\nAvailability defaults to the serviceId, resourceId and timezone
    from the original appointment.\r\nAfter choosing from the availability, you can
    call the appointment reschedule endpoint."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/onsched-logo.png
  humanURL: http://www.onsched.com
  baseURL: https://api.onsched.com//
  tags: API Provider, Bookings, Profiles, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/onsched/consumerv1availabilityappointmentidreschedule-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://onenote.api.gallery.streamdata.io
- type: x-api-stack
  url: http://onsched.stack.network
- type: x-documentation
  url: https://www.onsched.com/api/docs/
- type: x-pricing
  url: https://www.onsched.com/index.html#self-service
- type: x-website
  url: http://www.onsched.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---