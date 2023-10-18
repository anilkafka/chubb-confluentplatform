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


Here is the slide deck for reference:
https://docs.google.com/presentation/d/1fFlRrrTJf_x_w6heUMT_oYkq1qHMaWb2MUUfZH8UV_Y/edit?usp=sharing


## Cluster Setup:
1. Does Confluent Support Helm-chart based installation?
2. What is the Recommended setup from Confluent?
3. If Helmcharts are not supported, What privileges does the CFK Operator would need?
4. Access to storage?
5. Access to Active Directory
6. Access to other K8 components
7. DNS Access
8. Sizing review

## Cluster Architecture:
1. Overall high-level Architecture Diagram with all the CP Components
2. Explain all the included Components with CP
3. How do we expose CP endpoints in K8s? Right now, they use Kafka proxy from the grepplabs.
4. Do we still need Kafka Proxy with CP?

## Security:
1. What Authentication and Authorization methods are supported right now?
2. Is LDAP supported?
3. What is the path for OAuth? 
4. When OAuth is released to CP, can we use OAuth for new consumer clients in parallel to  LDAP for the existing clients? I.e..can both OAuth and LDAP run simultaneously.
5. Can we enforce the topic naming convention?
6. Encryption options

## DR Setup:
1. Different ways of DR setup in CP
2. Active/Active 
3. Active/Passive
4. Expected RTO/RPO 




