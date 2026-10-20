- [Visibility](/1.%20Concepts/Introduction%20to%20EDR/visibility.md) gives the raw data.
- Detection is the part where [EDR](/1.%20Concepts/Introduction%20to%20EDR/EDR.md) identifies/detects suspicious files.
- An [EDR](/1.%20Concepts/Introduction%20to%20EDR/EDR.md) have different detection approaches such as:
	1. **Signature-based Detection:** [EDR](/1.%20Concepts/Introduction%20to%20EDR/EDR.md) looks for known patterns/signatures that are associated with the malware/file.
	2. **Behavior-based Detection:** [EDR](/1.%20Concepts/Introduction%20to%20EDR/EDR.md) looks for suspicious behaviors that does not normally happen.
		For Example: a user does not normally open `Powershell.exe` but suddenly the same user opens `Powershell.exe`, runs a command and download files.
		[EDR](/1.%20Concepts/Introduction%20to%20EDR/EDR.md) may flag this as suspicious behavior. 