#
`t` is the `type` of the message (remember it).
<br></br>
`message` is the `message`.
<br></br>
`m`'s full form is `message`.
## Example
```json
{
  "t": "m",
  "message": "hello"
}
```
#
`join` is for someone joining.
<br></br>
`username` is the user's name who joined.
## Example
```json
{
  "t": "join",
  "username": "example"
}
```
#
`con` is for not having the connection closed.
<br></br>
`username` is the user's name who sent the message.
## Example
```json
{
  "t": "con",
  "username": "example"
}
```
#
`left` is for someone leaving the site.
<br></br>
`username` is the user's name who left.
## Example
```json
{
  "t": "left",
  "username": "example"
}
```
