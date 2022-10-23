# Bank of happiness (adapter)

## Overview

Bank of Happiness provides the ability to receive payments with or without a card using Express Pay terminals.

[More](docs/Bank%20of%20Georgia%20Adapter-Specification.pdf)

### Integration

To integrate with the pay box, you must contact the Bank of Happiness and request to become a service provider for iPay.\
The payment process is straightforward, and, roughly, consists of three steps:

1. getting information about the customer
2. verifying availability of payment
3. receive payment

To authorize request - USERNAME, PASSWORD and HASH_CODE parameters will be sent in the request from the Bank of Happiness.

## Design

### Component Diagram

![Component-Diagram](./docs/Bank%20of%20Georgia%20Adapter-Components.drawio.png)

### Sequence Diagrams

Verify

![Verify-Sequence-Diagram](./docs/Bank%20of%20Georgia%20Adapter-Verify%20Sequence.drawio.png)

Payment

![Payment-Sequence-Diagram](./docs/Bank%20of%20Georgia%20Adapter-Pay%20Sequence.drawio.png)

Ping

![Ping-Sequence-Diagram](./docs/Bank%20of%20Georgia%20Adapter-Ping%20Sequence.drawio.png)

Debt

![Debt-Sequence-Diagram](./docs/Bank%20of%20Georgia%20Adapter-Debt%20Sequence.drawio.png)

## API Specification

> Coming soon
