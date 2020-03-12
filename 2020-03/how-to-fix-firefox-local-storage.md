How to Fix Firefox's Local Storage NS_ERROR_FILE_CORRUPTED Error
================================================================

Close Firefox before continue.

Go to your Firefox's profile directory. In macOS, it is at: `/Users/<user+name>/Library/Application Support/Firefox/Profiles/<profile_name>`

Remove all local storage files. Yes, this will wipe out all your local storage data.

```
rm -r storage webappsstore.sqlite storage.sqlite
```

Start Firefox and you should be fine now.

