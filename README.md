# olivetree

Agentic AI for life insurance pricing.

This project is at an early stage. `olivetree` is a meta-package that installs
the following components, which share the `olivetree` namespace:

| PyPI package        | Import as           | Purpose                                                     |
| ------------------- | ------------------- | ----------------------------------------------------------- |
| `olivetree-tools`   | `olivetree.tools`   | Building-block utilities used by agents.                    |
| `olivetree-agents`  | `olivetree.agents`  | Agentic components built on top of tools.                   |
| `olivetree-mcp`     | `olivetree.mcp`     | MCP server exposing olivetree tools and agents.             |
| `olivetree-servers` | `olivetree.servers` | Servers that expose olivetree tools and agents as services. |

## Installation

```bash
pip install olivetree
```
