# base64ToFile

    var base64ToFile = require('./base64ToFile');
    base64ToFile.convert(data.image,"upload/",['jpg','jpeg','png'], function (filePath) {
        console.log(filePath);
    });
