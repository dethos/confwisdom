Here is the output in Markdown format:

**SUMMARY**
John from Cipher presents on their experience with music graphs and their decision to move from Cassandra to PostgreSQL, discussing the challenges they faced and how they're abstracting their data layer using a graph wrapper system called "dogs".

**IDEAS:**

• The number of times John and I have talked about policy controls to control like data segregation was just not an option for us.
• Cassandra requires scale and multiple instances, which can be problematic for certain use cases.
• PostgreSQL is being used as the new database solution.
• Dogs is a graph wrapper system that abstracts the data layer and allows Cipher to work seamlessly with different databases.
• The post-processing logic in bhc uses dogs to translate Cipher queries into raw database calls.

**INSIGHTS:**

• Abstraction can be a powerful tool for building scalable systems.
• Flexibility is key when designing systems that need to adapt to changing requirements.
• It's important to avoid painting oneself into a corner by making upfront decisions that limit future options.

**QUOTES:**

• "We haven't really talked about it very much publicly but uh in vhce right now when you run Cipher uh if you if you don't have like a certain flag set it's actually all getting translated through an interface called dogs..."
• "Yeah the postgress code is up there uh we're doing it all in the open..."

**HABITS:**

• Open-sourcing code to encourage collaboration and community involvement.
• Writing code that is abstracted and flexible enough to adapt to changing requirements.

**FACTS:**

• Cassandra requires scale and multiple instances to function effectively.
• PostgreSQL is a popular open-source relational database management system.

**REFERENCES:**

• Cipher
• bhc (BloodHound)
• Yanis Scra
• PostgreSQL

**ONE-SENTENCE TAKEAWAY**
The importance of abstraction and flexibility in designing scalable systems that can adapt to changing requirements.

**RECOMMENDATIONS:**

• Embrace abstraction and flexibility when designing systems.
• Consider open-sourcing code to encourage collaboration and community involvement.
• Prioritize scalability and flexibility in system design.

