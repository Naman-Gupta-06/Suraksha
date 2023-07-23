# Requirements

- User should be able to create SOS request.
  - [Should be able to make one successfull sos request ]
  - [should get the acknowledgement for success]
  - [should retry after failure occured]
  - [Should be able to store 5 emergency contacts]

- Any SOS should be visible to all those users who are in the range (1km)
- Store all the SOS requests made till now.
- Store the location locally and globally on the server.
- SOS request of same severity could be send after 30mins.

- User Profile:
    - Name
    - Mobile Num
    - 5 Emergency Contacts
    - Photo
    - bool Verified(Mobile Number)
    - password
    - email
    - location [max last 10 different locations]

- SOS requests
    - Severity message
    - last 5 location Coordinates
    - [Based on sevierty send audio/video/camera intruder/live locations]
    - [if high severity then send notifications to all the users nearby in 1km range]

    
