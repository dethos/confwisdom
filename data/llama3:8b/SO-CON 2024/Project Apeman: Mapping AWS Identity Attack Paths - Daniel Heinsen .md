Here is the extracted information in Markdown format:

**SUMMARY**
Daniel presented on AWS attack paths, discussing tier zero combinations and conditional access. He highlighted the importance of context templates for resolving conditions and expanding vocabulary for discussing AWS attack paths.

**IDEAS:**
• Tier zero combinations can be used to gain unauthorized access to AWS resources.
• Conditional access policies make it difficult to determine which path is being taken without meeting certain conditions.
• Context templates can help resolve conditions by populating variables and allowing template overrides.
• Defining custom templates for different norms in an environment can facilitate attack path analysis.
• The concept of effective or aggregate tier zero has been exploited in the wild, but its legitimacy as a security risk is unclear.
• Enumerating AWS resources and detecting unusual activity can be done through CloudTrail and other tools.
• Role assumption patterns can be used to infer relationships between roles and detect potential security risks.

**INSIGHTS:**
• Conditional access policies require careful consideration of conditions and variables to ensure secure access control.
• Context templates can simplify conditional access policy evaluation by providing a standardized framework for resolving conditions.
• Defining custom templates for different norms in an environment can improve the accuracy and relevance of attack path analysis.
• The concept of effective or aggregate tier zero highlights the importance of considering multiple paths and relationships when evaluating security risks.

**QUOTES:**
• "It's helpful to write alerts to say like is this the first time role B has ever assumed role C if that's the case then maybe just tell someone."
• "8man is opportunistic it is it's not going to require that you know you have the whole picture it'll infer these relationships on whatever nodes it has"

**HABITS:**
• None mentioned in this content

**FACTS:**
• CloudTrail can be used to enumerate AWS resources and detect unusual activity.
• Role assumption patterns can be used to infer relationships between roles.

**REFERENCES:**
• CloudTrail
• 8man (opportunistic)

**ONE-SENTENCE TAKEAWAY**
Carefully consider conditional access policies, context templates, and role assumption patterns when evaluating security risks in AWS attack paths.

**RECOMMENDATIONS:**
• Define custom templates for different norms in an environment to facilitate attack path analysis.
• Use CloudTrail to enumerate AWS resources and detect unusual activity.
• Consider the concept of effective or aggregate tier zero when evaluating security risks.

