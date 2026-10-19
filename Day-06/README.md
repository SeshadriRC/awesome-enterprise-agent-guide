# Day-06

- Switch the agent's deployment target to Agent Runtime and update the project configuration so it's ready to run on Agent Platform.
 
- Set up an MCP server in our GKE cluster and configure the agent to use it, so that the agent running in Agent Runtime can remotely inspect and troubLeshoot our Kubernetes cluster.
 
- Set up the Agent Platform Memory Bank for the agent so it automatically saves findings from each Kubernetes investigation and remembers past incidents when troubleshooting new issues.

 - Redeploy the agent
 
 - Create and run an evaluation to test that the agent actually uses its Memory Bank to recall past Kubernetes incidents when troubleshooting a related recurring issue.
