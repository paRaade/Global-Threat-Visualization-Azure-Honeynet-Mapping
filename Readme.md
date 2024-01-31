## Attack Map Origins



![2024-01-06 01_19_24-linux-ssh-auth-fail - Microsoft Azure — Mozilla Firefox](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/768802e4-2803-4d42-b9cc-616cd9fe9040)


![2024-01-06 01_09_16-mssql-auth-fail - Microsoft Azure — Mozilla Firefox](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/309b126f-d963-4704-a864-1cf18944c3c3)


![2024-01-06 01_15_58-nsg-malicious-allowed-in - Microsoft Azure — Mozilla Firefox](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/623b668b-bce2-4eb3-b571-f1e982b55efe)


![2024-01-06 01_22_35-windows-rdp-auth-fail - Microsoft Azure — Mozilla Firefox](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/1c5fec52-3a32-48ad-873e-cf197a1e56c9)


## **Before Securing Environment**

The following is data collected in the insecure environment over the course of 24 hours:

2024-01-05T05:52:03.5049008Z to 2024-01-06T05:52:03.5049008Z
|Metrics| Count |
|--|--|
| Security Events (Windows VMs) |33486  |
|Syslog (Linux VMs) |2715|
| SecurityAlert (Microsoft Defender for Cloud) |3|
| SecurityIncident (Sentinel Incidents) |186|
| NSG Inbound Malicious Flows Allowed |2392|


## **After Securing Environment**

The following is data collected after hardening the environment over the next 24 hours:

2024-01-08T18:37:19.9634111Z to 2024-01-09T18:37:19.9634111Z
|Metrics| Count |
|--|--|
| Security Events (Windows VMs) |11548|
|Syslog (Linux VMs) |0|
| SecurityAlert (Microsoft Defender for Cloud) |0|
| SecurityIncident (Sentinel Incidents) |0|
| NSG Inbound Malicious Flows Allowed |0|

![Pasted image 20240106142844](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/2bcb63e5-71b2-49f1-90ea-ffc15b58b2df)
![Pasted image 20240106140510](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/9e4ecd20-2297-4ce3-adda-dc98f5d78ced)
![Pasted image 20240106134713](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/cf456657-f323-4759-8ce9-ab1316ab787f)
![Pasted image 20240106115039](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/78b82980-2859-43c5-8ea9-a943b73abaf0)
![Pasted image 20240106114518](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/2a1d29c7-3ac7-4264-bd38-4a182e27c7a7)
![Pasted image 20240106113638](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/6700031b-b61c-4052-8e9e-6013bb03705e)
![Pasted image 20240106113424](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/51c83f84-bb22-4725-94b4-9b3d24e67d1b)
![Pasted image 20240106112856](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/e942c026-e449-488b-ad83-6aa9cce647cc)
![Pasted image 20240106112720](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/203c854e-3208-4892-8e83-382a862a8387)
![Pasted image 20240106112248](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/e176097a-aa63-4e45-9671-c03c7968cc22)
![Pasted image 20240106112059](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/1b5ff96a-9f1c-4730-ac64-24a2f11f3827)
![Pasted image 20240106111725](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/3c8ffff0-9e05-4dfd-b92d-1f3386342149)


Sentinel Incidents
![2024-01-06 11_16_37-BEFORE AND AFTER xlsx - Excel](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/8e59c704-4404-44e2-88d1-c36d99953b96)


![Pasted image 20240106112059](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/69369069-03be-455d-b3a7-c9246dc47849)

![Pasted image 20240106112720](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/71dff6b4-06b4-4821-ad64-a93c1a3e7d21)

![Pasted image 20240106112248](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/8761ff89-4fec-4c90-93b6-4ebafbe0d85f)

![Pasted image 20240106112856](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/8e5c5a3c-608a-4383-a95f-440faa07109a)

![Pasted image 20240106113424](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/f6b1cf62-77d3-4f8f-8119-c24a3929e877)

![Pasted image 20240106115039](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/753ddb06-a067-4a0c-a667-9f4de5beadd2)


![Pasted image 20240106113638](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/a0e38e59-8175-4dc1-b684-86b55e1dcacb)

![Pasted image 20240106114503](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/7a0d09e3-b9fe-400b-b339-57eb0fc7674a)

![Pasted image 20240106140510](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/b6d1517c-b64c-41eb-bb3c-b6a4ef53c279)

![Pasted image 20240106142844](https://github.com/paRaade/Global-Threat-Visualization-Azure-Honeynet-Mapping/assets/126734769/bb3ce11e-a5a5-4252-99be-7c4d795fe8ed)
