Strip title and subtext from input. Put inside [JSON utility](https://www.alfredapp.com/help/workflows/utilities/json/). Useful to get clean prompts in Alfred (i.e. it's used in [web-searches](https://github.com/nikitavoloboev/alfred-web-searches) workflow)

```json
{
  "alfredworkflow": {
    "arg": "{query}",
    "config": {
      "title": "",
      "runningsubtext": "",
      "subtext": ""
    },
    "variables": {}
  }
}
```
