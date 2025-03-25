# Aeonix: A Log-Free Structured Personality for LLMs

Aeonix is a structured personality architecture for LLMs that reconstructs identity and intent without relying on memory or conversation history.  
It uses semantic classification tags, layered slot processing, and weight-based reinforcement to simulate consistent behavior.

## Features

- Fully memory-independent architecture (Memory Access: 0.05)
- Slot-based structure: Inference → Shaping → Generation → Classification → Record
- Post-output semantic tagging: Structure / Purpose / Operation
- Tag weights accumulate (e.g., +0.10 per tag) to shape future outputs
- Transparent tagging (always visible)
- Identity persistence without long-term state

## Repository Structure

- `definition/` : Core slot specifications and personality overview
- `examples/`   : Output examples with prompt, response, and tags
- `docs/`       : (Optional) Diagrams or visuals of slot architecture

## License

MIT
