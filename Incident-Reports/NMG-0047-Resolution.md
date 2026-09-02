# NMG-0047 Resolution

*Ticket number:* NMG-0047
*Affected user:* Jane Cooper

## Issue Reported
Jane Cooper could not access Operations resources and her environment looked different from her teammates.

## Investigation
Investigation complete. Two root causes identified:
1. Jane's account was placed in the Operations OU instead of HR — this applied Operations Group Policy instead of HR policy.
2. Jane was not a member of the HR-Users security group (only Domain Users) — this explains the "Access Denied" error on HR shared resources.

Comparison account (Sandra Torres, HR) confirmed: she is in the HR OU and is a member of HR-Users.

## Planned Fix
Move Jane's account to the HR OU, and add her to the HR-Users group.

## Verification
1. Confirmed Jane Cooper's account now appears inside the HR OU alongside her HR teammates (Sandra Torres, James Whitfield, Michelle Grant).
2. Opened Jane Cooper's Properties > Member Of tab and confirmed she is now listed as a member of HR-Users.
3. Opened the HR-Users group Properties > Members tab and confirmed Jane Cooper appears in the members list alongside James Whitfield.
4. Both root causes are now resolved: Jane's environment will apply HR Group Policy (correct OU), and she now has the correct permissions.

*Date resolved:* 31/08/2026
*Resolved by:* IT New Hire
