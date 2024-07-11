SUMMARY:
Liv Matan presents on One Click Six Services abusing permissions without permission, using Cloud Run and pulling any image from Artifact Registry or Container Registry. He demonstrates a tool called Jizer that analyzes logs to find created services, with a focus on GCP, AWS, and Azure.

IDEAS:
• The minimum permissions required for custom service accounts are often not well-defined.
• One Click Six Services can be used to abuse permissions without permission.
• Cloud Run allows pulling any image from Artifact Registry or Container Registry.
• Storage admin access can be exploited to perform RCE attacks.
• Buckets in GCP store compute services code that attackers can exploit.
• Default cloud build service accounts are often deployed with dangerous defaults.
• CSPs sometimes get it wrong, and default configurations can be vulnerable.
• Jizer is a tool that analyzes logs to find created services.
• It can recursively check for invoked-by fields to detect more services.
• The tool currently only works on AWS, but will be expanded to GCP and Azure.

INSIGHTS:
• One Click Six Services can lead to privilege escalation attacks without permission.
• Cloud Run's flexibility can be exploited by attackers.
• Storage admin access can be used to perform RCE attacks.
• Default cloud build service accounts are often deployed with dangerous defaults.
• CSPs should ensure default configurations are secure.
• Jizer is a powerful tool for detecting created services.

QUOTES:
• "One Click Six Services abusing permissions without permission."
• "Storage admin access can be exploited to perform RCE attacks."
• "Buckets in GCP store compute services code that attackers can exploit."

HABITS:
• None mentioned in the input.

FACTS:
• Default cloud build service accounts are often deployed with dangerous defaults.
• CSPs sometimes get it wrong, and default configurations can be vulnerable.
• Buckets in GCP store compute services code that attackers can exploit.

REFERENCES:
• One Click Six Services
• Cloud Run
• Artifact Registry
• Container Registry

ONE-SENTENCE TAKEAWAY:
"One Click Six Services can lead to privilege escalation attacks without permission, highlighting the importance of secure default configurations."

RECOMMENDATIONS:
• Implement secure default configurations for cloud build service accounts.
• Ensure One Click Six Services are not used to abuse permissions.
• Use tools like Jizer to detect created services and prevent RCE attacks.
• Regularly monitor and update default configurations to prevent vulnerabilities.

