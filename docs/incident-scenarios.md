# Incident Scenarios

## Scenario 1: Cooling Failure (Zone B)

**Detection:**  
Monitoring alert triggered due to temperature exceeding threshold (85°F)

**Impact:**  
Risk of server overheating and hardware damage

**Response:**
- Alert acknowledged within 5 minutes
- Workload redistributed to adjacent zones
- Technician dispatched
- Cooling unit inspected

**Resolution:**  
Blocked airflow panel identified and cleared

**Metrics:**
- Time to detect: 2 minutes
- Time to resolve: 45 minutes

**Root Cause:**  
Improper rack airflow management

**Prevention:**  
Weekly airflow inspection added to maintenance checklist

---

## Scenario 2: Power Fluctuation

**Detection:**  
UPS system alert indicating unstable input voltage

**Impact:**  
Risk of system shutdown or hardware damage

**Response:**
- Load transferred to backup UPS
- Electrical system inspected
- Generator readiness verified

**Resolution:**  
Faulty power distribution unit identified and replaced

**Metrics:**
- Time to detect: 1 minute
- Time to resolve: 60 minutes

**Root Cause:**  
Aging power distribution hardware

**Prevention:**  
Monthly load testing and equipment lifecycle tracking implemented

---

## Scenario 3: Network Latency / Packet Loss

**Detection:**  
Monitoring system flagged abnormal latency increase

**Impact:**  
Degraded service performance

**Response:**
- Network traffic analyzed
- Faulty switch isolated
- Traffic rerouted

**Resolution:**  
Firmware issue identified and patched

**Metrics:**
- Time to detect: 3 minutes
- Time to resolve: 30 minutes

**Root Cause:**  
Outdated firmware

**Prevention:**  
Quarterly firmware review cycle implemented
