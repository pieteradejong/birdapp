# bird app
my twitter clone, for fun

# MVP:

## Entities
- User
- User Profile
- Tweet
- Follow
- Timeline (populated by some "provide"/mechanism)
- ...

## Use cases
- user can register with email, handle, display name
- user can post a tweet
- user can follow another user
- user can view another user's profile
- user can view timeline of all tweets by followed users, ordered chronologically
- ...


## Architecture
- Python FastAPI 
- MongoDB database for tweets
  - motivation: tweets are document-like in nature, must allow for structural evolution as product matures
- React front-end

# Next version
- Blocking
- Lists

