# CYB125-ai-final-project

# About this project

This is a Windows system configuration script that is supposed to collect information about a computers OS and put it in a JSON file. The script will gather the information from the OS and command line utilities. When the program collects the data, the program will analyze the data and organize it into categories. This could be really useful for IT and cybersecurity experts. 

# Approach

The program will be able to access the Windows Registry and able to collect important configurations settings. Then, the typeperf command will be able to gather statistics which would allow samplings of Windows performance counters. Then, the program will be able to execute commands to collect information on the system configuration. 

# Configuration Areas

1. snapshot_metadata=Records information about when and where the snapshot was collected
2. system_identity=Has information that identifies the OS, hostname, etc
3. hardware_profile=Has documents about the systems physical components
4. network_configuration=Information about the networks configuration
5. listening_ports=Helps to identify active services
6. local_user_accounts=List user accounts configured on the machine
7. password_policy=Shows the authentication requirements on password policy settings
8. auto_start_services=Programs that are launched during startup
9. running_processes=Able to see active applications and services
10. installed_software=Software information that is present on the system
11. installed_hotfixes=Shows what security patches are installed
12. persistence_locations=Used to maintain access after rebooting
13. scheduled_tasks=Jobs that are configured to run at certain times
14. security_posture=Has data on firewalls and antivirus
15. performance_snapshot=Helps to establish a baseline for system health
16. network_shares=Able to identify resources that are shared across the network

# Milestones
The project is structured around eight milestones, each one designed to produce a working
JSON file with an additional section implemented. The milestone structure isn't just a grading
convenience, it's a deliberate AI-collaboration pattern.
When students use AI well, they treat it like a pair programmer: they bring it small, well-scoped
problems, ask it to explain things rather than just produce things, and verify its answers against
an authoritative source (the textbook, the official Python docs, or their own running code). The
output is code they understand and could rewrite from scratch.
The eight-milestone structure exists to force the second pattern. Each milestone is small
enough that you can hold the whole thing in your head. Each milestone has a specific Python
concept attached to it, so you know what you're supposed to be learning. Each milestone has a
suggested AI prompt that asks for explanation, not code.
Your goal is not to finish the project as fast as possible. Your goal is to finish the project
understanding what you built. Those are different goals. The milestone structure pushes you
toward the second one.