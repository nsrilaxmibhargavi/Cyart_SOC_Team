# Evidence Analysis

## Tool Used
netstat

## Findings

| Protocol | Local Address | State | Process |
|----------|--------------|------|--------|
| TCP | 127.0.0.1 | ESTABLISHED | svchost.exe |
| TCP | 0.0.0.0 | LISTENING | System |

## Practical Explanation
Network connections were analyzed using netstat to identify suspicious activity.

## Conclusion
Most connections were internal and normal.
