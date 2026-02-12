# Attack Scenario Model

## Phase 1 – Initial Compromise

- Exploitation of CI/CD pipeline misconfiguration
- Stolen developer API key
- Malicious DLL inserted into update package

## Phase 2 – Distribution

- Signed update deployed automatically
- No integrity anomaly detected
- Endpoint trust chain not validated beyond signature

## Phase 3 – Activation

Payload executes beacon:

- C2 over HTTPS
- Delayed execution
- Host profiling

## Phase 4 – Targeted Escalation

- Domain discovery
- Credential harvesting
- Lateral movement

## Phase 5 – Impact

- Selective encryption of critical servers
- Data exfiltration
- Extortion communication
