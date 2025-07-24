# Beyond Tickets: The Product Spec is the New Source Code

In the push to be "agile," have we forgotten the most powerful tool for building robust, cost-effective financial systems? I've seen it from the inside—at Bundesbank on a critical subsystem for TARGET/SEPA, and now at the ECB on the digital euro pioneer projects.

While user stories in tickets are useful, relying on them as a complete specification for complex systems is a path to fragmentation, ambiguity, and hidden costs. Once a ticket is closed, its knowledge is buried. For systems handling real money, where the tolerance for error is zero, this isn't a risk we can afford.

The solution isn't to return to the old waterfall model. The solution is to embrace a **living, breathing Product Specification (Pflichtheft)** as a core agile asset.

### An Anchor Point for Human Communication

Before it is a guide for machines, a great spec is a tool for human alignment. When written clearly, it allows business teams, testers, and product owners—not just coders—to contribute, debate, and align on a shared goal. At Bundesbank, on a project some considered "old-fashioned," we had a secret weapon: we refined our spec (Pflichtheft) weekly. We treated it like code, fixing bugs and refactoring it together. It was our single source of truth.

### Designed for a Superior Developer Experience (DX)

In large programmes, information often lies scattered across dozens of documents—rulebooks, API definitions, workflow diagrams, etc. Developers waste precious time digging for the truth.

A great spec solves this. It is structured by business function, not document type. If you are working on a payment type, you find everything in one place: the high-level workflow diagrams, high-level description and examples in natural language, the state transitions, the communication legs, all detailed business rules, and every single success or error message. This creates a superior developer experience, enabling engineers to build with confidence and speed.

### The "New" Way of Writing Code

As Sean Grove of OpenAI aptly put it, the specification *is* the new code. It is the most comprehensive expression of our intent. The source code we write is just a "lossy projection" of that spec. You can see his brilliant talk on this here: [https://www.youtube.com/watch?v=8rABwKRsec4](https://www.youtube.com/watch?v=8rABwKRsec4)

This isn't just a theory for the AI era. My colleagues at Bundesbank were meticulously crafting exhaustive specs for longer than a decade, building rock-solid payment systems that underpin today's German economy. They proved a timeless lesson long before it became the latest trend: the most durable financial systems are built not from scrum sprints, not even directly from code, but from persisted clarity.

### The Payoff: Slashing Costs with Clarity and AI

Today, a top priority for the digital euro programme is to find ways to reduce costs. Here is the most direct way: **invest in the spec.**

A meticulous and exhaustive product spec is the ultimate prompt for Generative AI. With it, we can dramatically cut costs and accelerate development by generating:

* Interface definitions such as OpenAPI specs and gRPC protobuf.
* Most of the working code, and its unit tests and integration tests.
* Comprehensive end-to-end and acceptance test suites.
* CI/CD pipelines, Runtime configurations and API policy code. 
* Clear user documentation.

I’ve put this into practice, turning a detailed spec into automated test code, saving my team countless hours. It transforms development from a manual, error-prone process into a streamlined, automated workflow driven by clear, human-readable intent. It eliminates ambiguity, enables necessary rework to happen with precision and minimal effort, and allows us to build better, faster, and cheaper.

This entire process hinges on a well-defined flow. The diagram below illustrates this spec-driven approach, from initial business requirements to a tested, deployable artifact:

[An iterative workflow with the Product Spec as the single source of truth, serving as the ultimate prompt for development, testing, and documentation.](img/efficient_software_engineering_ning_2025.svg)


### Outlook

For our most critical, long-term initiatives like the digital euro, we need a knowledge base that is built to last. In the age of AI, the most valuable human skill is expressing intent with perfect clarity. The product spec is our primary interface for this future—let's start treating it with the rigor it deserves.

