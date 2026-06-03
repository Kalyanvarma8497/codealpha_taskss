# Task 2 - Jenkins Remoting Project

## Objective
Set up Jenkins Remoting to connect a remote Jenkins agent node and execute builds remotely.

## Tools Used
- Jenkins 2.555.2
- Java JDK 21
- Windows 11

## Steps Performed

1. Installed Jenkins.
2. Configured Jenkins Dashboard.
3. Created a new agent node named Agent.
4. Configured:
   - Remote Root Directory
   - Labels: agent1
   - Permanent Agent
5. Connected the agent using Jenkins Remoting (agent.jar).
6. Verified successful connection.
7. Created a Freestyle Project named RemoteTestJob.
8. Restricted build execution to agent1.
9. Executed a test build successfully on the remote agent.

## Result

The Jenkins agent was connected successfully and builds were executed remotely.

## Output

Console Output:

Jenkins Agent Connected Successfully

Hostname:

VarmaZone

Build Status:

SUCCESS