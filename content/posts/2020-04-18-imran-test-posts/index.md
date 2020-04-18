---
title: Imran Test posts
author: Dennis Brotzky
date: '2020-04-18'
hero: images/mevris-logo.png
---
Performs a left outer join to an unsharded collection in the*same*database to filter in documents from the “joined” collection for processing. To each input document, the[`$lookup`](https://docs.mongodb.com/manual/reference/operator/aggregation/lookup/#pipe._S_lookup "$lookup")stage adds a new array field whose elements are the matching documents from the “joined” collection. The[`$lookup`](https://docs.mongodb.com/manual/reference/operator/aggregation/lookup/#pipe._S_lookup "$lookup")stage passes these reshaped documents to the next stage.
