## Understanding Advanced Work Assignment (AWA) in ServiceNow

Advanced Work Assignment (AWA) is ServiceNow’s intelligent, push‑based routing engine designed to deliver work items—such as Incidents, Requests, Walk‑ups, Cases, and Chats—to the right agent at the right time. Instead of relying on the traditional “pull model,” where agents hand‑pick tickets from a queue, AWA automatically distributes work based on real‑time factors like agent availability, workload capacity, and especially *skills*. This ensures that work is assigned fairly and efficiently, prevents cherry‑picking, and helps managers maintain consistent service quality.

AWA works through a structure of **Skills**, **Service Channels**, **Queues**, and **Assignment Rules** that determine how work flows through the system. Service Channels define where work originates, Queues act as holding areas for incoming tasks, and Assignment Rules determine how and when work is pushed to specific agents. Skills play a crucial role in these decisions—AWA can identify not just who is available, but who is *qualified* to handle a specific type of work. This is particularly important for helpdesks where agents have different areas of expertise, such as hardware, networking, security, or specific applications.

## Why Skills Matter in AWA

One of the biggest advantages of AWA is its ability to enforce skills‑based routing. Without skills, work items might be assigned to agents who are available but not equipped to resolve the issue effectively. Skills help AWA ensure that the *most capable* agent receives the task, improving resolution speed and reducing unnecessary escalations. They also prevent less‑experienced agents from being overloaded with complex issues while more advanced agents become underutilized. When skills are properly defined and maintained, AWA becomes a powerful tool for balancing workload, improving service outcomes, and maintaining a high‑quality support experience.

## Key Concepts (Simple Definitions)

**Service Channel**  
A source of incoming work, such as Incidents, Service Requests, Walk‑ups, Chats, or SMS. Each work item enters AWA through a defined channel.

**Queue**  
A temporary holding area where incoming work waits until an eligible agent—based on skills, availability, and capacity—is ready to receive it.

**Assignment Rules**  
Logic that determines how work moves from queues to agents. These rules tell AWA who should receive which items and under what conditions.

**Work Item**  
Any unit of work managed by AWA—such as an Incident, Request, Case, Walk‑up, Chat, or SMS message. All work items move through AWA before being assigned.