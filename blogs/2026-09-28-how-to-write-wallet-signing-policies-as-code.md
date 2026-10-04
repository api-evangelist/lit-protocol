---
title: "How to write wallet signing policies as code"
url: "https://spark.litprotocol.com/signing-policies-as-code/"
date: "2026-09-28"
author: "Team Lit"
feed_url: "https://spark.litprotocol.com/rss/"
---
On Lit, a signing policy is a JavaScript function. It runs inside the enclave with the key, so it can check whatever it needs before it signs. Here is how to write one and attach it to a wallet.
