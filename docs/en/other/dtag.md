# Information about the problem
If you're here, you've probably noticed that there are a lot of sites and games that are poorly accessible on Magyar Telekom's network. You've probably also heard the news that DTAG, alias the Deutsche Telekom, has been unable to reach an agreement with Cloudflare for years, or that Meta has disconnected from their network.

## The root of the problem
Because of DTAG's business policy, they do not peer with IXPs, only and exclusively with other providers, as they have a direct financial benefit from it. They could not make a profit on an IXP. Although Telekom is connected to the BIX network, they use selective routing technology and we strongly suspect that they only peer with certain BIX members. As a result, some traffic is seen to come and go via Germany, the US or Brazil.

## Where is the solution?
There have been previous instances where the company has been sued, and there are ongoing complaints from the public, but this is not considered a success, as money can solve everything, which DTAG has 🙂.

Of course, if they wanted to, they could solve it, but they don't want to, so there is nothing left but a community solution, which is what we are trying to do.

As you read in the introduction: it's a VPN. The question arises whether other VPNs can solve the problem. The answer is yes. If you have the necessary knowledge, you can find a VPS that is on the DTAG network and create one yourself. Business VPNs such as Proton or Nord will not work because the hosting they are on is M247 and it is known that they do not peer with DTAG. If you really want to use commercial VPN you should look out for ones that is on Datapacket, as the connection from DTAG to them is reliable. Many places write about Cloudflare WARP as a possible solution, we used to suggest it too, but it's not reliable either anymore, so the obvious solution is us!

