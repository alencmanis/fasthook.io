# fasthook.io

Fast webhook routing, transformation, and delivery infrastructure.

Fasthook is a webhook platform for receiving events, routing them to the right destinations, transforming payloads, retrying failed deliveries, and giving teams visibility into the full event flow.

This repository is the public-facing home of the project. It is meant to explain the product, document the repository landscape, and point people to the parts of the Fasthook ecosystem that are intended to be public. It does not include the private core backend source code.

## Why Fasthook

Fasthook is being built to make webhook infrastructure easier to operate:

- fast ingestion for incoming webhook traffic
- flexible routing from one source to many destinations
- connection rules for filtering, delaying, deduplicating, retrying, and transforming events
- request and event visibility for debugging and operations
- a dashboard experience for managing sources, destinations, connections, and transformations

## Product Surface

Based on the current project structure, Fasthook includes:

- `www.fasthook.io` for the public website and docs
- `dashboard.fasthook.io` for the product UI
- `api.fasthook.io` for application APIs
- public webhook pages, docs pages, and API reference content
- operational primitives such as sources, destinations, connections, requests, events, and transformations

## Repository Map

The broader Fasthook project currently spans several repositories:

- `fasthook` - backend pipeline and control API
- `fasthook-ui` - website and dashboard applications
- `fasthook-widget` - Chrome extension / side panel for quick request and event visibility
- `fasthook.io` - public overview repository

## Core Concepts

- `Sources` receive webhook traffic
- `Destinations` define where processed events should be delivered
- `Connections` link sources to destinations
- `Rules` define delivery behavior per connection
- `Transformations` modify payloads before delivery
- `Requests` and `Events` provide operational history and debugging context

## Public Repository Goal

This repository exists to help people quickly understand:

- what FastHook is
- what problems it is solving
- how the product is structured
- which repositories are part of the ecosystem
- where public-facing work and updates live

## Status

Fasthook is an active product project. Some parts of the ecosystem are public-facing, while core implementation details may stay private or be shared selectively over time.

## License

No license is currently attached to this repository.
