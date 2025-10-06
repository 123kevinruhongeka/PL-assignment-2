Name:Kevin Ruhongeka
ID: 27168

    Oracle Pluggable Database (PDB) Management Assignment
     Project Overview
This assignment demonstrates practical Oracle Database Administration skills focusing on Oracle Multitenant Architecture. The project involves creating and managing Pluggable Databases (PDBs), user administration, and Oracle Enterprise Manager configuration.

    Objectives
- Master Pluggable Database (PDB) creation and lifecycle management
- Configure user accounts with appropriate privileges
- Implement Oracle Enterprise Manager for database monitoring
- Demonstrate proficiency in Oracle Multitenant architecture

## 🛠 Tasks Completed

### Task 1: Permanent PDB Creation
**Objective**: Create a dedicated PDB for coursework storage

    Implementation:
- Created PDB
- User Account
- Privileges Granted: 
  - CONNECT, RESOURCE, DBA roles
  - UNLIMITED TABLESPACE privilege
- Configuration: Auto-open on database startup
- Verification: Confirmed through data dictionary views (`v$pdbs`, `dba_users`)

### Task 2: PDB Lifecycle Management
**Objective**: Demonstrate complete PDB lifecycle from creation to deletion

    Implementation:
- Created temporary PDB
- Admin user setup and verification
- PDB operations performed:
  - Creation and opening
  - Status verification
  - Closing and dropping with datafile cleanup
- Final verification of remaining PDBs

 Task 3: Oracle Enterprise Manager Express Configuration 
 Objective: Set up and configure OEM for database monitoring

     Implementation:
- Configured HTTPS port 5500 for EM Express
- Dashboard access as SYSDBA
- Verified components:
  - PDB status monitoring
  - User account visibility
  - Security configurations
  - PDB details accessibility

