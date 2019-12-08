# session-recording
 Configure session recording using sssd and tlog on RHEL based systems.
## Overview
This role will install and configure TLOG based session recording. SSSD is used to configure which sessions are recorded. The basic configuration will use file based domains. If sssd is already configured, the role will ensure that session recording is added to the pre-existing configuration.
