# Healthcare IAM Assessment

## Objective
Assess whether access is appropriate for healthcare job functions and whether joiner/mover/leaver controls reduce unauthorized access.

## Assessment Areas
- Role-based access control
- Least privilege
- MFA
- Privileged access
- Shared accounts
- Access reviews
- Joiner/mover/leaver process
- Service accounts
- Password controls
- Emergency access

## Example Access Matrix
| Role | EHR | HR | Billing | Admin |
|---|---|---|---|---|
| Nurse | Yes | No | No | No |
| Physician | Yes | No | Limited | No |
| HR | No | Yes | No | No |
| Billing | Limited | No | Yes | No |
| IT Admin | Admin | Limited | Limited | Yes |

## Recommendations
- Enforce MFA for workforce access.
- Eliminate shared accounts where technically feasible.
- Perform quarterly access reviews.
- Automate termination access removal.
- Separate privileged administrative accounts from standard user accounts.
