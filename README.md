## Lorem ipsum text generator for vue.js

### Installation

Run ```npm install vue-lorem-ipsum --save```

### Usage

Add in the component ```import LoremIpsum from 'vue-lorem-ipsum';```

Use in the template ```<lorem add="2p"></lorem>```

### Query language

It uses [lorem.js](https://github.com/f/loremjs) logic for generating the text blocks.
Lorem.js has a simple query language: "how many?, what?"

 - 2p = 2 paragraphs => ```<lorem add="2p" />```
 - 5s = 5 sentences => ```<lorem add="5s" />```
 - 6w = 6 words => ```<lorem add="6w" />```
 - 1-6w = between 1 and 6 words => ```<lorem add="1-6w" />```
