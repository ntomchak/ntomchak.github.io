---
layout: project
type: project
image: images/cotton-square.png
title: TMC Minecraft Server
permalink: projects/cotton
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

Over the past several years, I have developed several plugins for TMC using Java. One of them allows players to level up and unlock new items when they reach a certain level through certain ingame tasks, like mining. Online players' xp and levels are cached in a hash map, and are saved to the SQL database when they leave or every 5 minutes.

<img class="ui medium right floated rounded image" src="/images/auction.jpg">

Another plugin I made for the server is called Player Warps. With this unique system, there is a list of 10 warp points that players can teleport to. Each week, there is an auction where the top 10 bids receive a spot on the list of 10 warps, which they can direct to their shops that sell ingame items for ingame currency. This process is automatic and requires no intervention to run the auction, with the auction and warp list cycling automatically every week.

