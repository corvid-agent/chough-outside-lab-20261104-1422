## ADDED

### REQUIREMENT REQ-shipping-002

The module SHALL charge no shipping fee for an order total at or above the free-shipping threshold. Trace: CHECKOUT-1.

Acceptance Criteria
- tests/threshold.rs asserts a zero fee at exactly the threshold and above it.

## MODIFIED

### SPEC SECTION Public API

| Name | Description |
|------|-------------|
| `FREE_SHIPPING_FROM_CENTS` | Order total in cents from which shipping is free |
| `STANDARD_FEE_CENTS` | Standard shipping fee in cents |
| `shipping_fee` | Shipping fee in cents for an order total in cents |
