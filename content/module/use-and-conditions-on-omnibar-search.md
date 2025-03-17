---
slug: web_search_with_and
title: Use AND conditions on omnibar search
usage: >-
  As an internal user, go to the search bar of the application you are on.


  Search for your first criteria.


  Type the second criteria then press the "Shift" key on your keyboard.


  At the same time, press the "Enter" key or click on the field you want to search in.


  Odoo will apply the condition "AND".
context: >-
  In vanilla Odoo, searching with multiple criteria for the same field is always
  performed using the "**OR**" condition.


  For example : 


  * Search for contact "*John*" on the field `Name`

    * Odoo displays contacts containing "*John*"
  * Search for "*Smith*" on same field `Name`

    * Odoo displays contacts containing "*John*" OR "*Smith*"

  Sometimes, we need to refine the search by adding more criteria to the search like in the example.
---
This module allows you to perform a search that combines multiple criteria for the same field (using the "**AND**" condition) by pressing the "*Shift*" key on your keyboard before searching.
