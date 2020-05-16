# JSON RPC

The next list of JSON RPC calls where used for plugin development.
For response examples see spec/resources:

  * getbalance

    `curl  --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "getbalance", "params": [] }' -H 'content-type: text/plain;' http://user:password@127.0.0.1:17798`
  * getblock

    `curl  --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "getblock", "params": ["51c209db5f7eaad7aee6983579a463eb49f03b9970d8cd852dc687a7380d3abb", 2] }' -H 'content-type: text/plain;' http://user:password@127.0.0.1:17798`
  * getblockcount

    `curl  --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "getblockcount", "params": [] }' -H 'content-type: text/plain;' http://user:password@127.0.0.1:17798`
  * getblockhash

    `curl --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "getblockhash", "params": [40500] }' -H 'content-type: text/plain;' http://user:password@127.0.0.1:17798 `
  * getnewaddress

    `curl --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "getnewaddress", "params": [] }' -H 'content-type: text/plain;' http://user:password@127.0.0.1:17798 `
  * listaddressgroupings

    `curl --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "listaddressgroupings", "params": [] }' -H 'content-type: text/plain;' http://user:password@127.0.0.1:17798`
  * sendtoaddress

    `curl --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "sendtoaddress", "params": ["NrR24vjA6AwoLw9w34hCpJKytUiAJnpSTP", 0.11] }' -H 'content-type: text/plain;' http://user:password@127.0.0.1:17798`
  * methodnotfound

    `curl  --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "methodnotfound", "params": [] }' -H 'content-type: text/plain;' http://user:password@127.0.0.1:17798`
