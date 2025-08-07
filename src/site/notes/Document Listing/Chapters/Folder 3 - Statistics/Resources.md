---
{"dg-publish":true,"permalink":"/document-listing/chapters/folder-3-statistics/resources/"}
---

Sometimes, as specified, a statistic can create a resource pool. A resource pool consists of a  number of points, which can be lost or replenished.

# Minimum Resource Value
The minimum for a resource is always 0. 

At minimum, you cannot spend any more of that resource, and anything that relies on spending the resource automatically fails.

# Maximum Resource Value
The maximum of a resource equals that of the statistic's value. 
For example, if the frame's integrity is 9, then its maximum integrity is 9 points.

# Loss and Replenishment
When you lose a resource, subtract a relevant value from the resource pool.
- Reaching minimum as a result of a loss often has additional effects.

When you replenish a resource, add a relevant value to the resource pool, up to the maximum. 
- Any replenishment in excess of the maximum is lost.