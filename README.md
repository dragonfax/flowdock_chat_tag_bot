
Simple script that listens to the chat in a flowdock flow and duplicates any chat messages that contain a specific tag, into the team inbox.

This is pretty simple, but it might serve as an example on how to use the streaming and non-streaming api (in a lazy way).

### How to run it

1. bundle install
2. copy config.rb.example and secrets.rb.example and fill in the values
3. bundle exec ./daemon

Now if you use the #sticky tag in the chat in that flow, the message will be duplicated over to the "team inbox"

### Notes:

Use an email with a gravatar if you want an icon for those inbox items.




