# sign_up_form

A webpage that is built for form validation for a user to *sign up* using HTML and styled with CSS

## Credits
  - google icon => <a href="https://www.flaticon.com/free-icons/google" title="google icons">Google icons created by Freepik - Flaticon</a>
  - user icon => <a href="https://www.flaticon.com/free-icons/user" title="user icons">User icons created by Freepik - Flaticon</a>
  - lock icon => <a href="https://www.flaticon.com/free-icons/lock" title="lock icons">Lock icons created by Those Icons - Flaticon</a>
  - email icon => <a href="https://www.flaticon.com/free-icons/email" title="email icons">Email icons created by Freepik - Flaticon</a>
  - wavy image => [Wolfgang Stanescu @Pinterest](https://za.pinterest.com/wolfgangstanescu/)


## Discoveries and Challenges


### Discoveries

 - [x] For improving the responsiveness of webpage i encountered the `<picture element>`

- This element takes in a set of `<source>` element in which it will display an image depending on screen width of device
- It is also important for the picture element to have a fallback

```
<picture>
  <source media="screen-width" scrset="relative/path/to/file">
  <img src="path/to/fallback" alt="mendatory">
</picture>
```

- [x] To make my images fit the screen and also stick to their ratios i use the CSS property `max-inline-size`

```
img{
  max-inline-size: 100%;
}
```
