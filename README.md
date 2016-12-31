# This is a fork

I need a fix for [#365](https://github.com/esdoc/esdoc/issues/365) and there is a pending [PR](https://github.com/esdoc/esdoc/pull/364), so I release it for myself / others.

# ESDoc

ESDoc is a documentation generator for JavaScript(ES2015 or later).

<img class="screen-shot" src="https://esdoc.org/manual/asset/image/top.png" width="500px" style="max-width: 500px; border: 1px solid rgba(0,0,0,0.1); box-shadow: 1px 1px 1px rgba(0,0,0,0.5);">

# Features
- Generates good documentation.
- Measures documentation coverage.
- Integrate test codes into documentation.
- Integrate manual into documentation.
- Parse ECMAScript proposals.
- [ESDoc Hosting Service](https://doc.esdoc.org)

# Users
- [ESDoc](https://doc.esdoc.org/github.com/esdoc/esdoc/) (self-hosting &#x1F604;)
- [RxJS](http://reactivex.io/rxjs/)
- [Sketch API](http://developer.sketchapp.com/reference/api/)

And [more](https://github.com/search?o=desc&q=esdoc+filename%3Apackage.json+-user%3Ah13i32maru+-user%3Aesdoc+-user%3Aes-doc&ref=searchresults&s=indexed&type=Code&utf8=%E2%9C%93).

# Quick Start
```sh
# install ESDoc from npm
npm install -g esdoc

# move to a your project directory
cd your-project/

# write a configuration file.
echo '{"source": "./src", "destination": "./doc"}' > .esdoc.json

# run ESDoc
esdoc

# see a documentation
open ./doc/index.html
```

# Document
please visit [esdoc.org](https://esdoc.org) to see more documentation.

[roadmap of v1.0.0](https://github.com/esdoc/esdoc/issues/293)

# License
MIT
