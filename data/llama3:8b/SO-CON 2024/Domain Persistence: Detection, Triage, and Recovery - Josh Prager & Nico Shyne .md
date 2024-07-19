**SUMMARY**
Presented by unknown, discussing domain controller security and rotation of Kerberos tickets. The talk covers various topics such as domain forest, trust delegation, and root CA compromise.

**IDEAS:**
• Domain controllers require periodic password rotations to maintain security.
• Machine account passwords are already rotated every 30 days by default.
• In a root CA compromise, it's necessary to revoke all certificates and refresh the certificate revocation list.
• Adversaries can potentially unrevoke revoked certificates if they still have access to the environment.
• Additional auditing is crucial for detecting domain persistence attack techniques.
• It's essential to validate attack techniques in your organization through benign and neutered means.

**INSIGHTS:**
• The importance of regular password rotations for domain controllers and machine accounts.
• The need to revoke all certificates and refresh the certificate revocation list in a root CA compromise.
• The potential for adversaries to unrevoke revoked certificates if they still have access to the environment.
• The importance of additional auditing for detecting domain persistence attack techniques.

**QUOTES:**
• "Machine account passwords are like 30 something characters long and they look ugly as hell, ain't nobody guessing that thing right."
• "If you don't validate these attack techniques can be executed in your environment highly recommend."

**HABITS:**
• None mentioned or discussed during the presentation.

**FACTS:**
• The default rotation period for machine account passwords is every 30 days.
• Adversaries can potentially unrevoke revoked certificates if they still have access to the environment.

**REFERENCES:**
• None mentioned or discussed during the presentation.

**ONE-SENTENCE TAKEAWAY:**
The importance of regular password rotations and additional auditing lies in maintaining domain controller security and preventing potential compromise.

**RECOMMENDATIONS:**
• Regularly rotate machine account passwords.
• Implement additional auditing to detect domain persistence attack techniques.
• Validate attack techniques in your organization through benign and neutered means.
• In a root CA compromise, revoke all certificates and refresh the certificate revocation list.

