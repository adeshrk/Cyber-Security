# Event Summary — Brute Force Detection

| Timestamp | Event Type | Username | Source IP | Description |
|-----------|------------|---------|-----------|-------------|
| 2025-10-05 10:12 | Failed Logon | user1 | 192.168.1.10 | Failed login attempt |
| 2025-10-05 10:12 | Failed Logon | admin | 192.168.1.10 | Failed login attempt |
| 2025-10-05 10:12 | Failed Logon | user2 | 192.168.1.10 | Failed login attempt |

**Observation:** Single IP attempting logins across multiple accounts in rapid succession.  
**Conclusion:** Likely brute-force login attempt; no successful logins observed.
