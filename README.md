#
`t` is the `type` of the message (remember it).
<br></br>
`message` is the `message`.
<br></br>
`m`'s full form is `message`.

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

```json
{
  "t": "left",
  "username": "example"
}
```
