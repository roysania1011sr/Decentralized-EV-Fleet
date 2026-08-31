# Decentralized-EV-Fleet
A decentralized EV fleet where vehicles communicate via V2V, share real-time status, and decide the best EV for each task. The decision goes to the Fleet Manager for approval, then the suitable driver is assigned and the task starts. This saves time, reduces manual work, speeds decisions, and improves fleet efficiency.

The Decentralized EV Fleet Management System is an intelligent multi-agent solution designed to make EV fleet operations faster, smarter, more efficient, and reliable.
Instead of depending entirely on a centralized system to decide which vehicle should perform a task, each EV acts as an autonomous agent. EVs communicate with nearby vehicles through V2V communication, exchange real-time information such as battery level, location, availability, and workload, and collaboratively determine which EV is best suited for a task.
The selected decision is then sent to the Fleet Manager for approval. Once approved, the appropriate driver is assigned, and the task is initiated.

🔄 System Workflow

Task/Request Generated
     
        ↓

EV Agents Share Real-Time Status

        ↓

V2V Communication

        ↓

EVs Evaluate & Decide Suitable Vehicle

        ↓

Decision Sent to Fleet Manager

        ↓

Manager Approval

        ↓

Suitable Driver Assigned

        ↓

Task Started

        ↓

Real-Time Monitoring


If the assigned EV becomes unavailable, has insufficient battery, or encounters a failure, the fleet can identify another suitable EV and initiate task reassignment, improving fleet resilience.

💡 Innovation

The core innovation is decentralized decision-making.
Traditional fleet systems generally depend on a central controller for vehicle selection and task allocation. This approach distributes intelligence among the EVs themselves.

#Key Innovations :

* Autonomous EV Agents: Each EV can monitor its own condition and participate in decision-making.
* V2V-Based Coordination: Vehicles exchange information directly to coordinate fleet operations.
* Collaborative Decision-Making: EVs collectively determine the most suitable vehicle instead of relying completely on one central decision-maker.
* Manager-in-the-Loop: Automated decisions are still verified through Fleet Manager approval before execution.
* Dynamic Task Reassignment: Tasks can be redirected when an assigned EV becomes unavailable.
* Real-Time Decisions: Current battery, location, workload, and availability can influence task selection.

This creates a balance between "automation and human supervision".

⚙️ Feasibility

The project is technically feasible because the prototype can be implemented using existing and accessible technologies.

#Software Feasibility

* Python, AI/ML algorithms can handle agent logic and decision-making.
* Flask/FastAPI can provide backend services.
* JavaScript, HTML and CSS can create the fleet dashboard and simulation.
* MQTT/Web Sockets can simulate real-time vehicle communication.
* JSON/CSV can store vehicle and task information.

The prototype does not require physical EVs. Multiple virtual EV agents can simulate real-world fleet behavior, making development and testing cost-effective.

#Hardware Feasibility

For future physical implementation, the system can integrate:
* GPS
* Battery Management System data
* Vehicle sensors
* On-board computers
* V2X communication modules

Therefore, the concept can progress from software simulation → hardware prototype → real-world EV deployment.

💰 Viability

The system can provide value for organizations operating multiple EVs, including:
* Logistics and delivery fleets
* Ride-hailing services
* Corporate transportation
* Public transport
* Autonomous vehicle fleets
* EV-based service fleets

By automating vehicle selection and reducing unnecessary centralized processing, the system can improve vehicle utilization and operational efficiency.
The architecture is also scalable: additional EVs can join the fleet as new agents without requiring every decision to pass through a single controller.

 🚀 Benefits

⏱️ Time Saving :
Automated vehicle selection reduces the time required for manual task allocation.

⚡ Faster Decision-Making :
EVs can exchange real-time information and make local decisions quickly.

 🎯 Better Task Allocation :
Tasks can be assigned according to battery level, distance, availability, and workload.

 👨‍💼 Reduced Manager Workload :
The Fleet Manager mainly supervises and approves decisions rather than manually selecting every vehicle.

🔄 Improved Flexibility :
Tasks can be reassigned when vehicle conditions change.

🛡️ Higher Reliability :
Failure of one EV does not necessarily stop the entire fleet operation.

📈 Scalability :
The decentralized architecture can support expansion to larger fleets.

🔋 Better Energy Utilization :
Battery status can be considered while selecting vehicles, helping avoid assigning demanding tasks to vehicles with low battery.

🧠 Why Decentralization?

In a centralized system:
All EVs → Central Controller → Decision → EV

The controller becomes heavily responsible for fleet-wide decisions.

This approach:
EV ↔ EV ↔ EV
 ↕    ↕    ↕
EV ↔ EV ↔ EV
      ↓
Fleet Manager Approval
      ↓
Driver Assignment

This distributes decision-making across the fleet while retaining managerial control and approval.

🖥️ Prototype Demonstration 

The prototype simulates multiple EVs operating as autonomous agents.

The dashboard demonstrates:
* EV movement
* Battery status
* Vehicle availability
* Driver availability
* V2V communication
* Task requests
* Agent decision-making
* Fleet Manager approval
* Driver assignment
* Task execution
* Vehicle failure
* Dynamic task reassignment

The simulation provides a visual representation of how decentralized EV coordination can work in a real fleet environment.

🔐 Safety & Human Oversight

Although the system uses autonomous decision-making, the Fleet Manager remains part of the control loop.
This makes the system more practical for real-world deployment where automated decisions may require human supervision.

🔮 Future Scope

The prototype can be extended with:

* Real V2X communication
* GPS and live maps
* AI-based route optimization
* Reinforcement learning for fleet decisions
* Real-time traffic information
* EV charging-station optimization
* Edge computing
* Real vehicle telemetry
* Advanced cybersecurity
* Large-scale fleet deployment

 🎯 Final Objective
The objective is to transform a conventional EV fleet into an intelligent, collaborative and semi-autonomous fleet where vehicles communicate, make informed decisions, obtain manager approval, and execute tasks efficiently.

Communicate → Decide → Approve → Assign → Execute
This approach aims to make EV fleet management faster, time-efficient, scalable, resilient, and less dependent on continuous centralized control.
