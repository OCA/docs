---
slug: base_name_search_improved
title: Improved Name Search
---
This module extends the name search feature to use additional, more relaxed matching methods, and to allow searching into configurable additional record fields.

The name search is the lookup feature to select a related record. For example, selecting a Customer on a new Sales order.

For example, typing "john brown" doesn't match "John M. Brown". The relaxed search also looks up for records containing all the words, so "John M. Brown" would be a match. It also tolerates words in a different order, so searching for "brown john" also works.
