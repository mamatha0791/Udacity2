//Deploy a High-Availability Web App using CloudFormation

1. infra.yml -- udagram aws cloud formation script
2. param.json - defined parameters for the cloud formation script
3. create.sh -- cloudformation stack script
4. delete.sh -- deletes cloudformation

Note: My App was successfully created without any errors. But I'm seeing issue in the Target groups where the Registered targets (2) status is being returned as unhealthy. When i'm browsing
the URL it says "502 Bad gateway".

I tried troubleshooting the network stats, the port is up and listening. Please help.