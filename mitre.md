# Screensaver Registry (T1546)
This technique was seen in several APT and malware where they put the malicious payload path to the SCRNSAVE.EXE registry key to redirect the execution to their malicious payload path. This TTP is a good indicator that some attacker may modify this entry for their persistence and privilege escalation.
[Attack](https://dmcxblue.gitbook.io/red-team-notes-2-0/red-team-techniques/privilege-escalation/untitled-3/screensaver)
[MITRE](https://attack.mitre.org/techniques/T1546/002/)
For defence we can set a policy in AD that delete this registry for each user.

