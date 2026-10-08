# Interledger

**Open protocols for payments and financial connectivity**

Interledger is an open protocol ecosystem designed to enable payments across different networks, currencies, payment systems, and financial services.

It provides open standards and developer tools for building interoperable payment applications and services.

This section collects Interledger documentation, protocols, Open Payments, APIs, SDKs, developer resources, examples, projects, and contribution resources.

---

## Quick Navigation

* [About Interledger](#about-interledger)
* [How Interledger Works](#how-interledger-works)
* [Interledger Protocol](#interledger-protocol)
* [Open Payments](#open-payments)
* [Getting Started](#getting-started)
* [Developer Resources](#developer-resources)
* [APIs and SDKs](#apis-and-sdks)
* [Wallets](#wallets)
* [Examples](#examples)
* [Use Cases](#use-cases)
* [Learning Path](#learning-path)
* [Open Source](#open-source)
* [Projects](#projects)
* [Official Resources](#official-resources)
* [Contributing](#contributing)
* [License](#license)

---

## About Interledger

Interledger is an open protocol ecosystem for connecting different payment networks.

The goal is to make payments more interoperable, allowing value to move between systems without requiring every participant to use the same network, currency, or payment provider.

Interledger can be used to explore applications involving:

* Digital payments
* Financial interoperability
* Cross-border payments
* Micropayments
* Digital wallets
* Payment APIs
* Open financial infrastructure
* Web payments
* Machine-to-machine payments

### Official Website

[Interledger](https://interledger.org/)

### Developer Documentation

[Interledger Developer Documentation](https://interledger.org/developers/get-started/)

### GitHub

[Interledger GitHub Organization](https://github.com/interledger)

---

## How Interledger Works

At a high level, Interledger connects different payment systems through an open protocol.

A simplified flow looks like:

```text
Sender
   ↓
Sender's Payment System
   ↓
Interledger Connector
   ↓
Interledger Network
   ↓
Receiver's Payment System
   ↓
Receiver
```

The important idea is that the sender and receiver do not necessarily need to use the same underlying payment system.

Interledger provides the protocol layer that allows different systems to communicate.

---

## Interledger Protocol

The **Interledger Protocol (ILP)** is the protocol layer that enables payments to move between different ledgers and payment networks.

ILP is designed around interoperability.

Instead of requiring every payment system to connect directly with every other system, Interledger can use connectors between networks.

Conceptually:

```text
Ledger A
   │
   ↓
Connector
   │
   ↓
Ledger B
   │
   ↓
Connector
   │
   ↓
Ledger C
```

This creates a network where different payment systems can participate without becoming one unified ledger.

### Learn More

* [Interledger Developers](https://interledger.org/developers/)
* [Interledger Protocol](https://interledger.org/developers/get-started/)

---

## Open Payments

**Open Payments** is an open standard for building interoperable payment experiences and APIs.

It provides a way for applications to interact with payment accounts and services through standardized interfaces.

Open Payments can be used to build applications involving:

* Sending payments
* Receiving payments
* Payment accounts
* Wallet integrations
* Payment authorization
* Financial applications

### Developer Resources

[Open Payments](https://interledger.org/developers/)

---

## Getting Started

A practical way to explore Interledger is:

```text
Understand Interledger
        ↓
Learn ILP concepts
        ↓
Explore Open Payments
        ↓
Understand wallets
        ↓
Explore APIs
        ↓
Try an SDK
        ↓
Build a payment application
        ↓
Test and experiment
```

Start with the official developer documentation:

[Interledger Developer Documentation](https://interledger.org/developers/get-started/)

---

## Developer Resources

Interledger provides resources for developers interested in building interoperable payment applications.

Explore:

* Protocol documentation
* APIs
* SDKs
* Payment standards
* Wallet integrations
* Developer tools
* Open source repositories
* Examples
* Community projects

### Main Developer Portal

[Interledger Developers](https://interledger.org/developers/)

### GitHub

[Interledger GitHub](https://github.com/interledger)

---

## APIs and SDKs

Interledger provides open source tools and libraries that developers can use to interact with the ecosystem.

Depending on the project, developers can work with:

* Payment APIs
* Open Payments APIs
* ILP implementations
* Wallet APIs
* Client libraries
* Server-side integrations

The Interledger GitHub organization contains the current open source repositories:

[Interledger GitHub](https://github.com/interledger)

---

## Wallets

Wallets are an important part of the Interledger ecosystem.

A wallet can provide the interface through which applications and users interact with payment systems.

A simplified architecture can look like:

```text
Application
     ↓
Wallet
     ↓
Payment API
     ↓
Interledger
     ↓
Payment Network
```

This architecture allows applications to interact with payment infrastructure without needing to implement an entire payment network themselves.

Explore the developer documentation:

[Interledger Developers](https://interledger.org/developers/)

---

## Examples

Interledger can be explored through different types of applications.

### Payment Applications

Applications can use payment APIs to send or receive value.

```text
Application
    ↓
Payment Request
    ↓
Wallet
    ↓
Payment Network
    ↓
Receiver
```

### Micropayments

Interledger can be useful for exploring small-value payment models.

Potential applications include:

* Digital content
* Online services
* APIs
* Streaming
* Creator platforms
* Machine-to-machine payments

### Cross-Network Payments

One of the core concepts is interoperability between different payment systems.

```text
Payment System A
       ↓
      ILP
       ↓
Payment System B
```

---

## Use Cases

Interledger can support a range of financial and web-based use cases.

### Cross-Border Payments

Connect different payment systems and financial networks.

### Micropayments

Explore payment models involving very small transactions.

### Creator Payments

Build systems for paying creators and digital content providers.

### Web Payments

Integrate payment functionality into web applications.

### Digital Services

Enable applications and services to interact with payment infrastructure.

### Machine Payments

Explore automated payments between software systems, services, and devices.

---

## Open Source

Interledger is built around open standards and open source development.

Its GitHub organization contains repositories related to:

* Protocols
* APIs
* SDKs
* Wallets
* Payment infrastructure
* Developer tools
* Documentation

### GitHub Organization

[github.com/interledger](https://github.com/interledger)

Explore the repositories to understand how the different parts of the ecosystem work together.

---

## Learning Path

A practical path for learning Interledger:

```text
1. Understand digital payments
            ↓
2. Learn Interledger concepts
            ↓
3. Understand ledgers and connectors
            ↓
4. Explore ILP
            ↓
5. Learn Open Payments
            ↓
6. Explore wallets
            ↓
7. Explore APIs
            ↓
8. Use an SDK
            ↓
9. Build a payment application
            ↓
10. Experiment with interoperability
            ↓
11. Contribute to Open Source
```

### Beginner

Start with:

* Interledger overview
* Developer documentation
* Basic payment concepts
* ILP fundamentals
* Open Payments

### Intermediate

Explore:

* Wallets
* APIs
* SDKs
* Payment flows
* Interoperability
* Open source repositories

### Advanced

Explore:

* Protocol implementations
* Payment infrastructure
* Connectors
* Wallet architecture
* Open Payments integrations
* Building interoperable financial applications

---

## Projects

This section can be used to document experiments and projects built with Interledger.

Each project can include:

* Project description
* Goal
* Payment flow
* APIs used
* Wallet used
* Technologies
* Setup
* Example requests
* Results
* Lessons learned
* Source code

Example:

```text
projects/
└── payment-project/
    ├── README.md
    ├── src/
    └── examples/
```

---

## Interledger Concepts

Some useful concepts to understand when learning the ecosystem:

| Concept              | Description                                                     |
| -------------------- | --------------------------------------------------------------- |
| **ILP**              | Protocol for connecting different payment systems               |
| **Ledger**           | A system that records balances and transactions                 |
| **Connector**        | Infrastructure that connects payment systems                    |
| **Wallet**           | Interface for interacting with payment accounts                 |
| **Open Payments**    | Open standard for interoperable payment APIs                    |
| **Interoperability** | Ability for different systems to communicate and exchange value |

These concepts provide a foundation for understanding how the ecosystem works.

---

## Official Resources

| Resource    | Link                                                                       |
| ----------- | -------------------------------------------------------------------------- |
| Interledger | [interledger.org](https://interledger.org/)                                |
| Developers  | [Interledger Developers](https://interledger.org/developers/)              |
| Get Started | [Developer Documentation](https://interledger.org/developers/get-started/) |
| GitHub      | [Interledger GitHub](https://github.com/interledger)                       |

---

## Contributing

Interledger is an open source ecosystem and contributions are welcome.

You can contribute through:

* Code
* Documentation
* Tests
* Examples
* Bug reports
* Issues
* Pull requests
* Developer tools
* Community projects

For this toolkit, useful contributions include:

* Tutorials
* Payment flow examples
* API examples
* SDK experiments
* Open Payments projects
* Wallet experiments
* Documentation
* Learning resources

Before contributing to an Interledger project, review the contribution guidelines in the specific repository.

[Interledger GitHub](https://github.com/interledger)

---

## License

Interledger contains multiple open source projects, and each repository may have its own license.

Always check the license of the specific repository or component you are using.

[Interledger GitHub](https://github.com/interledger)

The **Open Source Toolkit** repository itself is licensed under the MIT License.

---

### Explore · Experiment · Build · Share
