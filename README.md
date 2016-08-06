# chen-image-loader
var imgloader = require("./imageloader");
var imglist = {
    src1:"http://c.hiphotos.baidu.com/image/pic/item/472309f7905298220099cbe5d2ca7bcb0a46d46a.jpg",
    src2:"http://f.hiphotos.baidu.com/image/pic/item/b17eca8065380cd70c5150cba444ad345982814d.jpg",
    src3:"http://f.hiphotos.baidu.com/image/pic/item/242dd42a2834349b7eaf886ccdea15ce37d3beaa.jpg"

}
imgloader(imglist,function () {
    alert("ssss");
},500);

图片的数组
回调函数
超时函数