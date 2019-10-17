https://github.com/ipfs/js-ipfs-http-client/tree/master/examples/upload-file-via-browser 这个运行时
const ipfsClient = require('../../../src')这一句报错，我npm install --save ipfs-http-client,然后把这句改成了
const ipfsClient = require('ipfs-http-client')，运行通过。

昨天弄了一天的没通过的 npm install --save ipfs-http-client 这个命令，原来没仔细看报的错，是没有对root文件夹的访问权限，用chmod命令改一下
root文件夹的权限就可以了。(10.17)
