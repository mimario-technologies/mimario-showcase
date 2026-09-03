# Security Policy & Safe-Harbor Architecture

MIMARIO was engineered from inception around defensive isolation and fail-closed operational security.

## Core Architectural Invariants
1. **Local-First Processing:** All task qualification, proposal synthesis, and repository intake occur strictly on the operator workstation. No proprietary code is transmitted to external cloud VMs.
2. **Fail-Closed Gate 0:** Execution locks automatically prohibit any modifications to third-party code before verified funding/deposit confirmation.
3. **Loopback Isolation:** The Control Room web application and internal API bind strictly to `127.0.0.1:43177` and reject external network traffic.
4. **Zero Private Key Retention:** Web3 wallet integration operates strictly metadata-only. Private keys and recovery phrases are never stored or requested by the software.

## Security Audit Status
- **Files Scanned:** 594 project files
- **Detected Secrets / Credentials:** 0
- **License Incompatibilities:** 0 (Permissive MIT/Apache-2.0 core only)
- **Status:** Release Candidate RC1 Hardened

## Contact for Security or Acquisition Inquiries
Founder & Lead Architect  
📧 `chitara.trading@proton.me`
