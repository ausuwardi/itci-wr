---
layout: cover
background: >-
  https://images.unsplash.com/photo-1543251881-a8ceb0a50d06?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80
colorSchema: light
title: Weekly Update 17 March 2022
---

# Weekly Update 23 March 2022

Agustianes


---

# OpenShift

Project

```mermaid
gantt
    title OpenShift
    dateFormat YYYY-MM-DD
    excludes weekends
    axisFormat %d-%b

    section PoC
    Prerequisites :active, a1, 2022-03-14,5d
    Cluster setup :        a2, 2022-03-21, 2022-04-04
    PoC scenario  :        a3, after a2, 1w

    section Production
    Quotation :b1, 2022-03-17, 3d
    PO        :b2, 2022-04-11, 1w
```

---

# OpenShift

Project

This Week:
- Detailed list of requirements
- VM setup
- Create web-app deployment for PoC

Next:
- Get all VM ready [18 March 2022]
- Setup DNS ocp.pti-cosmetics.com [20 March 2022]
- Quotation

---

# Racoon

Operation

This Week:
- Support troubleshoot dask worker unable to upload to S3

Next:
- Fix supervisor process configuration in Worker Server

---

# Tableau

Operation

This Week:
- Troubleshoot node 3 ZFS pool problem

Next:
- Investigate systemctl failure when restarting tableau services

<!--
Cek memory usage ZFS. Ada set limit 16 atau berapa di file zfsconf.
-->

---

# EFaktur

Operation

This Week:
- Troubleshoot running backup server at PC Mba Irsya
- Test preparation for PPN change to 11%

---

# Redash

Operation

This Week:
- Setup Redash Commercial
    - Clone from Redash production
    - Setup DNS & reverse proxy
    - Add Zabbix host

<!--
Rethink deployment: cluster?
-->

---

# Others

Ad-Hoc:
- Support troubleshoot ERP toolbox script

Others:
- Portal content submission

---

# Time Consumed

- Project: 30%
- Operation: 60%
- Ad-Hoc: 10%

---
layout: center
---

# Thank You
