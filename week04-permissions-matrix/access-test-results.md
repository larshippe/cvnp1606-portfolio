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

Explanation
HR-Managers need full access to the file to make sure everything is working properly and can add files.

Staff only need to read and edit files, they do not need to delete files that admins made for their job.

Audit-Readonly only need to read for auditing. They make sure everything is working good.

The "Everyone" user group was removed because the people in Documenting for example do not need to access the Payroll files like HR does. All of these groups have access for the job they do, which follows the least-privilege idea.
