# Shipping requirements

### REQ-shipping-001

The module SHALL charge the standard fee for an order under the free-shipping threshold. Trace: CHECKOUT-2.

Acceptance Criteria
- tests/threshold.rs asserts the standard fee just below the threshold.

### REQ-shipping-002

The module SHALL charge no shipping fee for an order total at or above the free-shipping threshold. Trace: CHECKOUT-1.

Acceptance Criteria
- tests/threshold.rs asserts a zero fee at exactly the threshold and above it.

