# Security Policy

The Kyverno community has adopted this security disclosure and response policy to ensure we responsibly handle critical issues.

## Security Response Team

The security response team is responsible for triaging and coordinating fixes for reported vulnerabilities. Team members represent different organizations to ensure independent oversight.

| Name | GitHub | Affiliation |
|------|--------|-------------|
| Jim Bugwadia | [@JimBugwadia](https://github.com/JimBugwadia) | Nirmata |
| Shuting Zhao | [@realshuting](https://github.com/realshuting) | Nirmata |
| Mariam Fahmy | [@MariamFahmy98](https://github.com/MariamFahmy98) | Cloudflare |

The security response team monitors [GitHub private vulnerability reports](https://github.com/kyverno/kyverno/security/advisories), the single reporting channel for potential vulnerabilities. Reports and follow-up discussions are tracked in private GitHub Security Advisory (GHSA) threads.

When a report is received, one team member acts as the coordinator: they acknowledge the report, assess severity, and route the issue to the maintainer best placed to fix it based on the affected component. There is no fixed rotation; the coordinator for a given report is whoever picks it up first through GitHub.

## Security bulletins

For information regarding the security of this project please join our [Slack channel](https://slack.k8s.io/#kyverno).

## Reporting a Vulnerability

### When you should?

- You think you discovered a potential security vulnerability in Kyverno.
- You are unsure how a vulnerability affects Kyverno.
- You think you discovered a vulnerability in another project that Kyverno depends on. For projects with their own vulnerability reporting and disclosure process, please report it directly there.

### When you should not?

- You need help tuning Kyverno components for security - please discuss this in the Kyverno [Slack channel](https://slack.k8s.io/#kyverno).
- You need help applying security-related updates.
- Your issue is not security-related.

### Please use the below process to report a vulnerability to the project:

1. [Report the vulnerability privately through GitHub](https://github.com/kyverno/kyverno/security/advisories/new). GitHub private vulnerability reporting is the single reporting channel for potential vulnerabilities. Keep all follow-up discussion in the private GHSA thread so that the security response team can track the report, coordinate a fix, and plan disclosure in one place.
    * Reports should contain:
        * description of the problem
        * precise and detailed steps (including screenshots) that created the problem
        * the affected version(s)
        * any possible mitigations, if known
    * The security mailing list is no longer used for vulnerability reports. If you previously reported an unresolved issue by email, submit a private GitHub vulnerability report and include the relevant details and prior correspondence to continue the discussion there.
    * Keep vulnerability details private while the security response team investigates and coordinates a fix and disclosure. Do not report potential vulnerabilities in public GitHub issues, pull requests, or Slack channels.
2. The project security team will send an initial response to the disclosure in 3-5 days. Once the vulnerability and fix are confirmed, the team will plan to release the fix in 7 to 28 days based on the severity and complexity.
3. You may be contacted by a project maintainer to further discuss the reported item. Please bear with us as we seek to understand the breadth and scope of the reported problem, recreate it, and confirm if there is a vulnerability present.

## Supported Versions

Kyverno versions follow [Semantic Versioning](https://semver.org/) terminology and are expressed as x.y.z:
- where x is the major version
- y is the minor version
- and z is the patch version

Security fixes are typically addressed in the main branch and may be backported to one prior minor release depending on severity and feasibility. Patch releases are built from prior branches periodically, and may be created on-demand for critical security fixes.
