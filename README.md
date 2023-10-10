# Carrier-Pigeon-Chat
A private (whitelisted) chatroom / postroom using JSON-based posts.

Structure of a post:
```json
{
  "author": "thepigeon",
  "timestamp": (String ISO8601 Standard time in America/Chicago before conversion to local),
  "content": "Content of the post as a string!"
}
```
