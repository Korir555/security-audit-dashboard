# Security Audit Dashboard

Enterprise compliance and audit framework supporting GDPR, HIPAA, PCI-DSS, ISO27001, CIS Controls, and SOC2 with automated control validation and evidence collection.

## Features

- **Multi-Framework Support**: GDPR, HIPAA, PCI-DSS, ISO27001, CIS, SOC2
- **Automated Validation**: Policy scanning and control effectiveness testing
- **Evidence Collection**: Timestamped, tamper-proof audit trails
- **Finding Management**: Categorization, prioritization, remediation tracking
- **Executive Reporting**: Compliance dashboards and audit reports
- **Remediation Tracking**: Plan creation, status monitoring, closure verification

## Quick Start

```bash
git clone https://github.com/Korir555/security-audit-dashboard.git
cd security-audit-dashboard
pip install -r requirements.txt
flask run
```

Access: http://localhost:5000 (admin / password)

## Frameworks

| Framework | Controls | Status |
|-----------|----------|--------|
| GDPR | 18 | ✓ Implemented |
| HIPAA | 16 | ✓ Implemented |
| PCI-DSS | 12 | ✓ Implemented |
| ISO27001 | 14 | ✓ Implemented |

## Technologies

Python 3.9+ | Flask | PostgreSQL | YAML (policy-as-code) | Elasticsearch

## Hiring Relevance

- Equity Bank GRC operations
- Compliance framework automation
- Regulatory audit support
- Risk and governance management

## Documentation

Full framework mapping and evidence collection: [Case Study](https://korir555.github.io/cybersecurity-portfolio/projects/15-security-audit-dashboard/)

## License

MIT License
