# Family Tree (Template)

This is the Family Tree template made by Mayeenul Islam with the love of dTree.

👉 [**Demo**: Family Tree in Bengali](https://mayeenulislam.github.io/family-tree-template/)

> **Note:** Actually I made a family tree for my family in a quick round and thought it might help the others. Hence compiled the code for public. This repository in its **rudimentary shape**.<br>If you make improvement, please don't hesitate to submit Pull Request.

## Screenshots

### Tree View

![Tree View](https://github.com/mayeenulislam/family-tree-template/assets/4551598/9156955a-48cc-4869-ae6e-6ec580d55c39)

### List View (Collapsible)

![List View](https://github.com/mayeenulislam/family-tree-template/assets/4551598/271f1c2c-bb4a-41da-8a8e-81fe4a1a86ff)

## Features

- Family Tree in Tree View
- Family Tree as a list
- Family Tree List has Collapse/Expand feature
- Bengali Support (`bn`)
- Responsive and Mobile-friendly

## Usage

Update the `family-tree.json` file

### Syntax: Marriage & Children

```json
"marriages" : [
  {
    "spouse" : {
      "name" : "সহধর্মীর নাম",
      "class" : "female"
    },
    "children" : [
      {
        "name" : "সন্তান",
        "class" : "male"
      }
    ]
  }
]
```

### Syntax: Person

```json
{
  "name" : "ব‍্যক্তির নাম",
  "extra" : {
    "nickname" : "ডাকনাম"
  },
  "class" : "male",
  "textClass" : "emphasis"
}
```

## Limitations

One: When the tree expands with too many leaves, the tree becomes clueless to the audience (limitation of dTree)

Two: Tree View cannot be collapsed (dTree library does not support that feature)

## Credit

Made with [dTree](https://github.com/ErikGartner/dTree) ([Demo](https://jsfiddle.net/rha8sg79/))

- dTree.js
- Lodash
- d3.js

---

**Mayeenul Islam**<br/>
- X: [@mayeenulislam](https://twitter.com/mayeenulislam)
- LinedIn: [linkedin.com/in/mayeenulislam](https://linkedin.com/in/mayeenulislam)
- Facebook: [fb.me/mayeenulislam](https://facebook.com/mayeenulislam)
- CV: [mayeenulislam.github.io](https://mayeenulislam.github.io)
- YouTube: [youtube.com/mayeenulislam](https://youtube.com/mayeenulislam)
