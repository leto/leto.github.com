---
layout: post
title: Komodo Notary Election 2018 + Team ChainStrike
status: unpublished
---

# What is Komodo?

<a href="https://komodoplatform.com/">Komodo</a> is a source code fork of <a href="https://z.cash">Zcash</a>, one of the first, which has it's own genesis block and so does not share any transaction history with Zcash.
It is one of the most active Zcash forks, with many unique features, while also keeping up-to-date and updating upstream changes from Zcash.

# What is Notarization?

Notarization is the process where data is sent from one chain to another, in particular, from Komodo to Bitcoin, which essentially stores
some data in the Bitcoin blockchain about the current state of the Komodo chain. This means that if somebody wants to 51% attack Komodo,
they actually would need to attack Bitcoin itself, since data about the true state of Komodo is inside of the Bitcoin blockchain.

# What are Notary Nodes?

These special nodes run full Bitcoin and Komodo blockchains and sync special data from the KMD blockchain to the BTC blockchain, specifically,
Merkle Roots. Since Bitcion has a blocktime of 10 minutes, and Komodo has a blocktime of 1 minute, it there is essentially a snapshot
of the state of the KMD chain sent to the BTC chain continuously, and you need to wait about 10 minutes for that enhanced BTC hashpower
security to kick in. And to be clear, data that has only been on the Komodo blockchain for ~9 minutes or less is not protected by Bitcoin, since
there hasn't been a Bitcoin block to include the data in, yet.

# Why are Notaries being elected?

Komodo is a community-driven coin and also understands that decentralized notaries all over the world, run by diverse individuals, is the
best and most secure way to run the system, so these elections exist to serve that purpose. There are 4 regions around the world and
rotating spots which are up for election each year. There are a total of 64 notary nodes and 30 are running in the
<a href="https://www.dexstats.info/votelist.php">VOTE2018 election</a>. The 2018 elections were complete on April 1st, congrats to all
the new node operators!

# Why should I vote for one notary or another?

Reasons for voting are personal, but should include how much you trust the node operator to do a good job, keep their servers secure
and running and also what other "perks" various node operators claim to provide. Also, seeing that potential node operators have a
history as part of Komodo or other cryptocoins is a good sign.

# How is this related to Bitcoin Hush?

<a href="https://btchush.org">Bitcoin Hush</a> is a Komodo asset chain, so it relies on notarization to get "Bitcoin hashpower security" and hence it relies on notary
node operators to do their jobs correctly. Komodo notarization to Bitcoin gives BTCH more hashpower security than every other Bitcoin
fork.

# ChainStrike

This brings me to <a href="http://votefor.chainstrike.io/">Team ChainStrike</a>, which I joined because I wanted to be part of the notarization process which Bitcoin Hush depends on,
as well learn about it more deeply, since all of jl777's ideas have wheels within wheels. The team combines many years of Komodo notary
experience with core developer knowledge.

Team ChainStrike would like to thank all of our voters who helped us earn a
spot as a SH notary node for 2018!
