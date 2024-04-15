# Configuring and Updating Microsoft Defender



## Introduction

In this project, I constructed a mini honeynet within Azure, collecting log data from various resources into a Log Analytics workspace. Microsoft Sentinel utilizes this data to construct attack maps, trigger alerts, and create incidents. I measured some security metrics in the insecure environment for 24 hours, applied some security controls to harden the environment, measured metrics for another 24 hours, and then shown the results below. The metrics include:

## Updating Threat Definitions

![Updating Threat Definitions](https://github.com/portfolioAustinT/Configuring-and-Updating-Microsoft-Defender/assets/147944956/8efe6f17-c120-45bb-91e2-b5c0ca7caf49)

## Running Antivirus Quick Scan

![AntiVirus Scan](https://github.com/portfolioAustinT/Configuring-and-Updating-Microsoft-Defender/assets/147944956/6085ea85-a1a0-4af0-a7a5-2bfae2d270e8)


## Conclusion

To summarize, a mini honeynet was constructed in Microsoft Azure and log sources were integrated into a Log Analytics workspace. Microsoft Sentinel was employed to trigger alerts and create incidents based on the ingested logs. Additionally, metrics were measured in the insecure environment before security controls were applied, and then again after implementing security measures. It is noteworthy that the number of security events and incidents were drastically reduced after the security controls were applied, demonstrating their effectiveness.

It is worth noting that if the resources within the network were heavily utilized by regular users, it is likely that more security events and alerts may have been generated within the 24-hour period following the implementation of the security controls.
