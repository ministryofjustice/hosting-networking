# 1. Formation of the Hosting Networking Group

Date: 2025-10-17

## Status

✅ Accepted

## Context

We have different hosting platforms, the wider MoJ network and various 3rd parties which need network connectivity to each other and rely on shared services such as DNS.  No one team has ownership, skills, knowledge and people to complete all the activities required around this.  Currently these tasks are mainly completed on a good will basis, borrowing expertise where needed or doing tasks alongside their day job. 

## Decision

We will create a Hosting Networking Group (HNWG), this will pull together people with networking skill sets from various teams in hosting and the wider MoJ networking community. 

Here we can share ideas, standards, and take responsibility of critical networking resources from individuals and manage them as a group.   

We can give advice and guidance for teams to help them complete networking tasks themselves or find people from within the group with the skills required and liaise with their current teams to agree their time to work on the task. 

We will take on ownership of networking services which are currently without owners such as DNS. 

## Responsibilities

| Name | Owner | HNWG Responsibility |
|---|---|---|
|General networking advice |HNWG|Provide advice via the #hosting-networking Slack | channel |
|Cross hosting networking advice and implementation |HNWG |Provide advice and if needed arrange people from within the group to assist or implement |
|MoJ TGW advice and implementation|Network Operations|Provide advice and if needed arrange people from within the group to assist or implement |
|DNS |HNWG |Provide advice and if needed arrange people from within the group to assist or implement |
|Certificates |HNWG |Provide advice and if needed arrange people from within the group to assist or implement |
|Hosting Firewalls: application and networking|HNWG |Provide advice and if needed arrange people from within the group to assist or implement |
|Network security standards|HNWG |Provide advice and if needed arrange people from within the group to assist or implement |

### Repositories
 - https://github.com/ministryofjustice/dns 
 - https://github.com/ministryofjustice/deployment-tgw 
 - https://github.com/ministryofjustice/mta-sts 
 - https://github.com/ministryofjustice/moj-ip-addresses 
 - https://github.com/ministryofjustice/terraform-aws-mtasts 
 - https://github.com/ministryofjustice/operations-engineering-certificate-renewal 
 - https://github.com/ministryofjustice/operations-engineering - needs some things unpicking from here.

## Consequences

 - We use the #hosting-networking channel for queries and communication. 
 - We use a GitHub project for issue management - https://github.com/orgs/ministryofjustice/projects/138/views/1
 - We have regular calls to discuss work
 - There will knowledge transfer to the group needed
 - We will record decisions in ADRs
