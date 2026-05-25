# Access Application Summary

## Overview

| Category | Count |
| --- | --- |
| Forms | 0 |
| Subforms | 0 |
| Tables | 16 |
| Querys | 0 |
| Modules | 1 |
| Controls | 0 |
| Events | 0 |
| Procedures | 0 |
| Macros | 0 |

## Data Model

### CUSTOMER (6,046 records)

| Field | Type |
|-------|------|
| CID | Long Integer |
| Title | Text |
| Fname | Text |
| Lname | Text |
| Company | Text |
| Street1 | Text |
| City | Text |
| State | Text |
| Zip | Text |
| Source | Text |
| Map | Text |
| Grid | Text |
| Phone | Text |
| Fax | Text |
| Evening Phone | Text |
| Customer Note | Memo |
| Referance | Boolean |
| Cell Phone | Text |
| E-Mail | Memo |
| Tax Exempt | Boolean |
| Wood Chips | Boolean |
| Firewood | Boolean |

### DESCRIPTION (83 records)

| Field | Type |
|-------|------|
| DID | Long Integer |
| Descriptoin | Text |

### EVENT (8,633 records)

| Field | Type |
|-------|------|
| OID | Long Integer |
| Line No | Long Integer |
| Event_No | Double |
| Event_Date | Date/Time |
| Prod Type | Text |
| Completed | Boolean |
| Complete_Date | Date/Time |
| To Bill | Boolean |
| Billed | Boolean |
| Bill_Date | Date/Time |
| Event Price | Currency |
| Paid Date | Date/Time |
| Price | Currency |
| Paid Total | Currency |
| Total Order Price | Currency |
| Total Order Tax | Currency |
| Total Order | Currency |
| Total Accepted Price | Currency |
| Total Accepted Tax | Currency |
| Total Accepted | Currency |
| Paid in full | Boolean |
| Days Outstanding | Long Integer |
| Billed 2 | Boolean |
| Billed 3 | Boolean |
| Billed 4 | Boolean |
| Bill_Date 2 | Date/Time |
| Bill_Date 3 | Date/Time |
| Bill_Date 4 | Date/Time |
| Invoice note | Text |
| Gallonage | Long Integer |
| Invoice_Id | Long Integer |

### LOCATION (113 records)

| Field | Type |
|-------|------|
| Location | Text |

### ORDER (917 records)

| Field | Type |
|-------|------|
| OID | Long Integer |
| CID | Long Integer |
| Order | Boolean |
| Proposal Date | Date/Time |
| Accept Date | Date/Time |
| Work Street | Text |
| Work City | Text |
| Work State | Text |
| Work Zip | Text |
| Paid Amount | Currency |
| Job Note | Text |
| Office Note | Memo |
| Annual Contract | Boolean |
| Work Name | Text |
| Work Map | Long Integer |
| Work Grid | Text |
| Winter Work | Boolean |
| 2025 Accepted | Boolean |
| 2024 Accepted | Boolean |
| 2023 Accepted | Boolean |
| 2022 Accepted | Boolean |
| 2021 Accepted | Boolean |
| 2020 Accepted | Boolean |
| 2019 Accepted | Boolean |
| 2018 Accepted | Boolean |
| 2017 Accepted | Boolean |
| 2016 Accepted | Boolean |
| 2015 Accepted | Boolean |
| 2014 Accepted | Boolean |
| 2013 Accepted | Boolean |
| 2012 Accepted | Boolean |
| 2011 Accepted | Boolean |
| 2010 Accepted | Boolean |
| 2009 Accepted | Boolean |
| 2008 Accepted | Boolean |
| 2007 Accepted | Boolean |
| 2006 Accepted | Boolean |
| 2005 Accepted | Boolean |
| PrePaid Disc Given | Currency |
| Write-Off Given | Currency |
| Pd Amt 1 | Currency |
| Pd Amt 2 | Currency |
| Pd Amt 3 | Currency |
| Pd Amt 4 | Currency |
| Pd Amt 5 | Currency |
| Pd Amt 6 | Currency |
| Pd Date 1 | Date/Time |
| Pd Date 2 | Date/Time |
| Pd Date 3 | Date/Time |
| Pd Date 4 | Date/Time |
| Pd Date 5 | Date/Time |
| Pd Date 6 | Date/Time |
| Ck # 1 | Long Integer |
| Ck # 2 | Long Integer |
| Ck # 3 | Long Integer |
| Ck # 4 | Long Integer |
| Ck # 5 | Long Integer |
| Ck # 6 | Long Integer |
| Service Declined | Boolean |

### ORDER DETAIL (7,550 records)

| Field | Type |
|-------|------|
| OID | Long Integer |
| Line No | Long Integer |
| Prod Type | Text |
| Location | Text |
| Plant | Text |
| Description | Text |
| Pest | Text |
| Start | Date/Time |
| Price | Currency |
| 25 Price | Currency |
| 24 Price | Currency |
| 23 Price | Currency |
| 22 Price | Currency |
| 21 Price | Currency |
| 20 Price | Currency |
| 19 Price | Currency |
| 18 Price | Currency |
| 17 Price | Currency |
| 16 Price | Currency |
| 15 Price | Currency |
| 14 Price | Currency |
| 13 Price | Currency |
| 12 Price | Currency |
| 11 Price | Currency |
| 10 Price | Currency |
| 09 Price | Currency |
| 08 Price | Currency |
| 07 Price | Currency |
| Accept | Boolean |
| 25 Accepted | Boolean |
| 24 Accepted | Boolean |
| 23 Accepted | Boolean |
| 22 Accepted | Boolean |
| 21 Accepted | Boolean |
| 20 Accepted | Boolean |
| 19 Accepted | Boolean |
| 18 Accepted | Boolean |
| 17 Accepted | Boolean |
| 16 Accepted | Boolean |
| 15 Accepted | Boolean |
| 14 Accepted | Boolean |
| 13 Accepted | Boolean |
| 12 Accepted | Boolean |
| 11 Accepted | Boolean |
| 10 Accepted | Boolean |
| 09 Accepted | Boolean |
| 08 Accepted | Boolean |
| 07 Accepted | Boolean |
| Accepted Date | Date/Time |
| CrewID | Text |
| ScheduleDate | Date/Time |
| ScheduleReady | Boolean |
| Priority | Text |
| LargeTree | Boolean |
| TreatmentID | Long Integer |

### ORDERrestored (1,913 records)

| Field | Type |
|-------|------|
| OID | Long Integer |
| CID | Long Integer |
| Order | Boolean |
| Proposal Date | Date/Time |
| Accept Date | Date/Time |
| Work Street | Text |
| Work City | Text |
| Work State | Text |
| Work Zip | Text |
| Paid Amount | Currency |
| Job Note | Text |
| Annual Contract | Boolean |
| Work Name | Text |
| Work Map | Long Integer |
| Work Grid | Text |
| Winter Work | Boolean |
| 2008 Accepted | Boolean |
| 2007 Accepted | Boolean |
| 2006 Accepted | Boolean |
| 2005 Accepted | Boolean |
| PrePaid Disc Given | Currency |
| Write-Off Given | Currency |
| Pd Amt 1 | Currency |
| Pd Amt 2 | Currency |
| Pd Amt 3 | Currency |
| Pd Amt 4 | Currency |
| Pd Amt 5 | Currency |
| Pd Amt 6 | Currency |
| Pd Date 1 | Date/Time |
| Pd Date 2 | Date/Time |
| Pd Date 3 | Date/Time |
| Pd Date 4 | Date/Time |
| Pd Date 5 | Date/Time |
| Pd Date 6 | Date/Time |
| Ck # 1 | Long Integer |
| Ck # 2 | Long Integer |
| Ck # 3 | Long Integer |
| Ck # 4 | Long Integer |
| Ck # 5 | Long Integer |
| Ck # 6 | Long Integer |

### PEST (215 records)

| Field | Type |
|-------|------|
| Pest | Text |

### PLANT (174 records)

| Field | Type |
|-------|------|
| Plant | Text |

### PRODUCT (11 records)

| Field | Type |
|-------|------|
| Prod Type | Text |
| Prod Desc | Text |

### Paste Errors (1 records)

| Field | Type |
|-------|------|
| Field0 | Memo |

### STATE (14 records)

| Field | Type |
|-------|------|
| State | Text |
| State Name | Text |

### TEMP TABLE1 (13 records)

| Field | Type |
|-------|------|
| Sequence | Double |
| Oid | Long Integer |
| Line | Long Integer |
| Lname | Text |
| Street | Text |
| Map | Long Integer |
| City | Text |
| Grid | Text |
| Phone | Text |
| Location | Text |
| Plant | Text |
| Pest | Text |
| Price | Currency |
| Product | Text |
| Cust info | Text |
| Job Info | Text |
| Company Name | Text |
| Date | Date/Time |
| Prod | Text |
| Operator | Text |

### TREATMENT_DETAIL (233 records)

| Field | Type |
|-------|------|
| TID | Long Integer |
| Line No | Integer |
| Time of Year Start | Date/Time |
| For Pest | Text |

### Titles (13 records)

| Field | Type |
|-------|------|
| Title | Text |

### tblTreatmentIntervals (234 records)

| Field | Type |
|-------|------|
| TreatmentID | Long Integer |
| TreatmentName | Text |
| MinInterval | Long Integer |
| HighPriorityInterval | Long Integer |
| UrgentPriorityInterval | Long Integer |

## Form Hierarchy



## Navigation Flows

_None found._

## Key VBA Procedures (by outgoing CALLS)

_None found._

## Dead Controls (no events, no control source)

_None found._
