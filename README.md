# npmdoc-xml2js

#### api documentation for  [xml2js (v0.4.17)](https://github.com/Leonidas-from-XIV/node-xml2js)  [![npm package](https://img.shields.io/npm/v/npmdoc-xml2js.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-xml2js) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-xml2js.svg)](https://travis-ci.org/npmdoc/node-npmdoc-xml2js)

#### Simple XML to JavaScript object converter.

[![NPM](https://nodei.co/npm/xml2js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/xml2js)

- [https://npmdoc.github.io/node-npmdoc-xml2js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-xml2js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-xml2js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-xml2js/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-xml2js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-xml2js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "xml2js",
    "description": "Simple XML to JavaScript object converter.",
    "keywords": [
        "xml",
        "json"
    ],
    "homepage": "https://github.com/Leonidas-from-XIV/node-xml2js",
    "version": "0.4.17",
    "author": "Marek Kubica <marek@xivilization.net> (https://xivilization.net)",
    "contributors": [
        "maqr <maqr.lollerskates@gmail.com> (https://github.com/maqr)",
        "Ben Weaver (http://benweaver.com/)",
        "Jae Kwon (https://github.com/jaekwon)",
        "Jim Robert",
        "Ștefan Rusu (http://www.saltwaterc.eu/)",
        "Carter Cole <carter.cole@cartercole.com> (http://cartercole.com/)",
        "Kurt Raschke <kurt@kurtraschke.com> (http://www.kurtraschke.com/)",
        "Contra <contra@australia.edu> (https://github.com/Contra)",
        "Marcelo Diniz <marudiniz@gmail.com> (https://github.com/mdiniz)",
        "Michael Hart (https://github.com/mhart)",
        "Zachary Scott <zachary@zacharyscott.net> (http://zacharyscott.net/)",
        "Raoul Millais (https://github.com/raoulmillais)",
        "Salsita Software (http://www.salsitasoft.com/)",
        "Mike Schilling <mike@emotive.com> (http://www.emotive.com/)",
        "Jackson Tian <shyvo1987@gmail.com> (http://weibo.com/shyvo)",
        "Mikhail Zyatin <mikhail.zyatin@gmail.com> (https://github.com/Sitin)",
        "Chris Tavares <ctavares@microsoft.com> (https://github.com/christav)",
        "Frank Xu <yyfrankyy@gmail.com> (http://f2e.us/)",
        "Guido D'Albore <guido@bitstorm.it> (http://www.bitstorm.it/)",
        "Jack Senechal (http://jacksenechal.com/)",
        "Matthias Hölzl <tc@xantira.com> (https://github.com/hoelzl)",
        "Camille Reynders <info@creynders.be> (http://www.creynders.be/)",
        "Taylor Gautier (https://github.com/tsgautier)",
        "Todd Bryan (https://github.com/toddrbryan)",
        "Leore Avidar <leore.avidar@gmail.com> (http://leoreavidar.com/)",
        "Dave Aitken <dave.aitken@gmail.com> (http://www.actionshrimp.com/)",
        "Shaney Orrowe <shaney.orrowe@practiceweb.co.uk>",
        "Candle <candle@candle.me.uk>",
        "Jess Telford <hi@jes.st> (http://jes.st)",
        "Tom Hughes <<tom@compton.nu> (http://compton.nu/)",
        "Piotr Rochala (http://rocha.la/)",
        "Michael Avila (https://github.com/michaelavila)",
        "Ryan Gahl (https://github.com/ryedin)",
        "Eric Laberge <e.laberge@gmail.com> (https://github.com/elaberge)",
        "Benjamin E. Coe <ben@npmjs.com> (https://twitter.com/benjamincoe)",
        "Stephen Cresswell (https://github.com/cressie176)",
        "Pascal Ehlert <pascal@hacksrus.net> (http://www.hacksrus.net/)",
        "Tom Spencer <fiznool@gmail.com> (http://fiznool.com/)",
        "Tristian Flanagan <tflanagan@datacollaborative.com> (https://github.com/tflanagan)",
        "Tim Johns <timjohns@yahoo.com> (https://github.com/TimJohns)",
        "Bogdan Chadkin <trysound@yandex.ru> (https://github.com/TrySound)",
        "David Wood <david.p.wood@gmail.com> (http://codesleuth.co.uk/)",
        "Nicolas Maquet (https://github.com/nmaquet)"
    ],
    "main": "./lib/xml2js",
    "files": [
        "lib"
    ],
    "directories": {
        "lib": "./lib"
    },
    "scripts": {
        "test": "zap",
        "coverage": "nyc npm test && nyc report",
        "coveralls": "nyc npm test && nyc report --reporter=text-lcov | coveralls"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/Leonidas-from-XIV/node-xml2js.git"
    },
    "dependencies": {
        "sax": ">=0.6.0",
        "xmlbuilder": "^4.1.0"
    },
    "devDependencies": {
        "coffee-script": ">=1.10.0",
        "coveralls": "^2.11.2",
        "diff": ">=1.0.8",
        "docco": ">=0.6.2",
        "nyc": ">=2.2.1",
        "zap": ">=0.2.9"
    },
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
