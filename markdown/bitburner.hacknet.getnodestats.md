<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Hacknet](./bitburner.hacknet.md) &gt; [getNodeStats](./bitburner.hacknet.getnodestats.md)

## Hacknet.getNodeStats() method

Get the stats of a hacknet node.

<b>Signature:</b>

```typescript
getNodeStats(index: number): NodeStats;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  index | number | Index/Identifier of Hacknet Node |

<b>Returns:</b>

[NodeStats](./bitburner.nodestats.md)

Object containing a variety of stats about the specified Hacknet Node.

## Remarks

RAM cost: 0 GB

Returns an object containing a variety of stats about the specified Hacknet Node.

Note that for Hacknet Nodes, production refers to the amount of money the node generates. For Hacknet Servers (the upgraded version of Hacknet Nodes), production refers to the amount of hashes the node generates.
