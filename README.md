# Netdata Monitoring – Analyst Project

## 🎯 Objective
Use Netdata (Docker) to monitor system performance metrics including CPU, memory, disk, and running containers.

## 🐳 How to Run Netdata

```bash
docker run -d \
  --name=netdata \
  -p 19999:19999 \
  --cap-add SYS_PTRACE \
  --security-opt apparmor=unconfined \
  netdata/netdata


# netdata_monitoring
