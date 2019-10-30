# Middleware Notes

#Jargon

Separation of Concerns.
    - code is a communication device to reveal our intentions to the next developer... not writing code for the computer

    - optimize for readability

**EVERYTHING IS MIDDLEWARE!!**

Well, almost everything

##Types (based on how we got it or who built it)

-built-in: included with express. ex: `express.json()`
-third party: must be installed from 'npm'
-custom: we code these!!

## Types (based on how it's being used)

    - global: runs on every req
    - local

Order matters, top to bottom, left to right