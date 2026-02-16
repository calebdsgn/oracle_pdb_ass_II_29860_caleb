# Oracle Pluggable Database Assignment II

**Student:** CALEB UWAMBAJE  
**Student ID:** 29860

## Overview
This assignment demonstrates the creation, management, and deletion of Oracle Pluggable Databases (PDB) in a Container Database (CDB) architecture.

## Oracle Environment
- **Oracle Version:** [e.g., Oracle 19c]
- **Operating System:** Windows 11 Pro

## Task 1: Create Permanent PDB
**PDB Name:** ca_pdb_29860
**Username:** caleb_plsqlauca_29860

### Process:
1. Connected to CDB as SYSDBA
2. Created PDB with specified naming convention
3. Created admin user inside PDB
4. Opened PDB and verified status

### Screenshots:
 Connected to CDB as SYSDBA
<img width="1309" height="217" alt="pluggable" src="https://github.com/user-attachments/assets/6585df28-6df9-4163-947b-a6014065c194" />

 Created PDB with specified naming convention
<img width="783" height="659" alt="show" src="https://github.com/user-attachments/assets/e46c9518-8ba9-4136-bb3e-d899bc7ae0c9" />

Created admin user inside PDB

<img width="1225" height="547" alt="user" src="https://github.com/user-attachments/assets/adbd9249-5988-4922-beac-6dc2300fcd3b" />

## Task 2: Create and Delete Temporary PDB
**Temporary PDB Name:** ca_to_delete_pdb_29860

### Process:
1. Created temporary PDB
2. Verified existence
3. Closed PDB
4. Dropped PDB including datafiles
5. Confirmed successful deletion
   

### Screenshots:

Created temporary PDB
<img width="921" height="367" alt="new pluggable" src="https://github.com/user-attachments/assets/c7807179-7315-4eac-83b4-4bdc91c0033b" />

PDB deletion Commands and results 
<img width="1173" height="573" alt="drop plugable" src="https://github.com/user-attachments/assets/1fe6970f-96c1-44aa-bdc9-4fb0da30768e" />

## Task 3: Oracle SQL Developer
Configured Oracle SQL Developer to connect to both the Container Database (CDB) and the created Pluggable Database (PDB).

### Configuration:
- **CDB Connection:** Successfully established
- **PDB Connection:** Connected as [YourFirstName]_plsqlauca_[StudentID]
- **PDB Status:** READ WRITE mode confirmed

### Verification Queries:
1. Listed all PDBs in the container
2. Verified user account in the PDB
3. Confirmed connection context

### Screenshots:
<img width="997" height="985" alt="developer" src="https://github.com/user-attachments/assets/bf35b94a-f7d6-473a-994b-1e7fca97f846" />
<img width="629" height="643" alt="sys context" src="https://github.com/user-attachments/assets/8d8dd5fe-cab4-4b52-9145-64f9bbd36773" />

## Challenges Encountered
OEM not available on Oracle 23ai Free,	Used Oracle SQL Developer 24.3.1 as dashboard alternative

## Integrity Statement
I certify that this work is my own and was completed in accordance with academic integrity policies. All screenshots are authentic and represent work performed by me.

---

**Repository Link:** https://github.com/calebdsgn/oracle_pdb_ass_II_29860_caleb/edit/main/README.md
