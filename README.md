https://github.com/ipfs/js-ipfs-http-client/tree/master/examples/upload-file-via-browser 这个运行时
const ipfsClient = require('../../../src')这一句报错，我npm install --save ipfs-http-client,然后把这句改成了
const ipfsClient = require('ipfs-http-client')，运行通过。
