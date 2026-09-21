hr-staff-test: access test results for Payroll folder

predicted outcomes:
read: allow
edit: allow
delete: deny
access security: deny

actual outcomes:
read: allow
edit: allow
delete: deny
access security: deny

comparison:
predicted matches actual
no discrepancies found

proof:
week04step4create-proof
week04step4edit-proof
week04step4delete-proof
week04step4security-proof

| | HR-Managers | HR-Staff | Audit-Readonly |
| --- | --- | --- | --- |
| Read | X | X | X |
| Edit | X | X | - |
| Delete | X | - | - |
| Security | X | - | - |
