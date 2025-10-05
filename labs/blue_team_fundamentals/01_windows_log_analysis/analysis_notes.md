# Analysis Notes — Brute Force Detection

## Methodology
- Focused on authentication events (failed vs. successful logins).
- Grouped by username and source IP to identify repetitive patterns.
- Visualized activity over time to detect bursts.
- Compared failures to successes to confirm malicious activity.

## Observations
- Repeated failed logins from one IP suggest brute-force attempts.
- Multiple user accounts targeted in a short time frame.
- Visualization clearly shows spikes corresponding to the attack.

## Next Steps (optional)
- Enrichment: GeoIP or hostname mapping for suspicious IPs
- Correlation: Compare with network logs or alerting platform
- Automation: Integrate detection logic into a SOC pipeline
