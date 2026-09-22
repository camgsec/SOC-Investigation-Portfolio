# RDP Compromise and Host Discovery

> **SOC Investigation | LetsDefend Lab | True Positive | Contained**

This investigation involved an initially low-severity system discovery alert that led to the identification of successful unauthorized RDP access and post-compromise reconnaissance on a Windows endpoint.

---

## Case Summary

| Field | Details |
|---|---|
| **Alert** | SOC291 – System Time Lookup Detected |
| **Affected Host** | Campbell |
| **Affected IP** | `172.16.17.213` |
| **Operating System** | Windows 10 |
| **Source IP** | `37.19.221.238` |
| **Compromised Account** | `LetsDefend` |
| **Access Method** | RDP / TCP 3389 |
| **Classification** | True Positive |
| **Response** | Endpoint Contained |

---

## Executive Summary

An investigation was initiated following a detection for system time discovery on endpoint **Campbell (`172.16.17.213`)**.

The triggering command was:

```cmd
net time \\EC2AMAZ-ILGVOIN
