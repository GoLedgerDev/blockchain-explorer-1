#API Mapping

## Get Number of Transactions in Block

URL: http://<host>:<port>/api/block/transactions/<channel>/<block-number>

```
channel: name of the channel containing the block
block-number: number of the block wanted
```

Returns:
```json
{
    "number": 2, // block number
    "txCount": 1 // number of transactions in block
}
```

## Get Transaction Information

URL: http://<host>:<port>/api/transaction/<channel>/<txid>

## Get Peer List

URL http://<host>:<port>/api/peers/<channel>

## Get Block List from blockNum to end of chain

URL: http://<host>:<port>/api/blockAndTxList/channel/<blockNum>/

## Transactions by Org

URL: http://<host>:<port>/api/txByOrg/<channel>

## Get Channels

URL: http://<host>:<port>/api/channels/<info>