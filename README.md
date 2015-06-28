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
  - node_id
- target
  - name
  - body
  - channel_id
- channel
  - name
  - icon
  - feed_url
  - feed_format
  - feed_formula
- channel_item
  - body
  - channel_id
  - image
  - title
  - url
  - pub_date
- subscription
  - user_id
  - target_id

Gems:
- https://github.com/cmer/socialization
