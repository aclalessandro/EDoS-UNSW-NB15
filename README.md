Database EDoS-UNSW-NB15

The UNSW-NB15 dataset, developed by Moustafa and Slay (2015), includes various types of local and cloud-based attacks. There are 9 attack models, namely: Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode and Worms.

Over the course of five months, we manually identified Economic Denial of Sustainability (EDoS) attacks based on the characteristics described by Zhijun et al. (2020) and the UNSW-NB15 report (link: https://shre.ink/gv3X) in the set of DoS attacks originally.

The attacks found include ICMP Flood, TCP SYN Flood, DNS Flood, UDP Flood and HTTP Flood, which exhibit high-rate denial-of-service characteristics, as well as EDoS attacks with low-rate characteristics, such as Slowloris, XXE, BREACH, Apache HTTP Server Range Header Memory Exhaustion and so on. EDoS attacks have been labeled “EDOS”, creating a new attack category in the dataset, which is available in this repository.


References:

W. Zhijun, L. Wenjing, L. Liang, and Y. Meng, “Low-rate dos attacks, detection, defense, and challenges: a survey,” IEEE access, vol. 8, pp.43 920–43 943, 2020.

N. Moustafa and J. Slay, “Unsw-nb15: a comprehensive data set for network intrusion detection systems (unsw-nb15 network data set),” in 2015 military communications and information systems conference (MilCIS). IEEE, 2015, pp. 1–6.
