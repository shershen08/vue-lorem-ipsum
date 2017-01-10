### Lorem ipsum text generator for vue.js

Uses [lorem.js](https://github.com/f/loremjs)

### Installation 

Run ```npm install vue-lorem-ipsum```

Add in the component ```import LoremIpsum from 'vue-lorem-ipsum';```

Use in the template ```<lorem add="2p"></lorem>```


### Query language

Lorem.js has a simple query language: "how many?, what?"

 - 2p = 2 paragraphs => ```<lorem add="2p" />```
 - 5s = 5 sentences => ```<lorem add="5s" />```
 - 6w = 6 words => ```<lorem add="6w" />```
 - 1-6w = between 1 and 6 words => ```<lorem add="1-6w" />```
