# Down the Tunnel 🕳️

> **A build-in-public journal of Hedera Agent Commerce Kit (HACK).**

This is the record of building **Hedera Agent Commerce Kit (HACK)** from the inside.

Not the polished version.

Not the finished product.

The actual journey.

The architecture decisions, experiments, mistakes, technical discoveries, configuration work, late-night debugging, things that worked, things that didn't, and everything I learn while trying to build infrastructure that other developers can eventually use.

---

## Why "Down the Tunnel"?

There is a point in every project where the outside world doesn't see much yet.

You have an idea.

You have a repository.

You have a few files.

You have a lot of questions.

And then you start digging.

You don't know exactly what the finished system will look like, but you keep moving deeper, solving one problem after another.

That's where I am with HACK.

**Down the Tunnel** is my way of documenting that process.

The goal isn't to make the journey look perfect.

The goal is to make it **real**.

---

# What is HACK?

**Hedera Agent Commerce Kit (HACK)** is an open-source developer infrastructure project focused on enabling commerce and payment interactions between agents, services, APIs, and applications.

The project is being designed around the idea that software agents will increasingly need to interact with services that aren't simply free endpoints.

Agents may need to:

* Discover services
* Request resources
* Pay for services
* Verify payment outcomes
* Receive receipts
* Handle retries safely
* Observe what happened
* Operate within defined spending constraints

HACK is an attempt to build the infrastructure around those interactions.

The project is still being developed.

This repository documents that development.

---

# What You'll Find Here

Every meaningful development milestone can become a log.

That includes:

### 🧠 Architecture

Why a particular abstraction exists.

Why one approach was chosen over another.

What assumptions changed.

What I got wrong.

### 💻 Implementation

The actual technical work behind HACK.

Examples include:

* Idempotency
* Observability
* Providers
* Receipts
* Exports
* Memory keys
* Base abstractions
* Payment infrastructure
* Agent commerce primitives

### 🔐 Security & Engineering

The work required before and around implementation.

For example:

* Code quality
* Code review
* CodeQL
* Repository protection
* Dependency/security considerations
* Contribution workflows

### 🧪 Experiments

Things I'm testing before deciding whether they belong in the final architecture.

Some experiments will work.

Some won't.

Both are worth documenting.

### 📚 Things I Learn

Technical concepts I didn't understand before starting.

Interesting discoveries.

Mistakes that taught me something.

Things I would do differently if I started again.

---

# The Timeline

The logs are organized chronologically.

Each entry represents a point in the development journey.

A typical entry may contain:

```text
Date
↓
What I worked on
↓
Why I worked on it
↓
What changed
↓
Problems encountered
↓
What I learned
↓
Current state
↓
What's next
```

The objective is to preserve the **reasoning**, not just the commits.

GitHub already tells you *what changed*.

Down the Tunnel tries to explain **why it changed**.

---

# Current Phase

## Surface Layer / Foundation

The project is currently in the foundational stage.

The first step wasn't immediately writing payment logic.

I wanted to establish the engineering foundation first.

The repository was configured with development and security tooling before moving deeper into implementation.

The current implementation work includes foundational components around:

* Idempotency
* Observability
* Logging
* Providers
* No-operation providers
* Receipts
* Exports
* Memory keys
* Base abstractions

This layer is still actively being developed.

---

# Building in Public

HACK is currently being developed privately.

The intention is to eventually open the main project to public contribution once the core surface is sufficiently understandable and stable.

**Down the Tunnel is the public development journal before that happens.**

As the project matures, the goal is to make it possible for developers to contribute in different ways.

You don't necessarily need to write Python to contribute.

You might contribute through:

* Documentation
* README improvements
* Tutorials
* Examples
* Technical writing
* Testing
* Bug reports
* Research
* Architecture discussions
* Developer experience
* Code

Open source isn't only about writing code.

It's about building something that other people can understand, improve, and build upon.

---

# Why I'm Doing This

This is one of the first times I'm deliberately building something with **other developers as potential users and contributors**.

That changes the way I think about engineering.

It's no longer enough to ask:

> "Does it work?"

I also have to ask:

> "Can someone else understand it?"

> "Can someone else use it?"

> "Can someone else contribute to it?"

> "Can someone discover this project without me explaining everything personally?"

Those questions are becoming part of the engineering process itself.

---

# The Bigger Picture

HACK is being built around a broader idea:

**Agents should eventually be able to participate in commerce as software entities.**

If an agent can discover an API, use an MCP tool, request a resource, or interact with another service, there will increasingly be situations where that interaction has an economic component.

The infrastructure required for that world is still being figured out.

HACK is my attempt to explore that problem from the developer-infrastructure side.

Hedera is an important part of that exploration.

But the goal is not to use a technology simply because it exists.

The goal is to solve the underlying problem first and then use the right infrastructure to solve it well.

---

# A Note to Future Me

If you're reading this months or years later and HACK has become something much bigger than what it is today, remember this stage.

Remember the small files.

Remember the configuration.

Remember the abstractions that took hours to get right.

Remember the things that broke.

Remember the uncertainty.

Remember that there was a point where the project was private, the architecture was still evolving, and most people had never heard of it.

This repository exists so that the beginning doesn't disappear.

---

# Follow the Journey

The main HACK project:

**Hedera Agent Commerce Kit**

The development journey:

**Down the Tunnel**

The code will show you what was built.

**These logs will show you how I got there.**

---

> *We're still down the tunnel.*

> *Still building.*

> *Still figuring it out.*
