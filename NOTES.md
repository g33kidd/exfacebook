## Important Stuff

- secure requests with `appsecret_proof`
- use HTTPotion instead of hackney
- **WRITE TESTS**

## Basic Needed Features

- submit graph API calls like the API explorer is able to do.
- create a few helper functions for various API methods.
- upload media for the user

### Helper functions

- me() - retrieves the current user information
- me(params) - retrieves extra information of the current user based on the params
- post(params) - creates a post on behalf of the user in the params
- upload(video or photo, params) - uploads a piece of media based on the params and posts on behalf of the user

**Some basic request helpers**

- get()
- post()
- delete()

## Nodes to Implement

- Page
- Photo
- Post
- Video
