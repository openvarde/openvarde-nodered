# openvarde-nodered

This module provides NodeRED application in OpenVarde for automations and integrations with other systems.

**OpenVarde** is an open-source, modular platform for building resilient and offline-capable information systems for preparedness and emergency use.

## Features

* NodeRED application for automation

## Integration

This module integrates with OpenVarde through:

* **HTTP:** `http://openvarde-[short-id].local/nodered`
* **Dependencies:** `openvarde-core`

## Getting started

### Requirements

* Docker
* Docker Compose
* openvarde-core

### Run

```bash id="ht13no"
git clone https://github.com/openvarde/openvarde-nodered.git
cd openvarde-nodered
docker compose up -d
```

View logs:

```bash id="k9md4g"
docker compose logs -f
```

## Configuration

No configuration available yet.

## Discussion & contributing

OpenVarde is under active development. Testing, bug reports, documentation improvements and code contributions are welcome.

For bugs and concrete development tasks, please use GitHub Issues.

For questions, ideas and general discussion, visit the [OpenVarde section on Norsk Beredskapsforum](https://norskberedskapsforum.no/topic/1871-prosjekt-openvarde-åpen-og-modulær-beredskaps-pc-for-bruk-med-og-uten-internett/).

## AI disclosure

AI-assisted tools are used in the development of OpenVarde, including code, documentation and technical problem solving. AI-assisted contributions are reviewed and treated as development input, not authoritative output.

## License

See `LICENSE` for licensing information.
