# marked

expand [marked](https://github.com/chjj/marked) with custom heading ids feature.

## install 

    npm install marked-with-custom-heading-ids --save

## usage

    var marked = require('marked-with-custom-heading-ids');
    marked(text, { headerIdCreator:function () {
        return Math.floor(Math.random() * 1000)
    } })