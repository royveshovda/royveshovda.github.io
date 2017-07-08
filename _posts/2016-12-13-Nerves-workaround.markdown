---
layout: post
title:  "Nerves workaround"
date:   2016-12-13 07:00:00
categories: blog
---
After a new release of Exrm, we now have dead Nerves-projects.
This is very unfortunate, and I am not sure how the team plan to fix this one.
I have read some rumors that they might replace Exrm with Distillery.

However a workaroud for now is to pin relx and erlware_commons to previous version in your mix.exs file:

'{:relx, "3.21.0", override: true}'
'{:erlware_commons, "0.21.0", override: true}'
