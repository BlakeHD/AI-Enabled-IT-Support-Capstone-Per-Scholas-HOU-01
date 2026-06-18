# Phase 2 – Migration Event

# Introduction

## Purpose

The purpose of Phase 2 is to execute a centrally approved migration package within the project environment and document the execution process.

During this phase, my responsibility is to follow approved procedures, execute the migration package exactly as instructed, and document the resulting system state without performing investigation, troubleshooting, remediation, rollback activities, or analysis.

As the assigned IT Support Technician, my role is to ensure that approved changes are implemented according to established operational procedures while maintaining accurate records of the migration event.

## Change Management Context

Migration activities in enterprise environments must follow established change-management processes. Unauthorized modifications, analysis, or corrective actions can introduce additional variables that complicate future troubleshooting and recovery efforts.

To maintain the integrity of the migration event, I executed the migration package exactly as provided and documented only the execution process and immediate system observations.

---

# Phase Objectives

The objectives of this phase are to:

* Execute the approved migration package
* Verify successful execution
* Record execution details
* Document immediate post-execution observations
* Preserve the environment for future incident investigation activities

## Completion Checklist

* [ ] Migration package executed
* [ ] Executed only once
* [ ] Executed on MIG-SRV01
* [ ] Executed using Run as Administrator
* [ ] No remediation performed
* [ ] Environment remains operational

---

# Migration Event Overview

## Server Information

| Item             | Value               |
| ---------------- | ------------------- |
| Server Name      | MIG-SRV01           |
| Domain           | migration.local     |
| Operating System | Windows Server 2022 |

## Migration Package Information

| Item                    | Value              |
| ----------------------- | ------------------ |
| Script Name             | *To Be Documented* |
| Date Received           | *To Be Documented* |
| Source                  | *To Be Documented* |
| Execution Authorization | *To Be Documented* |

---

# Server & Account Verification

Prior to executing the migration package, I verified that I was logged into the correct system using an authorized administrative account.

This verification helps ensure that changes are applied to the intended environment and supports auditability throughout the migration process.

## Verification Details

| Validation Item                     | Status  |
| ----------------------------------- | ------- |
| Correct Server Identified           | Pending |
| Authorized Account Verified         | Pending |
| Administrative Privileges Confirmed | Pending |

### Verification Commands

```powershell
hostname
whoami
```

### Evidence

![Server Verification](../screenshots/phase2/P2-00-Server-Verification.png)

*Figure 1: Verification of server identity and execution account prior to migration execution.*

---

# Pre-Execution Verification

Before executing the migration package, I verified that all required prerequisites were satisfied.

## Verification Checklist

* [ ] Server operational
* [ ] Logged into MIG-SRV01
* [ ] PowerShell launched as Administrator
* [ ] Migration package available
* [ ] No modifications made to package
* [ ] No previous execution performed

### Evidence

![PowerShell Elevated Session](../screenshots/phase2/P2-01-Elevated-PowerShell.png)

*Figure 2: Elevated PowerShell session prepared for migration execution.*

### Notes

> Record any observations made prior to execution.

---

# Migration Script Execution

## Execution Details

| Item             | Value                             |
| ---------------- | --------------------------------- |
| Date             | *To Be Documented*                |
| Time             | *To Be Documented*                |
| User Account     | *To Be Documented*                |
| Server           | MIG-SRV01                         |
| Execution Method | PowerShell (Run as Administrator) |

## Execution Command

```powershell
# Insert migration execution command here
```

## Command Output

```powershell
# Insert execution output here
```

### Evidence

![Migration Script Execution](../screenshots/phase2/P2-02-Migration-Execution.png)

*Figure 3: Migration package execution in progress.*

### Notes

> Record execution details, timestamps, and console output.

---

# Execution Confirmation

Following execution, I verified that the migration package completed successfully and that the environment remained operational.

## Validation Status

| Validation Item         | Status  |
| ----------------------- | ------- |
| Script Started          | Pending |
| Script Completed        | Pending |
| Errors Observed         | Pending |
| Environment Operational | Pending |

### Evidence

![Migration Completion](../screenshots/phase2/P2-03-Migration-Completion.png)

*Figure 4: Migration completion confirmation.*

### Completion Notes

> Record completion messages, timestamps, and validation details.

---

# Change Management & Operational Compliance

Successful IT operations require more than technical execution. They depend on adherence to operational controls, change-management procedures, documentation standards, and environment preservation practices.

Throughout this migration event, I executed the approved migration package within the authorized scope of work while maintaining procedural consistency, accountability, and traceability.

## Change Management Compliance

| Control Objective             | Validation Method                                     |
| ----------------------------- | ----------------------------------------------------- |
| Execute approved changes only | Migration package executed as provided                |
| Maintain change integrity     | No modifications made                                 |
| Follow approved procedures    | Execution performed according to project requirements |
| Maintain accountability       | Execution details and timestamps documented           |
| Preserve environment state    | Environment maintained for future investigation       |

### Compliance Verification

* [ ] Approved migration procedure followed
* [ ] Migration package executed without modification
* [ ] Execution performed within approved scope
* [ ] Change activity documented

---

## Operational Controls

| Operational Standard                        | Verification                               |
| ------------------------------------------- | ------------------------------------------ |
| System readiness confirmed                  | Pre-execution verification completed       |
| Administrative execution standards followed | Elevated PowerShell session utilized       |
| Execution details recorded                  | Date, time, account, and server documented |
| Environment status monitored                | Post-execution observations recorded       |
| Documentation maintained                    | Evidence and execution records preserved   |

### Compliance Verification

* [ ] Pre-execution verification completed
* [ ] Administrative standards followed
* [ ] Execution details documented
* [ ] Environment status recorded

---

## Rules of Engagement & Environment Preservation

To preserve the integrity of the migration event, I intentionally avoided activities that could alter the post-migration state of the environment.

All actions performed during this phase remained within the approved migration scope and were documented to maintain accountability, traceability, and operational consistency.

### Compliance Verification

| Requirement                       | Status  |
| --------------------------------- | ------- |
| No script inspection performed    | Pending |
| No script modifications performed | Pending |
| No troubleshooting performed      | Pending |
| No remediation performed          | Pending |
| No rollback performed             | Pending |
| No baseline comparison performed  | Pending |
| Migration executed once           | Pending |
| Environment preserved for Phase 3 | Pending |

---

# Evidence & Screenshots

## Evidence Inventory

### Server Verification

![Screenshot Placeholder](../screenshots/phase2/P2-00-Server-Verification.png)

---

### Elevated PowerShell Session

![Screenshot Placeholder](../screenshots/phase2/P2-01-Elevated-PowerShell.png)

---

### Migration Execution

![Screenshot Placeholder](../screenshots/phase2/P2-02-Migration-Execution.png)

---

### Migration Completion

![Screenshot Placeholder](../screenshots/phase2/P2-03-Migration-Completion.png)

---

### Execution Timestamp

![Screenshot Placeholder](../screenshots/phase2/P2-05-Execution-Timestamp.png)

---

### Post-Execution System State

![Screenshot Placeholder](../screenshots/phase2/P2-04-Post-Execution-State.png)

---

### Execution Authorization

![Screenshot Placeholder](../screenshots/phase2/P2-06-Execution-Authorization.png)

---

# Immediate Post-Execution Observations

This section records the system state immediately following migration execution.

Observations are documented without analysis, troubleshooting, remediation, or investigation.

## Observations

### Observation 1

> To Be Documented

### Observation 2

> To Be Documented

### Observation 3

> To Be Documented

Examples:

* Server remained operational
* PowerShell execution completed
* Services remained running
* No unexpected shutdown occurred

### Evidence

![Post Execution State](../screenshots/phase2/P2-04-Post-Execution-State.png)

*Figure 5: System state immediately following migration execution.*

---

# Migration Event Summary

During Phase 2, I executed the approved migration package on MIG-SRV01 using an elevated PowerShell session.

The migration package was executed exactly one time according to approved procedures. No modifications were made to the package, and no troubleshooting, remediation, rollback, or investigative activities were performed.

Execution details, timestamps, validation results, and supporting evidence were documented to maintain accountability and traceability throughout the migration process.

The environment was preserved in its post-migration state to support future incident investigation and recovery activities.

## Summary Checklist

* [ ] Migration executed successfully
* [ ] Execution documented
* [ ] Environment operational
* [ ] No remediation performed
* [ ] Environment preserved for Phase 3

---

# Phase 2 Conclusion

During Phase 2, I successfully executed the approved migration package according to established operational procedures and project requirements.

The migration activity was completed within the approved scope of work and documented to maintain operational traceability, accountability, and readiness for subsequent incident response activities.

In accordance with project requirements, I did not inspect, modify, troubleshoot, remediate, or reverse any changes introduced by the migration package. The environment remains preserved in its post-migration state and is ready for Phase 3: Incident Response & Investigation.
