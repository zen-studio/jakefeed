# jakefeed
Jake the feed is a RoR app for small corp social net

#TODO
Models:

- user
  - username
  - password
  - email
- post
  - title
  - body
- comment
  - body
- target
  - name
  - body
  - channel_id
- channel
  - name
  - icon
  - feed_url
  - feed_format
- channel_item
  - body
- subscription
  - user_id
  - target_id

Gems:
- https://github.com/cmer/socialization
