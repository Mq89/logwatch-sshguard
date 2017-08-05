# logwatch-sshguard

Counts logmessages of sshguard blocking IPs and puts them into the aggregation of logwatch.

## Installation

  - Copy or symlink `scripts/services/secure` into `/usr/share/logwatch/scripts/services`
  - Keep the old file as a backup

## Test

  - Run `logwatch --service secure`


## Sample Output

```
 --------------------- Connections (secure-log) Begin ------------------------ 

 SSHGuard blocked 3 IP(s).
 
 ---------------------- Connections (secure-log) End ------------------------- 
```