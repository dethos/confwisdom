Here is the extracted information in Markdown format:

**SUMMARY**
A researcher presents a talk on vulnerabilities found in AWS AppSync and assume roles, discussing how they exploited a zero-day vulnerability to gain access to an AWS account. The presentation also touches on support from management and colleagues.

**IDEAS:**
* A researcher found a vulnerability in AWS AppSync that allowed them to break the shared responsibility model and gain access to an AWS account.
* The vulnerability was originally present in all public AWS accounts that used AppSync, without requiring undocumented APIs or early-stage features.
* The researcher assumed 8,000 roles from 8,000 web assume roles with web identity calls based on roles found on GitHub, without encountering any issues or triggering AWS monitoring.
* The presenter's management and colleagues were supportive of their research, allowing them to publicly disclose the findings.
* The vulnerability was fixed by removing a condition key that had no specific reason for its removal.
* Service Control Policies (SCPs) could be used to prevent similar vulnerabilities by limiting access at an account level.

**INSIGHTS:**
* Public disclosure of vulnerabilities can lead to positive outcomes, such as improved security and reduced risk for cloud services.
* Support from management and colleagues is crucial for researchers who want to publicly disclose their findings.
* Removing condition keys without understanding their purpose can lead to unexpected consequences and potential security risks.
* SCPs can be used to implement guardrails and limit access at an account level, reducing the risk of zero-day vulnerabilities.

**QUOTES:**
* "I'd be happy if you're uh interested in this research definitely check out security labs. dq.com or follow me on Twitter or mastedon uh appreciate your time happy to answer any questions or if you see me around the con happy to chat about this as well thanks"

**HABITS:**
* None mentioned

**FACTS:**
* None mentioned

**REFERENCES:**
* Security Labs. dq.com
* Twitter
* Mastedon

**ONE-SENTENCE TAKEAWAY**
A public disclosure of a vulnerability can lead to improved security and reduced risk for cloud services, highlighting the importance of transparency in research.

**RECOMMENDATIONS:**
* Implement Service Control Policies (SCPs) to limit access at an account level and reduce the risk of zero-day vulnerabilities.
* Remove condition keys only after understanding their purpose and potential impact on system security.

