# Pull Request template for migrating signup/unregister to JSON body

This PR changes the signup and unregister endpoints to accept a JSON body with an email field and adds server-side validation using Pydantic's EmailStr.

See issue #8 for context.
