# aix53.pam.conf
## Modified AIX pam.conf opening up OTHER control for services not explicitly defined

SSH is not explicityly defined in the PAM configuration for AIX, therefore to
configure SSH for outside authentication like and [AD bridge](https://www.saferstrategy.com/active-directory-bridge/) or Authentication Services connections to Active Directory OTHER should be reconfigured from
denied to pam_aix
