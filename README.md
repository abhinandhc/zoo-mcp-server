# Secure MCP Server on Google Cloud Run

This repository contains a Model Context Protocol (MCP) server built with FastMCP and deployed securely to Google Cloud Run with IAM authentication.

## Features & Tools

- `get_animals_by_species`: Queries zoo animals by species.
- `get_animal_details`: Retrieves habitat and trail details for a specific animal.

## Architecture

- Containerized via Docker using Python 3.13 and `uv`.
- Hosted on Google Cloud Run (`--no-allow-unauthenticated`).
- Invoked via Antigravity CLI (`agy`) or AI agents using Bearer ID tokens.
