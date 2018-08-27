---
name: Dezrez
x-slug: dezrez
description: Cloud based estate agent software , sales & letting agent software, estate
  agent website design and property management software - Dezrez  Services
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
x-kinRank: "7"
x-alexaRank: "385559"
tags: Appointments
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apis.md
specificationVersion: "0.14"
apis:
- name: Dezrez.Rezi.Client.Api - Return the Groups with appointments between a given
    date range, ordered by appointments Count
  x-api-slug: apigroupupdateprimarygroupmember-put
  description: Return the groups with appointments between a given date range, ordered
    by appointments count.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apigroupupdateprimarygroupmember-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Endpoint to complete the multi viewing container
    once individual appointments have been booked.
  x-api-slug: apiviewingiddelete-delete
  description: Endpoint to complete the multi viewing container once individual appointments
    have been booked..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingiddelete-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Get an appointment by its id.
  x-api-slug: apiappointmentid-get
  description: Get an appointment by its id..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentid-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Get details of a calculated appointment using it's
    id and date.
  x-api-slug: apiappointmentiddatedate-get
  description: Get details of a calculated appointment using it's id and date..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentiddatedate-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Delete an appointment by id if it exists.
  x-api-slug: apiappointmentdeleteid-put
  description: Delete an appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentdeleteid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel an appointment by id if it exists.
  x-api-slug: apiappointmentcancelid-put
  description: Cancel an appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentcancelid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel calculated appointment by id and datetime,
    if it exists.
  x-api-slug: apiappointmentcanceliddatedate-put
  description: Cancel calculated appointment by id and datetime, if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentcanceliddatedate-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Save or update an appointment.
  x-api-slug: apiappointmentsaveappointment-put
  description: Save or update an appointment..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentsaveappointment-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Auto-picks attendees and the next available appointment
    slot given the parameters in the request.
  x-api-slug: apiappointmentsuggest-post
  description: Auto-picks attendees and the next available appointment slot given
    the parameters in the request..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentsuggest-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a correspondence confirming the booking
    of a valuation appointment.  Uses default values where possible.
  x-api-slug: apidocumentgenerationconfirmvaluation-post
  description: Generates a correspondence confirming the booking of a valuation appointment.  uses
    default values where possible..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationconfirmvaluation-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a correspondence confirming the result
    of a valuation appointment.  Uses default values where possible.
  x-api-slug: apidocumentgenerationvaluationresult-post
  description: Generates a correspondence confirming the result of a valuation appointment.  uses
    default values where possible..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationvaluationresult-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a EPC Appointment letter correspondence
  x-api-slug: apidocumentgenerationrescheduleepcappointment-post
  description: Generates a epc appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationrescheduleepcappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a cancel an epc appointment letter correspondence
  x-api-slug: apidocumentgenerationcancelepcappointment-post
  description: Generates a cancel an epc appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationcancelepcappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a confirm an epc appointment letter correspondence
  x-api-slug: apidocumentgenerationconfirmepcappointment-post
  description: Generates a confirm an epc appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationconfirmepcappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a confirm general appointment letter correspondence
  x-api-slug: apidocumentgenerationconfirmgeneralappointment-post
  description: Generates a confirm general appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationconfirmgeneralappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a cancel general appointment letter correspondence
  x-api-slug: apidocumentgenerationcancelgeneralappointment-post
  description: Generates a cancel general appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationcancelgeneralappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a reschedule general appointment letter
    correspondence
  x-api-slug: apidocumentgenerationreschedulegeneralappointment-post
  description: Generates a reschedule general appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationreschedulegeneralappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Gets all tasks for a particular event / appointment
  x-api-slug: apitodoeventtaskeventid-get
  description: Gets all tasks for a particular event / appointment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apitodoeventtaskeventid-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a valuation appointment by id if it exists.
  x-api-slug: apivaluationid-delete
  description: Cancel a valuation appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apivaluationid-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Book multiple viewings appointment
  x-api-slug: apiviewingbookmultiviewing-post
  description: Book multiple viewings appointment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingbookmultiviewing-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Set approval status of viewing slot on multi viewing
    appointment
  x-api-slug: apiviewingidrecordslotapprovalviewingslotid-put
  description: Set approval status of viewing slot on multi viewing appointment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingidrecordslotapprovalviewingslotid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a viewing appointment by id if it exists.
  x-api-slug: apiviewingid-delete
  description: Cancel a viewing appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingid-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Get an appointment by its id.
  x-api-slug: apiappointmentid-get
  description: Get an appointment by its id..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentid-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Get details of a calculated appointment using it's
    id and date.
  x-api-slug: apiappointmentiddatedate-get
  description: Get details of a calculated appointment using it's id and date..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentiddatedate-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Delete an appointment by id if it exists.
  x-api-slug: apiappointmentdeleteid-put
  description: Delete an appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentdeleteid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel an appointment by id if it exists.
  x-api-slug: apiappointmentcancelid-put
  description: Cancel an appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentcancelid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel calculated appointment by id and datetime,
    if it exists.
  x-api-slug: apiappointmentcanceliddatedate-put
  description: Cancel calculated appointment by id and datetime, if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentcanceliddatedate-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Save or update an appointment.
  x-api-slug: apiappointmentsaveappointment-put
  description: Save or update an appointment..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentsaveappointment-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Auto-picks attendees and the next available appointment
    slot given the parameters in the request.
  x-api-slug: apiappointmentsuggest-post
  description: Auto-picks attendees and the next available appointment slot given
    the parameters in the request..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentsuggest-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a correspondence confirming the booking
    of a valuation appointment.  Uses default values where possible.
  x-api-slug: apidocumentgenerationconfirmvaluation-post
  description: Generates a correspondence confirming the booking of a valuation appointment.  uses
    default values where possible..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationconfirmvaluation-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a correspondence confirming the result
    of a valuation appointment.  Uses default values where possible.
  x-api-slug: apidocumentgenerationvaluationresult-post
  description: Generates a correspondence confirming the result of a valuation appointment.  uses
    default values where possible..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationvaluationresult-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a EPC Appointment letter correspondence
  x-api-slug: apidocumentgenerationrescheduleepcappointment-post
  description: Generates a epc appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationrescheduleepcappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a cancel an epc appointment letter correspondence
  x-api-slug: apidocumentgenerationcancelepcappointment-post
  description: Generates a cancel an epc appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationcancelepcappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a confirm an epc appointment letter correspondence
  x-api-slug: apidocumentgenerationconfirmepcappointment-post
  description: Generates a confirm an epc appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationconfirmepcappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a confirm general appointment letter correspondence
  x-api-slug: apidocumentgenerationconfirmgeneralappointment-post
  description: Generates a confirm general appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationconfirmgeneralappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a cancel general appointment letter correspondence
  x-api-slug: apidocumentgenerationcancelgeneralappointment-post
  description: Generates a cancel general appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationcancelgeneralappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a reschedule general appointment letter
    correspondence
  x-api-slug: apidocumentgenerationreschedulegeneralappointment-post
  description: Generates a reschedule general appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationreschedulegeneralappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Gets all tasks for a particular event / appointment
  x-api-slug: apitodoeventtaskeventid-get
  description: Gets all tasks for a particular event / appointment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apitodoeventtaskeventid-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a valuation appointment by id if it exists.
  x-api-slug: apivaluationid-delete
  description: Cancel a valuation appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apivaluationid-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Book multiple viewings appointment
  x-api-slug: apiviewingbookmultiviewing-post
  description: Book multiple viewings appointment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingbookmultiviewing-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Set approval status of viewing slot on multi viewing
    appointment
  x-api-slug: apiviewingidrecordslotapprovalviewingslotid-put
  description: Set approval status of viewing slot on multi viewing appointment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingidrecordslotapprovalviewingslotid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a viewing appointment by id if it exists.
  x-api-slug: apiviewingid-delete
  description: Cancel a viewing appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingid-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a viewing appointment by id if it exists.
  x-api-slug: apiviewingid-delete
  description: Cancel a viewing appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingid-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Set approval status of viewing slot on multi viewing
    appointment
  x-api-slug: apiviewingidrecordslotapprovalviewingslotid-put
  description: Set approval status of viewing slot on multi viewing appointment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingidrecordslotapprovalviewingslotid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Book multiple viewings appointment
  x-api-slug: apiviewingbookmultiviewing-post
  description: Book multiple viewings appointment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiviewingbookmultiviewing-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel a valuation appointment by id if it exists.
  x-api-slug: apivaluationid-delete
  description: Cancel a valuation appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apivaluationid-delete-openapi.md
- name: Dezrez.Rezi.Client.Api - Gets all tasks for a particular event / appointment
  x-api-slug: apitodoeventtaskeventid-get
  description: Gets all tasks for a particular event / appointment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apitodoeventtaskeventid-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a reschedule general appointment letter
    correspondence
  x-api-slug: apidocumentgenerationreschedulegeneralappointment-post
  description: Generates a reschedule general appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationreschedulegeneralappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a cancel general appointment letter correspondence
  x-api-slug: apidocumentgenerationcancelgeneralappointment-post
  description: Generates a cancel general appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationcancelgeneralappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a confirm general appointment letter correspondence
  x-api-slug: apidocumentgenerationconfirmgeneralappointment-post
  description: Generates a confirm general appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationconfirmgeneralappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a confirm an epc appointment letter correspondence
  x-api-slug: apidocumentgenerationconfirmepcappointment-post
  description: Generates a confirm an epc appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationconfirmepcappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a cancel an epc appointment letter correspondence
  x-api-slug: apidocumentgenerationcancelepcappointment-post
  description: Generates a cancel an epc appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationcancelepcappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a EPC Appointment letter correspondence
  x-api-slug: apidocumentgenerationrescheduleepcappointment-post
  description: Generates a epc appointment letter correspondence.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationrescheduleepcappointment-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a correspondence confirming the result
    of a valuation appointment.  Uses default values where possible.
  x-api-slug: apidocumentgenerationvaluationresult-post
  description: Generates a correspondence confirming the result of a valuation appointment.  uses
    default values where possible..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationvaluationresult-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Generates a correspondence confirming the booking
    of a valuation appointment.  Uses default values where possible.
  x-api-slug: apidocumentgenerationconfirmvaluation-post
  description: Generates a correspondence confirming the booking of a valuation appointment.  uses
    default values where possible..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apidocumentgenerationconfirmvaluation-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Auto-picks attendees and the next available appointment
    slot given the parameters in the request.
  x-api-slug: apiappointmentsuggest-post
  description: Auto-picks attendees and the next available appointment slot given
    the parameters in the request..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentsuggest-post-openapi.md
- name: Dezrez.Rezi.Client.Api - Save or update an appointment.
  x-api-slug: apiappointmentsaveappointment-put
  description: Save or update an appointment..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentsaveappointment-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel calculated appointment by id and datetime,
    if it exists.
  x-api-slug: apiappointmentcanceliddatedate-put
  description: Cancel calculated appointment by id and datetime, if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentcanceliddatedate-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Cancel an appointment by id if it exists.
  x-api-slug: apiappointmentcancelid-put
  description: Cancel an appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentcancelid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Delete an appointment by id if it exists.
  x-api-slug: apiappointmentdeleteid-put
  description: Delete an appointment by id if it exists..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentdeleteid-put-openapi.md
- name: Dezrez.Rezi.Client.Api - Get details of a calculated appointment using it's
    id and date.
  x-api-slug: apiappointmentiddatedate-get
  description: Get details of a calculated appointment using it's id and date..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentiddatedate-get-openapi.md
- name: Dezrez.Rezi.Client.Api - Get an appointment by its id.
  x-api-slug: apiappointmentid-get
  description: Get an appointment by its id..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28888-www-dezrez-com.jpg
  humanURL: https://www.dezrez.com
  baseURL: https://api.dezrez.com//
  tags: SaaS, Technology, Real Estate, Properties, Service API, Relative Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/appointments/master/_listings/dezrez/apiappointmentid-get-openapi.md
x-common:
- type: x-github
  url: https://github.com/dezrez
- type: x-openapi
  url: https://api.dezrez.com:443/swagger/docs/v1
- type: x-api-gallery
  url: http://datumbox.api.gallery.streamdata.io
- type: x-api-stack
  url: http://dezrez.stack.network
- type: x-documentation
  url: https://api.dezrez.com/swagger/ui/index#!/AccountingExport
- type: x-support
  url: https://www.dezrez.com/uk/estate-agency-software-support
- type: x-twitter
  url: https://twitter.com/dezrezsoftware
- type: x-website
  url: https://www.dezrez.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---