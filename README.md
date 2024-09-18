# AutofillBookmarklet
JavaScript to run via Browser bookmark to autofill fields (useful for unsecure http sites)

Add Bookmark

```
javascript:(function() {
    document.getElementById('Id of username box').value = 'username';
    document.getElementById('Id of password box').value = 'password';
    
    document.getElementById('Id of sign in button').disabled = false;
})();
```


