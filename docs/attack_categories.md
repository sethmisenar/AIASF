**Input Vectors**
**Description:** This category includes vulnerabilities and attack vectors arising from how the LLM application processes user-provided inputs or external data. These vectors exploit weaknesses in input handling, such as manipulating prompts, crafting adversarial examples, or inserting malicious data to alter the model's behavior or compromise its integrity. Effective management of input vectors is crucial to safeguard the model against unwanted actions, data poisoning, or exploitation. Key defenses include input validation, sanitization, filtering mechanisms, and monitoring for abnormal input patterns.

**Output Vectors**
**Description:** This category encompasses vulnerabilities and attack vectors related to the LLM application's output. It includes how the application handles, sanitizes, validates, and delivers model-generated content to users or other systems. Properly managing outputs is critical to prevent information leakage, misuse, or unintended behaviors that might arise when delivering LLM responses directly to users or downstream components. Failure to address output vectors can lead to the propagation of harmful content, unintentional disclosure of sensitive information, or manipulation of subsequent processes.

**Functional Vectors**
**Description:** This category focuses on vulnerabilities and attack vectors associated with the specific functionalities offered by the LLM application during its operation. These vectors target how the application interacts with external systems, executes tasks, and performs actions such as web browsing, code interpretation, function calling, and retrieval-augmented generation. Risks in this category include insecure handling of function calls, improper interactions with external systems, plugin misuse, and granting excessive permissions. Addressing functional vectors requires secure implementation, monitoring, and constraint of the application's capabilities to prevent misuse or exploitation.

**Infrastructure and Model Vectors**
**Description:** This category covers attack vectors targeting the underlying infrastructure, backend components, and model lifecycle of the LLM application. It includes risks associated with model theft, supply chain vulnerabilities, hardware attacks, deployment environments, data storage, and resource management. These vectors also encompass threats during the model training phase, where malicious data or compromise of the infrastructure can lead to model tampering or degradation. Properly securing the infrastructure, managing supply chain dependencies, implementing access controls, and safeguarding training processes are essential to defending against these vectors.