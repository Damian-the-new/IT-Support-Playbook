# WiFi Connectivity Issue – Troubleshooting Guide

## Scenario
User reports inability to connect to WiFi network.

---

## Step 1 – Identify Scope

- Is the issue affecting only one user?
- Are other users connected successfully?
- Is the issue isolated to one device?

---

## Step 2 – Basic Checks

- Ensure WiFi is enabled
- Restart device
- Forget and reconnect to network
- Test with Ethernet cable (if available)

---

## Step 3 – Network Diagnostics

Open Command Prompt and run:

- ipconfig /all
- ipconfig /release
- ipconfig /renew
- ipconfig /flushdns

Verify:
- Valid IP address assigned
- Default gateway present
- DNS server configured

---

## Step 4 – Device Manager Check

- Check for network adapter errors
- Update or reinstall driver if required

---

## Step 5 – Router / External Check

- Restart router
- Check if issue persists on other devices

---

## Escalation Criteria

Escalate to Network Team if:

- Multiple users affected
- No IP address assigned after renewal
- Hardware failure suspected
- Router configuration issue identified

---

## Documentation Notes

- Record all actions taken
- Document IP address before and after renewal
- Attach screenshots if required
