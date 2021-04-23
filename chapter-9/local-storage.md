# Storing data with localstorage

```html
<form method='post' action='data:text/plain, Form submited.'>
  <p>Email:<br><input type='email' name='email' id='email' placeholder='test@example.com'></p>
  <p>Password:<br><input type='password' placeholder='********'></p>
  <p><input type='submit' value='Login'></p>
</form>
```


## JavaScript

```javascript
$("#email").on('keyup', function() {
  return localStorage['email'] = $(this).val();
});

$(function() {
  return $("#email").val(localStorage['email']);
});
```


In browser inspector, reader can view and modify any stored data in Local Storage.
