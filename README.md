# Oracle Pluggable Databases Assignment II

## Student Information
- Name: Dave
- Student ID: 28966
- Course: Database Development with PL/SQL (INSY 8311)
- Instructor: Eric Maniraguha

---

## Oracle Environment Used
- Oracle Database Version: 19c
- Tool Used: SQL*Plus
- Operating System: Windows
- OEM: EM Express (Browser-based)

---

## Task 1: Create a New Pluggable Database

Created PDB:
GI_PDB_28966

Created Admin User:
dave_plsqlauca_28966

Steps Performed:
- Connected as SYSDBA
- Created PDB using CREATE PLUGGABLE DATABASE
- Opened the PDB
- Saved state
- Switched container
- Verified user login

Screenshots provided as evidence.

---

## Task 2: Create and Delete a Temporary PDB

Temporary PDB Name:
GI_TO_DELETE_PDB_28966

Steps Performed:
- Created temporary PDB
- Opened and verified existence
- Closed PDB
- Dropped PDB including datafiles
- Verified deletion using SHOW PDBS

Screenshots provided as evidence.

---

## Task 3: Oracle Enterprise Manager (OEM)

- Accessed EM Express via browser
- Verified PDB GI_PDB_28966 exists
- Verified user dave_plsqlauca_28966 exists
- Captured dashboard screenshots

---

## Challenges Faced

- SQL*Plus connection errors (ORA-12154, ORA-01017)
- Listener service issues
- PATH conflicts with multiple Oracle installations

Solutions:
- Used Easy Connect syntax
- Verified services in Windows
- Adjusted PATH to correct Oracle 19c home

---

## Integrity Statement

I confirm that this assignment was completed individually.
All commands were executed by me and all screenshots are from my own environment.
