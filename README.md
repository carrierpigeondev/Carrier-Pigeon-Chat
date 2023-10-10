# Carrier-Pigeon-Chat
A private (whitelisted) chatroom / postroom using JSON-based posts.


##Posts are JSON object in the following format.

"author" is the UAN (User Account Name), not their PVN (Preferred Visible Name)
"timestamp" must be in the ISO 8601 standard. Can be generated with `generate_timestamp.iso_8601()`
"content" is the text content of the post

Example:

```json
{
    "author": "thepigeon",
    "timestamp": "2023-10-09T12:51:48",
    "content": "Hello, Pigeons!"
}
```
