# figma-tokens-sync-example

Using [open-props](https://github.com/argyleink/open-props) in [figma-tokens](https://github.com/six7/figma-tokens).

Use this URL: 

```
https://raw.githubusercontent.com/hchiam/figma-tokens-sync-example/main/open-props.figma-tokens.sync.json
```

Sync > URL > Add new credentials > Name and [URL](https://raw.githubusercontent.com/hchiam/figma-tokens-sync-example/main/open-props.figma-tokens.sync.json) > Save > Tokens

![setup](setup.gif)

The JSON tab uses the top-level string `"open-props"` as the name, so if you're manually copy-pasting into the JSON tab, you can go one level down to things like `"color"`, `"sizing"`, etc. Note that it doesn't necessarily match the "Name" that you entered for credentials in the Sync tab.

![JSON tab looks different](json-tab-looks-different.png)

## Further work:

Currently, using the URL tab in the figma-tokens plugin prevents you from editing the JSON or from adding your own tokens. So for extra flexibility and more realistic usage, you'll need to use the JSONbin or GitHub settings. Or download the JSON file and use it. 
