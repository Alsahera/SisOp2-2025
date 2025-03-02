# Alsahera Ramadhan Nesa || 3124521023
# 1.1	What are three main purposes of an operating system?
    •	Resource management: The operating system manages the computer's hardware resources, such as the CPU, memory, storage devices, and input/output devices. It allocates resources to various programs and processes, ensuring that they operate efficiently and without conflict. This includes scheduling tasks, managing memory allocation, and handling input/output operations.
    •	User interface: The OS provides a user interface that allows users to interact with the computer system. This can be in the form of a command-line interface (CLI) or a graphical user interface (GUI). The user interface enables users to execute commands, run applications, manage files, and configure system settings in a user-friendly manner.
    •	Security and access control: The operating system is responsible for maintaining the security of the system and protecting it from unauthorized access. It implements user authentication, access controls, and permissions to ensure that only authorized users can access certain resources or perform specific actions. Additionally, the OS helps protect against malware and other security threats.

# 1.2	We have stresseed the need fir an operating system to make afficient use of the computing hardware. When is it appropriate for the operating system to forsake this principle and to “waste” resources? Why is such a system not really wasteful?
    Although operating systems are usually designed to utilize hardware effectively, there are situations where "wasting" resources can be the right choice. For example, in a system that requires high availability, reserving backup resources can enhance responsiveness to demand spikes or component failures, thereby improving service reliability.
    In the software development phase, using resources for testing, while seemingly wasteful, is important to ensure the application functions well under various conditions. Additionally, in a cloud environment, resource overprovisioning can enhance performance and user experience by reducing latency.
# 1.3	What is the main difficulty that a programmer must overcome in writing an operating system for a real-time enviorment?
    The main difficulties that a programmer must overcome in writing an operating system for a real-time environment include several important aspects. First, the programmer must ensure that there is a guarantee of response time, which means they need to design effective scheduling algorithms so that critical tasks can be completed within the specified time limits, even under varying load conditions. Additionally, the management of resources such as CPU, memory, and I/O devices must be done very efficiently to avoid unwanted delays. The programmer must also design systems that can quickly detect and handle failures, ensuring that performance and reliability are maintained.
    Hardware limitations are also a challenge, where programmers need to write efficient code to operate on devices with limited specifications, such as slower CPUs or limited memory. Interaction with the external environment is also important, as the system must be able to respond quickly and accurately to changing conditions.
    Finally, maintaining data consistency and reliability is crucial. Programmers should avoid race conditions and ensure that the data remains consistent even when multiple tasks are running simultaneously.
# 1.4	Keeping in  mind the various definitons of operating system, consider whether the operating system should include applications such as wed browsers and mail programs. Argue both that it should and that it should not, and support your answers.
    Yes, the operating system must include a browser and other email programs. By including applications such as browsers and email programs, the operating system can provide a better user experience. Users don't need to search and install additional apps. Including basic applications such as browsers and email programs can make the technology more accessible to inexperienced users. This can help new users to more quickly adapt to the operating system and take advantage of the basic functionality they need.
# 1.5	How does the distinction between kernel mode and user mode function as a rudimentary form of protection (security)?
    •	Kernel Mode: In kernel mode, the operating system has unrestricted access to all hardware and system resources. It can execute any CPU instruction and access any memory address. This mode is reserved for the core components of the operating system, such as device drivers and the kernel itself.
    •	User Mode: In user mode, applications and user-level processes operate with limited privileges. They cannot directly access hardware or reference memory outside their allocated space. This separation ensures that user applications cannot interfere with the core functions of the operating system or other applications.
# 1.6	Which of the following instructions should be privileged?
a.	Set value of timer.
b.	Read the clock.
c.	Clear memory.
d.	Issue a trap instruction.
e.	Turn off interrupts.
f.	Modify entries in device-status table.
g.	Switch form user to kernel mode.
h.	Access I/O device.

     Set value of timer
    	Clear memory
    	Turn off interrupts
    	Modify entries in device-status table
    	Access I/O device
# 1.7	Some early computers protected the operating system by placing it in a memory partition that could not be modified by either the user job or the operating system itself. Describe two difficulties that you think could arise with such a scheme.
    Difficulties in OS Updates or Maintenance
    Updating or fixing bugs becomes difficult because the operating system cannot be modified, so each update may require a complete reinstallation.

    Limitations in Resource Management
    The operating system cannot dynamically adjust memory or process allocation, which reduces system efficiency.
#
