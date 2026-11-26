# OT Incident Response and Recovery Considerations

## OT-specific priorities
Incident response in OT must consider personnel safety, environmental protection, process stability and operational continuity. IT containment actions must not be applied blindly to control environments.

## Preparation
- Maintain an approved asset inventory and network-zone model.
- Identify process owners, control engineers, safety personnel and incident decision-makers.
- Define safe escalation and out-of-band communications.
- Keep approved recovery media, configuration backups and vendor support arrangements.
- Exercise scenarios in an isolated simulator or tabletop environment.

## Detection and triage
- Correlate network, endpoint, identity and process alarms.
- Preserve logs and evidence using approved procedures.
- Distinguish cyber indicators from equipment faults and process anomalies.
- Escalate suspected impact to safety and operations authorities.

## Containment decision
Before isolating, shutting down or changing an OT asset, assess operational and safety consequences with authorized OT engineering and site leadership. Prefer pre-approved, process-aware containment actions.

## Recovery
- Restore from known-good, validated configurations and backups.
- Verify controller logic and engineering change integrity through authorized procedures.
- Validate process safety interlocks and operational state.
- Confirm monitoring, communications and operator visibility.
- Obtain formal operational acceptance before returning to normal service.

## Lessons learned
Document timeline, decisions, affected zones, root causes, recovery evidence, safety implications and corrective actions. Never publish sensitive process data or incident details from a real facility.
