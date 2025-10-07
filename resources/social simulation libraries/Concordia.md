# Concordia Library for Social Agent Simulation

Following up on our discussion in class today (week 2 - 09/30/2025) about creating LLM agents with certain life stages and developing better frameworks for social simulation, I wanted to share the [Concordia](https://github.com/google-deepmind/concordia) library developed by Google DeepMind that addresses many of the challenges we talked about.

## What is Concordia?

Concordia is a powerful library for creating Generative Agent-Based Models (GABMs) - simulations where AI agents interact in physical, social, or digital spaces using natural language. Think of it as creating a realistic social simulation where each agent has their own personality, memories, and backstory!

## Why It's Great for Social Simulation

While the library does have some issues and limitations, it performs remarkably well on social experiments and provides excellent documentation to help you get started. Here are the key features:

### Game Master Architecture

Concordia uses a unique approach inspired by tabletop role-playing games. A special "Game Master" agent narrates the world and manages the environment while player agents interact using natural language descriptions like "Alice makes breakfast" or "Bob calls a town meeting."

### Rich Persona Development

Agents are designed around three key questions (inspired by March & Olsen, 2011):

- What kind of situation is this?
- What kind of person am I?
- What does a person such as I do in a situation such as this?

### Sophisticated Memory System

- **Associative Memory**: Agents use embeddings and semantic search to retrieve relevant past experiences
- **Formative Memories**: Backstories can include memories from different life stages
- **Contextual Retrieval**: Memory retrieval is triggered by situation relevance

### Backstory Generation

You can create diverse agents by:

- Defining traits (e.g., "very rude", "slightly irritable")
- Writing backstories that condition the LLM
- Generating sequences of formative memories at different ages
- Creating realistic individual differences through initial conditions

### Component System

Agents are built using flexible components including:

- **Identity** (core characteristics, daily occupation, feelings about life)
- **Plans** (goals and intentions)
- **Observations** (what they perceive)

All components work together to create coherent, realistic behavior.

---

Feel free to explore the documentation and examples in the GitHub repository.

This library does have some limitations, but I find it really cool for social simulation and believe it's one step closer to creating realistic agent-based models of human social behavior.

**GitHub Link**: https://github.com/google-deepmind/concordia
