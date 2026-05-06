# Troubleshooting (Day 6)

## Scenario 1: High CPU Usage

### Check
top

### Action
Identify process → kill

---

## Scenario 2: Disk Full

### Check
df -h

### Action
Remove unnecessary files

---

## Scenario 3: Service Not Working

### Check logs
cat /var/log/syslog

---

## My Understanding

Troubleshooting is step-by-step problem solving.

## SRE Insight

This is the core of SRE:
- identify issue
- analyze
- fix
- prevent