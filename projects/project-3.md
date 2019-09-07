---
layout: project
type: project
image: images/Grass_Block_Revision_6.png
title: TMC Minecraft Server
permalink: projects/tmc
# All dates must be YYYY-MM-DD format!
date: 2018-01-12
labels:
  - Linux server
  - Java
  - SQL
  - Networking
summary: A Minecraft server I created and managed.
---

The TMC Minecraft server is a open-world survival Minecraft server that I created and manage. There are actually about a dozen servers running across 3 machines that make up TMC, including the main Minecraft server, a captcha server, eight or so proxies, and a few "decoy" Minecraft servers for shadowbanned bot accounts. The network typically peaks at 30-40 concurrent real players on the weekends, and during peak months there have been as many as 70 concurrent players.

Over the past several years, I have developed several plugins for TMC using Java. One of them allows players to level up and unlock new items when they reach a certain level through certain in-game tasks, like mining. Online players' xp and levels are cached in a hash map, and are saved to the SQL database when they leave or every 5 minutes.

<img class="ui medium right floated rounded image" src="/images/auction.jpg">

Another plugin I made for the server is called Player Warps. With this unique system, there is a list of 10 warp points that players can teleport to. Each week, there is an auction using the in-game currency, where the top 10 bids receive a spot on the list of 10 warps, which they can direct to their shops that sell in-game items for in-game currency. This process is automatic and requires no intervention to run the auction, with the auction and warp list cycling automatically every week.

The plugin I am most proud of, which secures the server against spam bot accounts, is listed as "Bungee Player Filter" in my projects.

The server makes money by selling ranks that provide some in-game features and cosmetics. You can find the webstore [here](http://toomanyco.ws/vip).

In addition to maintaining the technical side of the server, I also select and manage the team of volunteer staff who moderate the chat and keep troublemakers in check. The staff are selected from applicants who submit their applications through Discord. Staff are given a quick training and follow my [staff handbook](https://docs.google.com/document/d/1HoTug_RQ5UcyASbFRJ2PnaKeDh6IlFnTXNDZ79ClQEU/).
