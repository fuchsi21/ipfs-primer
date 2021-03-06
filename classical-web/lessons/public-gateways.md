# Lesson: Using the public IPFS gateways at ipfs.io to access content

This lesson explains how to retrieve IPFS content from the public IPFS gateways at ipfs.io. This topic is covered in greater depth in the tutorial on [Interacting with the Classical (HTTP) Web](/classical-web/README.md).

## Goals

After doing this Lesson you will be able to  
* Use the public gateway at ipfs.io to access IPFS content

## How to Do It

This process is the same as [using any other IPFS gateway](/classical-web/lessons/other-gateways.md) -- only the address of the gateway is different: If you're using the hash of a specific snapshot of content, use the path `https://ipfs.io/ipfs/<your-ipfs-hash>`. If you're using an IPNS hash to get the _latest_ version of some content, use the path `https://ipfs.io/ipns/<your-ipns-hash>`

To view the wikipedia page we're using as an example in all of the lessons in the [Tutorial on The Myriad Ways to Access and Distribute IPFS Content](/avenues-for-access/README.md), use these links:

- 2017-04-30 snapshot: http://ipfs.io/ipfs/Qme2sLfe9ZMdiuWsEtajWMDzx6B7VbjzpSC2VWhtB6GoB1/wiki/Anasayfa.html
- latest (IPNS): http://ipfs.io/ipns/QmQP99yW82xNKPxXLroxj1rMYMGF6Grwjj2o4svsdmGh7S/wiki/Anasayfa.html [correct example though this link may be stale]
- latest (DNS): http://ipfs.io/ipns/ipfs.io

## Explanation

The IPFS project maintains public IPFS gateways that you can use to access any content from the IPFS network. When sharing HTTP links to IPFS content, people often use ipfs.io addresses but you can use the address of any gateway.

## Next Steps

If you want to learn about the many other ways you can use IPFS to access the same content using the same content-addressed link, go to the [Tutorial on The Myriad Ways to Access and Distribute IPFS Content](/avenues-for-access/README.md).

Otherwise proceed to the next lesson to learn how to [Access IPFS content through any IPFS gateway](/classical-web/lessons/other-gateways.md)
