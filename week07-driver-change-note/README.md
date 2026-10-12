## Scenario:

A driver failure was put onto the machine through a .ps1 file provided by the instructor. Your task is to document everything about the driver error including the error codes, hardware IDs, details tab for identifying the exact device, driver date, driver version, driver provider, and if rollback is available or not.

You are then instructed to document the before state and then write a document including your findings, fix you will employ, why this fix specifically, and the expected outcome. You will then employ the fix and document a rollback plan if things stop working in the future.

## Tools Used:
- Powershell
- VMware Workstation
- Git

## Steps Taken:
- Run the powershell command to cause a driver failure.
- Document the specifications of the driver failure such as:
    - Error Code
    - Hardware IDs
    - Exact device in details tab
    - Driver Date
    - Driver Version
    - Driver Previdor
    - Is rollback available
- Document before state and save it as a file for proof.
- Document a change note that includes:
    - The before state and info
    - Fix you will employ
    - Why this fix
    - Expected Outcome
- Employ fix
- Document after state
- Document rollback plan

## Evidence List:
- All .md files listed in this folder
- week7 steps1-6 screenshots of device
- all .ps1 files used within the VM to simulate and test a driver failure
