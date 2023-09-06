# Windows Event Code 4625
logontype 8 stands for cleartext login

# Windows Event code 4673
Indicates that the specified user exercised the user right specified in the Privileges field.
Note: "User rights" and "privileges" are synonymous terms used interchangeably in Windows. Some user rights are logged by this event - others by 4674

# Windows Event Code 4674
Indicates that the specified user exercised the user right specified in the Privileges field.
Note: "User rights" and "privileges" are synonymous terms used interchangeably in Windows. Some user rights are logged by 4674 - others by 4673.

# Windows Event Code 4688
Is normally logged in event Viewer when a new process is created

# Windows Event Code 4689
This event documents when a process ends. When you start a program you are creating a "process" that stays open until the program exits.
This process is identified by the Process ID:. You can use this event to tell how long the program ran by correlating it to the earlier 4688 with the same Process ID.

# Windows Event Code 4720
A User Account Was Created

# Windows Event Code 4726
User Account Was Deleted

# Windows Event Code 4734
A Security-Enabled Local Group Was Deleted

# Windows Event Code 4771
This message is logged after a failed user's Kerberos pre-authentication attempt.
- 0x6: The user's password has expired.
0x12: The user's account is no longer active.
0x18: This error code indicates an account lockout.
0x24: The user's password is incorrect.
0x1	Client's entry in database has expired	 
0x2	Server's entry in database has expired	 
0x3	Requested protocol version # not supported	 
0x4	Client's key encrypted in old master key	 
0x5	Server's key encrypted in old master key	 
0x6	Client not found in Kerberos database	Bad user name, or new computer/user account has not replicated to DC yet
0x7	Server not found in Kerberos database	 New computer account has not replicated yet or computer is pre-w2k
0x8	Multiple principal entries in database	 
0x9	The client or server has a null key	 administrator should reset the password on the account
0xA	Ticket not eligible for postdating	 
0xB	Requested start time is later than end time	 
0xC	KDC policy rejects request	Workstation restriction
0xD	KDC cannot accommodate requested option	 
0xE	KDC has no support for encryption type	 
0xF	KDC has no support for checksum type	 
0x10	KDC has no support for padata type	 
0x11	KDC has no support for transited type	 
0x12	Clients credentials have been revoked	Account disabled, expired, locked out, logon hours.
0x13	Credentials for server have been revoked	 
0x14	TGT has been revoked	 
0x15	Client not yet valid - try again later	 
0x16	Server not yet valid - try again later	 
0x17	Password has expired	The user’s password has expired.
0x18	Pre-authentication information was invalid	Usually means bad password
0x19	Additional pre-authentication required*	 
0x1F	Integrity check on decrypted field failed	 
0x20	Ticket expired	Frequently logged by computer accounts
0x21	Ticket not yet valid	 
0x21	Ticket not yet valid	 
0x22	Request is a replay	 
0x23	The ticket isn't for us	 
0x24	Ticket and authenticator don't match	 
0x25	Clock skew too great	Workstation’s clock too far out of sync with the DC’s
0x26	Incorrect net address	 IP address change?
0x27	Protocol version mismatch	 
0x28	Invalid msg type	 
0x29	Message stream modified	 
0x2A	Message out of order	 
0x2C	Specified version of key is not available	 
0x2D	Service key not available	 
0x2E	Mutual authentication failed	 may be a memory allocation failure
0x2F	Incorrect message direction	 
0x30	Alternative authentication method required*	 
0x31	Incorrect sequence number in message	 
0x32	Inappropriate type of checksum in message	 
0x3C	Generic error (description in e-text)	 
0x3D	Field is too long for this implementation	 

# Windows Event Code 5858
Is a common issue occurring while using the windows server with applications that use IWebSService:Execquery

# Windows Event Code 7036
Means that a service has changed its state to the one indicated in the error message.
The error can occur due to corrupt system files and issues with Log files.
A clean boot and an SFC scan can fix the error.