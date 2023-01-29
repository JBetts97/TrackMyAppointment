# TrackMyAppointment
Open Source Web application that tracks appointments

## Software Stack
- sprint boot
- mysql
- docker

## Details 
two user types:
service user - creates the appointments
consumer user - gets information about the appointment and can request changes

## Database
- users containing(name, email, address, userid, appointmentid)
- appointments (title, description, datetime, userid, appointmentid)

## Web Application
- sign-up form (create user)
- sign-in form (login as user - authentication required)
- manage appointments
- create appointments 