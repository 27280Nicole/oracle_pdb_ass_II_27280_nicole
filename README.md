# oracle_pdb_ass_II_27280_nicole
# Oracle Pluggable Database Assignment II

## Student Information
 -**Name:** Nicole Umutoniwase
 -**Student ID:** 27280
 -**Course:** INSY 8311 - Database Development with PL/SQL
 -**Assignment:**  Oracle Pluggable Databases(PDB) Management


## Repository Link
[https://github.com/27280Nicole/oracle_pdb_ass_II_27280_nicole/edit/main/README.md]


## Oracle Environment Used
- Oracle Database 21c Enterprise Edition
- SQL*Plus
- Oracle Enterprise Manager (OEM)
- Windows Operating System

## Task 1: Create a New Pluggable Database

### PDB Name Created:
ni_pdb_27280

### Username Created:
nicole_plsqlauca_27280

### Description:
- Created a new Pluggable Database using required naming conventions.
- Opened the PDB in READ WRITE mode.
- Created a dedicated user inside the PDB.
- Granted necessary privileges (CONNECT, RESOURCE).

<img width="1101" height="855" alt="pdb creation command" src="https://github.com/user-attachments/assets/40ae13c3-4c92-4487-9749-059d87e0896f" />
<img width="1102" height="973" alt="PDB OPEN" src="https://github.com/user-attachments/assets/822b5568-be9f-4999-afc4-06decacbf8d7" />
<img width="1108" height="950" alt="user created" src="https://github.com/user-attachments/assets/8e86b032-0777-4dc7-969d-3d8c03e2222d" />
<img width="963" height="826" alt="user" src="https://github.com/user-attachments/assets/2295128b-2134-470a-a74b-0b84a74967cf" />


## Task 2: Create and Delete a Temporary PDB

### Temporary PDB Name:
ni_to_delete_pdb_27280

### Description:
- Created a temporary PDB.
- Verified its existence using V$PDBS.
- Closed the PDB.
- Dropped it completely using INCLUDING DATAFILES.
- Confirmed it no longer exists.

<img width="1130" height="922" alt="ni_delete creation" src="https://github.com/user-attachments/assets/94e5eeba-485f-407b-bd67-1c3bfc08031b" />
<img width="1047" height="962" alt="drop" src="https://github.com/user-attachments/assets/f9b582cb-0224-4c07-ac7d-16018d5c5ca5" />


## Task 3: Oracle Enterprise Manager (OEM)

 Configured OEM HTTPS port.
 Accessed OEM via https://localhost:5500/em
 Verified:
 Oracle 21c Environment
 ni_pdb_27280 visible
 User nicole_plsqlauca_27280 visible

<img width="1908" height="917" alt="oracle" src="https://github.com/user-attachments/assets/799f272b-7a9a-4757-aa4c-61841717f4c8" />
<img width="1905" height="546" alt="table" src="https://github.com/user-attachments/assets/fe9f490c-9c1b-41f4-b3cd-e3f201398c1f" />


## Challenges Encountered

Minor issue encountered:
ORA-65020 (PDB already closed)

Solution:
 Confirmed PDB state using V$PDBS
 Proceeded directly with DROP PLUGGABLE DATABASE

Issues Encountered: No major issues

## Integrity Statement

I hereby confirm that this work is entirely my own.  
All tasks were performed independently following assignment guidelines.  
I understand that academic integrity and professionalism are essential in database administration.


Excellence is never an accident; it is the result of discipline, commitment, and integrity.
