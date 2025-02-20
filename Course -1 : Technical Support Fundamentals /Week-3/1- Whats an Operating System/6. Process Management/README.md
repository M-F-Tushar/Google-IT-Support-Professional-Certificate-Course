**Process Management**

### What is a Process?
A **process** is a program that is currently executing. It differs from a **program**, which is just an application stored on a computer. For example:
- 🖥️ **Program**: Google Chrome.
- 🔄 **Processes**: Multiple Chrome windows running simultaneously.

Each process has its own dedicated resources and runs independently.

### The Role of the Kernel in Process Management
The **kernel** plays a crucial role in handling multiple processes efficiently. It ensures that:
- ⚡ Each process gets the necessary **CPU time and memory**.
- 🔒 Processes do not interfere with each other.
- 📊 System resources are allocated efficiently.

### Key Concepts in Process Management
1. 🆕 **Process Creation**
   - When a user launches an application, the OS creates a new process.
   - Each process has a unique **Process ID (PID)**.

2. 🔄 **Process States**
   - 🏗️ **New**: Process is being created.
   - ⏳ **Ready**: Process is waiting for CPU time.
   - 🚀 **Running**: Process is currently executing.
   - ⏸️ **Waiting**: Process is paused, waiting for input/output.
   - ✅ **Terminated**: Process has completed execution.

3. ⚙️ **Multitasking and Scheduling**
   - The kernel uses **scheduling algorithms** to manage multiple processes.
   - Common scheduling types:
     - 📌 **First-Come, First-Served (FCFS)**: Processes run in order of arrival.
     - 🔄 **Round Robin (RR)**: Each process gets a fixed time slot before switching.
     - 🎯 **Priority Scheduling**: Higher-priority processes execute first.

### Why Process Management Matters
Efficient process management ensures that:
- 🚀 The computer **runs smoothly without freezing**.
- ⚡ Applications **respond quickly to user actions**.
- 🔄 System resources are **shared effectively** among running processes.

Understanding how the OS handles processes helps in **troubleshooting slow performance** and **optimizing system efficiency**.

