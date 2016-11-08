# Description
Here we list the minimum requirements that a repository must fulfill.

# Requirements
* JWT Authentication
* A CRUD implementation for a root model
* A CRUD for Relationships

All CRUD implementations must implement:
* At least one *Create* endpoint must be available via a *Post* request.
* At least one *Read* endpoint must be available via a *Get* request.
* At least one *Update* endpoint must be available via a *Put* request.
* At least one *Delete* endpoint must be available via a *Delete* request.

The HEAD and OPTIONS implementation are optional.

The PATCH implementation is optional.

# Database
All implementations must use only the framework's tool to access the database.

Creating the tables, seeding data, queries etc. all must be as agnostic as possible.

# Endpoints
A list of some basic endpoints that must be implemented:
* (POST) /login

* (GET) /contacts
* (GET) /contacts/:id
* (POST) /contacts
* (PUT) /contacts/:id
* (DELETE) /contacts/:id

* (GET) /contacts/:id/address
* (POST) /contacts/:id/address (should this be sent within the parent's request?)
* (PUT) /contacts/:id/address
* (DELETE) /contacts/:id/address (should we allow this?)

# Responses
TBI

# Documentation
TBI

# Tests
TBI

# CI
TBI
