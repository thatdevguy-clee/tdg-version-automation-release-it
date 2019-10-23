# Details

Don't waste your time downloading this.
`This is just a test.`  Please IGNORE.

This is an example implementation of version automation of an NPM package using Release-It! by Lars Kappert


1) Create a token in github with repo rights. https://github.com/settings/tokens

2) Add this into your package.json file read in the GITHUB_TOKEN:

```
"release-it": {
    "github": {
        "tokenRef": "GITHUB_TOKEN"
    }
},
```

3) Go to terminal and run:
```
export GITHUB_TOKEN="#YOUR-TOKEN-FROM-GITHUB-GOES-HERE#"
```

