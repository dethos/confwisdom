**SUMMARY**
Katie and Nor (from Slack) discuss the risks and mitigations of non-human access between a user agent and a malicious user agent. They present a detection rule in Sigma for detecting OCTA (Octa Cloud) configuration takeover attacks.

**IDEAS:**
* The attack involves establishing trust between two different OCTA logs, not based on attacker's config.
* Building tooling that works with multiple clouds can help detect these attacks.
* Social engineering of an administrator user is often used in these attacks.
* Detection rules are relevant for SOC teams to identify and respond to these attacks.
* Establishing SCM sync can automate syncing of new users to prevent malicious app access.

**INSIGHTS:**
* Non-human access attacks on OCTA configurations can be stealthy and hard to detect.
* Building multi-cloud tooling can help detect and respond to these attacks.
* Social engineering is often used in these attacks, making them difficult to prevent.
* SOC teams need to be aware of this vector and develop detection rules to identify it.

**QUOTES:**
* "It's not about having admin privileges; it's about how long you can stay alive post-exploitation."
* "We have to work together to say okay this is one of our red lines things that should never happen."

**HABITS:**
* No specific habits mentioned in the content.

**FACTS:**
* No specific facts mentioned in the content.

**REFERENCES:**
* Sigma detection rule for OCTA configuration takeover attacks
* Octa Cloud configuration

**ONE-SENTENCE TAKEAWAY**
Develop multi-cloud tooling and establish SCM sync to prevent stealthy OCTA configuration takeover attacks.

**RECOMMENDATIONS:**
* Implement Sigma detection rules to identify OCTA configuration takeover attacks.
* Establish SCM sync to automate syncing of new users and prevent malicious app access.
* Train SOC teams on this vector and develop detection rules to identify it.

