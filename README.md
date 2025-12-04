# CleanStart Container for Curl

Official Curl container image optimized for enterprise environments. Includes comprehensive HTTP client tools for API testing, web scraping, and data transfer operations. Features security-hardened base image, minimal attack surface, and FIPS-compliant cryptographic modules. Supports both production deployments and development workflows with separate tagged versions. Includes curl, wget, jq, and essential HTTP client tools.

---

## Key Features

Complete HTTP client environment with data transfer capabilities:

- Complete HTTP client environment with data transfer capabilities
- Optimized for cloud-native and microservices architectures
- Security-hardened base image with minimal attack surface
- FIPS-compliant cryptographic modules
- Includes curl, wget, jq, and essential HTTP client tools

---

## Common Use Cases

Typical scenarios where this container excels:

- Building and deploying HTTP clients
- Cloud-native API development
- API testing and validation
- Web scraping operations
- Data transfer and file downloads
- RESTful API interactions

---

## Getting Started

### Pull Commands

Download the runtime container images:
```bash
docker pull ghcr.io/cleanstart-containers/curl:latest
docker pull ghcr.io/cleanstart-containers/curl:latest-dev
```

### Interactive Development

Start interactive session for development:
```bash
docker run --rm -it --entrypoint /bin/sh ghcr.io/cleanstart-containers/curl:latest-dev
```

### Container Start

Start the container(HEAD request to images.cleanstart.com/):
```bash
docker run --rm ghcr.io/cleanstart-containers/curl:latest -I https://images.cleanstart.com/
```

---

## Best Practices

- Use specific image tags for production (avoid latest)
- Configure resource limits: memory and CPU constraints
- Enable read-only root filesystem when possible

---

## Architecture Support

### Multi-Platform Images
```bash
docker pull --platform linux/amd64 ghcr.io/cleanstart-containers/curl:latest
docker pull --platform linux/arm64 ghcr.io/cleanstart-containers/curl:latest
```

---

## Resources

- **Official Documentation:** https://curl.se/docs/
- **Provenance / SBOM / Signature:** https://images.cleanstart.com/images/curl
- **Docker Hub:** https://hub.docker.com/r/cleanstart/curl
- **CleanStart All Images:** https://images.cleanstart.com
- **CleanStart Community Images:** https://hub.docker.com/u/cleanstart

---

## Vulnerability Disclaimer

CleanStart offers Docker images that include third-party open-source libraries and packages maintained by independent contributors. While CleanStart maintains these images and applies industry-standard security practices, it cannot guarantee the security or integrity of upstream components beyond its control.

Users acknowledge and agree that open-source software may contain undiscovered vulnerabilities or introduce new risks through updates. CleanStart shall not be liable for security issues originating from third-party libraries, including but not limited to zero-day exploits, supply chain attacks, or contributor-introduced risks.

**Security remains a shared responsibility:** CleanStart provides updated images and guidance where possible, while users are responsible for evaluating deployments and implementing appropriate controls.
