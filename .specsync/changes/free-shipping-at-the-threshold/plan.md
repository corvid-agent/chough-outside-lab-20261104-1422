---
change: free-shipping-at-the-threshold
artifact: plan
---

# Plan

## Approach

Add FREE_SHIPPING_FROM_CENTS and return a zero fee from that total upward.

## Out of scope

Discount codes, regional fees and checkout wording.

## Steps

1. Add the threshold rule.
2. Add boundary tests.
3. Run the selected cases.

## Risks

An off-by-one at the boundary; covered by TC-shipping-0001.

## Constraints consulted

None beyond the sample module context.
