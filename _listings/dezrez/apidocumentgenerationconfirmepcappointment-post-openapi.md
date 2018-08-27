---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Generates a confirm an epc appointment letter correspondence
  version: 1.0.0
  description: Generates a confirm an epc appointment letter correspondence.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/group/updateprimarygroupmember:
    put:
      summary: Return the Groups with appointments between a given date range, ordered
        by appointments Count
      description: Return the groups with appointments between a given date range,
        ordered by appointments count.
      operationId: Group_UpdatePrimaryGroupMemberByfilter
      x-api-path-slug: apigroupupdateprimarygroupmember-put
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Return
      - Groups
      - Appointments
      - Between
      - Given
      - Date
      - Range
      - ""
      - Ordered
      - By
      - Appointments
      - Count
  /api/viewing/{id}/delete:
    delete:
      summary: Endpoint to complete the multi viewing container once individual appointments
        have been booked.
      description: Endpoint to complete the multi viewing container once individual
        appointments have been booked..
      operationId: Viewing_CompleteMultiViewingBookingByid
      x-api-path-slug: apiviewingiddelete-delete
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Endpoint
      - To
      - Complete
      - Multi
      - Viewing
      - Container
      - Once
      - Individual
      - Appointments
      - Have
      - Been
      - Booked
  /api/appointment/{id}:
    get:
      summary: Get an appointment by its id.
      description: Get an appointment by its id..
      operationId: Appointment_GetByid
      x-api-path-slug: apiappointmentid-get
      parameters:
      - in: path
        name: id
        description: The id of the appointment to get
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Appointment
      - By
      - Its
      - Id
  /api/appointment/{id}/Date/{date}:
    get:
      summary: Get details of a calculated appointment using it's id and date.
      description: Get details of a calculated appointment using it's id and date..
      operationId: Appointment_GetByidBydate
      x-api-path-slug: apiappointmentiddatedate-get
      parameters:
      - in: path
        name: date
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Details
      - Of
      - Calculated
      - Appointment
      - Using
      - Its
      - Id
      - Date
  /api/appointment/delete/{id}:
    put:
      summary: Delete an appointment by id if it exists.
      description: Delete an appointment by id if it exists..
      operationId: Appointment_DeleteByidBydeleteAppointmentDataContract
      x-api-path-slug: apiappointmentdeleteid-put
      parameters:
      - in: body
        name: deleteAppointmentDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: the appointment id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Appointment
      - By
      - Id
      - If
      - It
      - Exists
  /api/appointment/cancel/{id}:
    put:
      summary: Cancel an appointment by id if it exists.
      description: Cancel an appointment by id if it exists..
      operationId: Appointment_CancelByidBycancelAppointmentDataContract
      x-api-path-slug: apiappointmentcancelid-put
      parameters:
      - in: body
        name: cancelAppointmentDataContract
        description: The cancellation details, including reason of cancellation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: the appointment id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Appointment
      - By
      - Id
      - If
      - It
      - Exists
  /api/appointment/cancel/{id}/Date/{date}:
    put:
      summary: Cancel calculated appointment by id and datetime, if it exists.
      description: Cancel calculated appointment by id and datetime, if it exists..
      operationId: Appointment_CancelByidBydateBycancelAppointmentDataContract
      x-api-path-slug: apiappointmentcanceliddatedate-put
      parameters:
      - in: body
        name: cancelAppointmentDataContract
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: date
        description: appointment start date
      - in: path
        name: id
        description: appointment id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Calculated
      - Appointment
      - By
      - Id
      - Datetime
      - ""
      - If
      - It
      - Exists
  /api/appointment/saveappointment:
    put:
      summary: Save or update an appointment.
      description: Save or update an appointment..
      operationId: Appointment_SaveAppointmentByappointment
      x-api-path-slug: apiappointmentsaveappointment-put
      parameters:
      - in: body
        name: appointment
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Save
      - Update
      - Appointment
  /api/appointment/suggest:
    post:
      summary: Auto-picks attendees and the next available appointment slot given
        the parameters in the request.
      description: Auto-picks attendees and the next available appointment slot given
        the parameters in the request..
      operationId: Appointment_SuggestAppointmentSlotByrequest
      x-api-path-slug: apiappointmentsuggest-post
      parameters:
      - in: body
        name: request
        description: An appointment suggest request containing information about the
          desired appointment
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Auto-picks
      - Attendees
      - Next
      - Available
      - Appointment
      - Slot
      - Given
      - Parameters
      - In
      - Request
  /api/documentgeneration/confirmvaluation:
    post:
      summary: Generates a correspondence confirming the booking of a valuation appointment.  Uses
        default values where possible.
      description: Generates a correspondence confirming the booking of a valuation
        appointment.  uses default values where possible..
      operationId: DocumentGeneration_GenerateValuationConfirmationLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationconfirmvaluation-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Correspondence
      - Confirming
      - Booking
      - Of
      - Valuation
      - Appointment
      - ""
      - ""
      - Uses
      - Default
      - Values
      - Where
      - Possible
  /api/documentgeneration/valuationresult:
    post:
      summary: Generates a correspondence confirming the result of a valuation appointment.  Uses
        default values where possible.
      description: Generates a correspondence confirming the result of a valuation
        appointment.  uses default values where possible..
      operationId: DocumentGeneration_GenerateValuationResultLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationvaluationresult-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Correspondence
      - Confirming
      - Result
      - Of
      - Valuation
      - Appointment
      - ""
      - ""
      - Uses
      - Default
      - Values
      - Where
      - Possible
  /api/documentgeneration/rescheduleepcappointment:
    post:
      summary: Generates a EPC Appointment letter correspondence
      description: Generates a epc appointment letter correspondence.
      operationId: DocumentGeneration_RescheduleEpcAppointmentLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationrescheduleepcappointment-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - EPC
      - Appointment
      - Letter
      - Correspondence
  /api/documentgeneration/cancelepcappointment:
    post:
      summary: Generates a cancel an epc appointment letter correspondence
      description: Generates a cancel an epc appointment letter correspondence.
      operationId: DocumentGeneration_CancelEpcAppointmentLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationcancelepcappointment-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Cancel
      - Epc
      - Appointment
      - Letter
      - Correspondence
  /api/documentgeneration/confirmepcappointment:
    post:
      summary: Generates a confirm an epc appointment letter correspondence
      description: Generates a confirm an epc appointment letter correspondence.
      operationId: DocumentGeneration_ConfirmEpcAppointmentLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationconfirmepcappointment-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Confirm
      - Epc
      - Appointment
      - Letter
      - Correspondence
  /api/documentgeneration/confirmgeneralappointment:
    post:
      summary: Generates a confirm general appointment letter correspondence
      description: Generates a confirm general appointment letter correspondence.
      operationId: DocumentGeneration_ConfirmGeneralAppointmentLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationconfirmgeneralappointment-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Confirm
      - General
      - Appointment
      - Letter
      - Correspondence
  /api/documentgeneration/cancelgeneralappointment:
    post:
      summary: Generates a cancel general appointment letter correspondence
      description: Generates a cancel general appointment letter correspondence.
      operationId: DocumentGeneration_CancelGeneralAppointmentLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationcancelgeneralappointment-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Cancel
      - General
      - Appointment
      - Letter
      - Correspondence
  /api/documentgeneration/reschedulegeneralappointment:
    post:
      summary: Generates a reschedule general appointment letter correspondence
      description: Generates a reschedule general appointment letter correspondence.
      operationId: DocumentGeneration_RescheduleGeneralAppointmentLetterPackBygeneratePackDetails
      x-api-path-slug: apidocumentgenerationreschedulegeneralappointment-post
      parameters:
      - in: body
        name: generatePackDetails
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Generates
      - Reschedule
      - General
      - Appointment
      - Letter
      - Correspondence
  /api/todo/event/task/{eventId}:
    get:
      summary: Gets all tasks for a particular event / appointment
      description: Gets all tasks for a particular event / appointment.
      operationId: EventToDo_EventTasksByeventIdBypageSizeBypageNumber
      x-api-path-slug: apitodoeventtaskeventid-get
      parameters:
      - in: path
        name: eventId
        description: Id of event or appointment
      - in: query
        name: pageNumber
        description: Page number
      - in: query
        name: pageSize
        description: Page size
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - S
      - ""
      - Tasksa
      - Particular
      - Event
      - ""
      - ""
      - Appointment
  /api/Valuation/{id}:
    delete:
      summary: Cancel a valuation appointment by id if it exists.
      description: Cancel a valuation appointment by id if it exists..
      operationId: Valuation_DeleteByidBycancelAppointmentDataContract
      x-api-path-slug: apivaluationid-delete
      parameters:
      - in: body
        name: cancelAppointmentDataContract
        description: The cancellation details, including reason of cancellation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: the valuation appointment id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Valuation
      - Appointment
      - By
      - Id
      - If
      - It
      - Exists
  /api/viewing/bookmultiviewing:
    post:
      summary: Book multiple viewings appointment
      description: Book multiple viewings appointment.
      operationId: Viewing_BookMultiViewingBydataContract
      x-api-path-slug: apiviewingbookmultiviewing-post
      parameters:
      - in: body
        name: dataContract
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Book
      - Multiple
      - Viewings
      - Appointment
  /api/viewing/{id}/recordslotapproval/{viewingSlotId}:
    put:
      summary: Set approval status of viewing slot on multi viewing appointment
      description: Set approval status of viewing slot on multi viewing appointment.
      operationId: Viewing_RecordViewingSlotApprovalByidByviewingSlotIdBystatus
      x-api-path-slug: apiviewingidrecordslotapprovalviewingslotid-put
      parameters:
      - in: path
        name: id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: status
      - in: path
        name: viewingSlotId
      responses:
        200:
          description: OK
      tags:
      - Set
      - Approval
      - Status
      - Of
      - Viewing
      - Slot
      - "On"
      - Multi
      - Viewing
      - Appointment
  /api/Viewing/{id}:
    delete:
      summary: Cancel a viewing appointment by id if it exists.
      description: Cancel a viewing appointment by id if it exists..
      operationId: Viewing_DeleteByidBycancelAppointmentDataContract
      x-api-path-slug: apiviewingid-delete
      parameters:
      - in: body
        name: cancelAppointmentDataContract
        description: The cancellation details, including reason of cancellation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: the viewing appointment id
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Cancel
      - Viewing
      - Appointment
      - By
      - Id
      - If
      - It
      - Exists
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