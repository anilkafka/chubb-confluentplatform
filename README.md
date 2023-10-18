# chubb-confluent platform


## Onsite Agenda:

| Topic |  Time  | Speaker |
| --- |  ---  | --- |
| Kickoff and Introductions|  1:00 - 1:15PM  | Ashish and team - Chubb|
| Chubb's Architecture|  1:15 - 2PM  | Chubb's team |
| Confluent Platform Security |  2 - 2:45PM  | Anuj Sawani - Confluent |
| Break |  2:45 - 3:00PM  | Break |
| CP Architecture/Components |  3 - 3:45PM  | Anil and Ravi - Confluent |
| CP Cluster Setup |  3:45 - 4:30PM  | Greg Trout - Confluent |
| DR setup |  4:30 - 5PM  |  Anil and Ravi - Confluent  |
| Wrap-up and next steps |  5 - 5:30PM  |  Chubb and Confluent|



## Cluster Setup:
1. [Does Confluent Support Helm-chart based installation?]
2. [What is the Recommended setup from Confluent?]
3. [If Helmcharts are not supported, What privileges does the CFK Operator would need?]
4. [Access to storage?]
5. [Access to Active Directory]
6. [Access to other K8 components]
7. [DNS Access]
8. [Sizing review]

## Cluster Architecture:
Overall high-level Architecture Diagram with all the CP Components
Explain all the included Components with CP
How do we expose CP endpoints in K8s? Right now, they use Kafka proxy from the grepplabs.
Do we still need Kafka Proxy with CP?

## Security:
What Authentication and Authorization methods are supported right now?
Is LDAP supported?
What is the path for OAuth? 
When OAuth is released to CP, can we use OAuth for new consumer clients in parallel to LDAP for the existing clients? I.e..can both OAuth and LDAP run simultaneously.
Can we enforce the topic naming convention?
Encryption options

## DR Setup:
Different ways of DR setup in CP
Active/Active 
Active/Passive
Expected RTO/RPO 




