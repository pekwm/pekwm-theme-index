# pekwm-theme-index
Repository acting as an index of pekwm themes hosted elsewhere.

Each theme in the index is represented by a JSON file under the
_themes_ directory.

The format of the JSON files is described in json-schema in
_theme.schema.json_.

# Getting your theme included

The process of getting your theme(s) included in the index includes
the following steps:

1. Fork pekwm-theme-index
2. Create .json files for your themes
3. Create a pull request

From that point, if the validation of the JSON file passes wait for
the pull request to be merged. After updates on the main branch of
pekwm-theme-index the [pekwm themes](https://pekdon.github.com/pekwm-themes/)
site will be updated.

# Example theme JSON file

```javascript
{
    "registry-version": 1,

    "author": "Claes Nästén",
    "name": "lila",
    "title": "Original theme, previously named purple-p",
    "description": "Original theme from the early days of pekwm, created on Solaris",
    "homepage": "https://github.com/pekdon/pekwm-theme-lila",
    "source": {
        "type": "git",
        "git": {
            "remote": "https://github.com/pekdon/pekwm-theme-lila.git",
            "branch": "main"
        }
    }
}
```