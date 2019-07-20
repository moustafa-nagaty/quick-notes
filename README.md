# quick-notes
Definitions and explanations of common terminologies.

## Authentication

Is this user really who they say they are? It is the act of identifying who you are, authenticating that you are who you say you are. For example, using a username and password to authenticate yourself.

Related HTTP error code: `401 Unauthorized`. Occurs when user authentication was not possible, either because it has failed (bad credentials), or the authentication paramters (authentication headers) were not present.

## Authorization

What can this user do? It is related to the permissions of the users, what they are allowed to see, edit, delete etc.

### Authorization types:
**Role/User Group based:** For example: Student, Teacher roles. Users will be checked if they are part of a certain group.

**Permission set:** For example: Read from DB, Write to DB. Users will be checked if they have the permission for certain activities.

Related HTTP error code: `403 Forbidden`. Occurs when the server understood the request, but is refusing to fulfill it. The message can sometimes convey why the request failed, for example: Unauthorized - missing `database_read` scope. In some cases, if the server does not wish to make this information available to the client, it uses the `404 Not Found` error code.

## OAuth 2.0

## Session

## Token

## Single Sign On