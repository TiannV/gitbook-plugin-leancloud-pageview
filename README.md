# leancloud integration for GitBook

To use the leancloud plugin in your Gitbook project, add the leancloud plugin to the `book.json` file

```
{
    "plugins": ["leancloud"],
    "pluginsConfig": {
        "leancloud": {
            "app_id": "XXXXXXX",
            "app_key": "xxxxxx",
        }
    }
}
```

Then run `gitbook install` to download and install the plugin.
