# OT Secure Remote Access — Design Considerations

> This is a governance and architecture checklist. It is not a configuration guide for connecting to live industrial systems.

## Principles
- Remote access is disabled by default unless an approved operational need exists.
- Access is attributable to an individual or approved service identity.
- Strong authentication and least privilege are mandatory.
- Sessions are time-bound, approved, monitored and logged.
- Access terminates at a controlled boundary such as an industrial DMZ.
- Direct inbound connectivity to control assets is avoided unless a formally assessed exception exists.

## Governance checklist
- [ ] Business justification and system owner approval recorded
- [ ] OT operations and process-safety review completed
- [ ] Vendor identity and support scope verified
- [ ] MFA and privileged access controls required
- [ ] Session broker/jump host located in approved zone
- [ ] Access limited to approved assets, protocols and time windows
- [ ] Session logging and monitoring assigned
- [ ] Emergency revocation process tested
- [ ] Vendor access reviewed and removed when no longer required
- [ ] Recovery and incident procedures account for remote access failure

## Questions for design review
- What operational task requires remote access?
- Can the task be completed locally or through a safer mediated process?
- Who approves, observes and terminates the session?
- What happens if the remote session is compromised?
- Could the access path affect safety, availability or deterministic operation?

All implementation must follow site policies, vendor guidance, applicable standards and authorized engineering change procedures.
