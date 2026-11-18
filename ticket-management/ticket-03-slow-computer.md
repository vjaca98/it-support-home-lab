
# INC-003: Computer Running Slowly

## 1. Ticket Information

- **Ticket ID:** INC-003
- **Category:** Desktop Support
- **Priority:** Medium
- **Status:** Investigation Completed
- **Environment:** Windows 11

## 2. Problem Description

A simulated employee reports that their computer is running slowly and applications take longer than usual to respond.

## 3. Initial Investigation

Task Manager was used to review system resource utilization.

### Initial Observations

- CPU usage: Low
- Memory usage: Medium
- Disk usage: Low
- Computer performance: Normal

No unusual resource consumption was identified.

## 4. Detailed Troubleshooting

### A. Task Manager

- Reviewed running processes.
- Sorted processes by CPU and memory usage.
- No application showed unusually high resource consumption.

### B. Startup Applications

- Reviewed applications under Autostart-Apps.
- Most applications showed low startup impact.
- No obvious startup-related performance issue was identified.

### C. Resource Monitor

- Opened Resource Monitor using the `resmon` command.
- Explored CPU, Memory, Disk and Network monitoring.
- Observed Google Chrome as an active application.
- No confirmed performance issue was identified.

## 5. Findings

The computer was responsive during the investigation.

CPU and disk utilization were low, while memory usage was moderate.

No unusually resource-intensive application or significant startup impact was identified.

Google Chrome was observed running, but there was insufficient evidence to identify it as the cause of the reported issue.

## 6. Root Cause

Undetermined.

The reported performance issue could not be reproduced during testing.

Further investigation would be necessary if the employee continues to experience slow performance.

## 7. Recommended Next Steps

If the issue occurs again:

1. Ask the user when the performance problem occurs.
2. Identify which applications are affected.
3. Check CPU, RAM and disk utilization while the issue is happening.
4. Review Windows updates and available disk space.
5. Check Windows Event Viewer for relevant system errors.
6. Escalate to the appropriate IT team if the issue persists.

## 8. Final Result

**Investigation:** Completed

**Resolution:** No performance issue was reproduced during testing.

No system settings or processes were modified.

## 9. Skills Demonstrated

- Windows 11 troubleshooting
- Task Manager
- Resource Monitor
- CPU and RAM monitoring
- Disk utilization
- Startup application investigation
- Process monitoring
- Technical documentation

---

*Note: This is a fictional IT support scenario. Diagnostic exercises were performed on a personal Windows 11 computer. No system processes or startup settings were modified.*
