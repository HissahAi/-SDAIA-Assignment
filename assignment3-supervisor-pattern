Assignment 3 – Supervisor Pattern Use Case
Use Case

E-Commerce Order Management Assistant

Description

This system represents an AI assistant used in an e-commerce platform to manage customer requests related to orders, inventory, and payments.

Customers often make requests that involve multiple systems. For example:

"Cancel my order, check if the item is still available, and refund my payment."

This type of request cannot be handled efficiently by a single agent because it involves multiple domains such as order management, inventory systems, and payment processing. Instead, the system uses a Supervisor Pattern where a supervisor agent coordinates specialized sub-agents.

Sub-Agents
Order Management Agent

Responsible for handling order operations such as:

creating orders

cancelling orders

modifying orders

checking order status

Inventory Agent

Responsible for inventory-related tasks such as:

checking product availability

verifying stock levels

updating inventory records

Payment and Refund Agent

Responsible for payment operations such as:

verifying payments

checking billing records

issuing refunds when required

Supervisor Agent

The supervisor agent coordinates the entire workflow.

It first analyzes the user request and determines which domain is involved. Then it calls the appropriate sub-agent to perform the task.

For example:

The supervisor sends the cancellation request to the Order Management Agent.

It sends the stock check request to the Inventory Agent.

It sends the refund request to the Payment Agent.

Finally, the supervisor combines the responses from all agents and returns a single answer to the user.

Why One Agent Is Not Enough

A single agent would struggle to handle this task because the request spans multiple business domains with different tools and systems.

Order management requires access to order databases and order APIs.
Inventory management requires access to product stock systems.
Payment processing requires access to financial records and billing systems.

If one agent had access to all tools, several problems could occur:

Too many tools to choose from

Higher reasoning complexity

Increased risk of selecting the wrong tool

Difficult system maintenance

Limited scalability if new domains are added

Why the Supervisor Pattern Works Better

The Supervisor Pattern solves this problem by separating responsibilities across specialized agents.

Each agent focuses on one domain, while the supervisor agent handles task coordination.

This architecture provides several advantages:

clearer separation of responsibilities

easier debugging and testing

improved reliability

better scalability

easier future expansion

Conclusion

The supervisor pattern is useful for complex workflows that involve multiple domains and tools. Instead of relying on a single agent with many responsibilities, a supervisor agent coordinates specialized agents to complete the task efficiently. This design improves system reliability, modularity, and scalability.
