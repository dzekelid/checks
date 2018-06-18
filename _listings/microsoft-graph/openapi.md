---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/checkMemberGroups:
    post:
      summary: Check Member Groups
      description: Check member groups Check for membership in a specified list of
        groups, and returns from that list those groups of which the specified user,
        group, or directory object is a member. This function is transitive.
      operationId: CheckMemberGroups
      x-api-path-slug: mecheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Member
      - Groups
  /users/{id | userPrincipalName}/checkMemberGroups:
    post:
      summary: Check Member Groups
      description: Check member groups Check for membership in a specified list of
        groups, and returns from that list those groups of which the specified user,
        group, or directory object is a member. This function is transitive.
      operationId: CheckMemberGroups
      x-api-path-slug: usersid--userprincipalnamecheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Member
      - Groups
  /groups/{id}/checkMemberGroups:
    post:
      summary: Group Check Member Groups
      description: 'group: checkMemberGroups Check for membership in the specified
        list of groups. Returns from the list those groups of which the specified
        group has a direct or transitive membership.'
      operationId: Group:CheckMemberGroups
      x-api-path-slug: groupsidcheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - Checks
      - Member
      - Groups
  /directoryObjects/{id}/checkMemberGroups:
    post:
      summary: Check Member Groups
      description: Check member groups Check for membership in a specified list of
        groups, and returns from that list those groups of which the specified user,
        group, or directory object is a member. This function is transitive.
      operationId: CheckMemberGroups
      x-api-path-slug: directoryobjectsidcheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Member
      - Groups
---