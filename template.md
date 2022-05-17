# On-boarding Process Documentation

The purpose of this document is to design and implement a standardized on-boarding procedure for new customers.

- Kick off call.
- Questionnaire.
- Data collection.
- Data correction.
- Update call.
- Initiate active monitoring.
- Project call.
- Move away from on-boarding.

## Kick off call

- Go over questionnaire if needed.
- Do you have any long standing issues?
- What would you like to see happen with your Infrastructure?
- Any desired integration projects?
- Discuss the "things" we will ask them to do (e.g. Add accounts/Run scripts/fill forms)

## Data collection

DATA COLLECTION PROCESS

### Questionnaire
### See questionnaire.md

- How many seats do you have?
- How many do you anticipate having in the next year?
- How do you monitor your infrastructure?
- Existing Process and procedures documentation/planning
- List of people/employee's
- Tools they use for the day to day operations/management of the platform
- Drawings/Platform documentation
- Datacenter/Network documentation
- Securfity Policies/procedures

### SNAPwalk

    - Install and run SNAPwalk program.

### IP Infrastucture

    - Compile or collect dataset of IP addresses, Server names, Identifiers, etc.
    - Compile or collect network configuration from servers.
    - Compile or collect route information. 

## Data Processing

### Actions - Data Processing

    - Create client on backend systems
    - Create dataset on IPAM/DCM
    - Review Cluster Dataset  
    - Build infrastructure state dataset (for centrilized change management)
    - Run Cluster Checker tool

## Data correction

### Actions - Data correction

    - Sync disparities between systems.
    - Prepare list of missing/needed documentation/SOPs 
        - E.g. Change control process
        - E.g. Adding shell/tac to systems

## Update call

Now that your data is true let's begin monitoring to make sure it stays that way.

    - Checkin with customer to inform them that we have corrected any data variance between nodes.
    - Inquire if customer is happy with services thus far.
    - Inform customer that we will now begin active monitoring services.
    - Inform customer that after the monitoring services are implemented another call will be scheduled to discuss further projects/needs.

## Implement tools and processes

    - Initiate active monitoring
        - Smokeping ? Nagio ? Does the IPAM tool have something built in ? 
        - Do we want to also provide the customer a tool to monitor their customers latency/jitter ? 
        - From a termination standpoint...Monitor top 5 destinations and MoS.  Alert on dest if mos < 3 over X amount of time and Y amount of calls.
        - Monitor call costs and alert if set threshold met.
        - Monitor if X vendor has consistently low MoS. 
        - Monitor if X vendor trunks go down. 

## Project call

    - Identify data silo's.
    - Identify integrations that may help the customer's efficiency. 
    - Discuss integrations between varying platforms?

## Move away from on-boarding

That's all folks

## Misc/Other nodes

### IPAM Tool

  This is for us to add all their systems/datacenter/IPs/hosts/serial numbers

- Should probabaly create a script to get some of the data automatically

## Configuration Management

- Process/

## Copyright (c)

Copyright (c) 2022 P2P Tech, LLC.
All Rights reserved.