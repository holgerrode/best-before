# Schema
## Campaign - "ITP Arbeitsphase"
### Attributes
- final event
- events
- admins
- users

## Activity - "Teilnehmer einladen"
### Attributes
- name
- description
- author
- owners
- trigger
- actions

## Trigger - "3 Monate vorher"
### Attributes
- fired by days before event
- fired by activity

## Action - "Einladungsmail schicken"
### Attributes
- name
- description
- send mail
- call URL
- inform user

# Instanzierung
## ScheduledAction
### Attributes
- ref to Schema Activity
- Date
- Status

# Tech details
- Git repo
- Serverless AWS
- DynamoDB as DB storage
- S3 for files
