#metasploit-metasploitable2-pentest-report
Przeprowadzenie kontrolowanego testu penetracyjnego na maszynie Metasploitable2 przy użyciu Metasploit Framework. Zidentyfikowano i wykorzystano metodą PoC 8 podatności (m.in. vsFTPd 2.3.4 Backdoor, Samba Usermap Script, UnrealIRCd Backdoor, DistCC, Apache Tomcat Manager, PostgreSQL, Java RMI, NFS), uzyskując zdalne powłoki/sesje Meterpreter z uprawnieniami root. Następnie wdrożono i zweryfikowano działania naprawcze (wyłączenie podatnych usług), potwierdzając ich skuteczność ponowną próbą ataku.
Narzędzia: Kali Linux, Metasploit Framework, Metasploitable2, OpenVAS/Nessus.
#zabbix-monitoring-incident-simulation-report
Wdrożenie systemu monitoringu Zabbix (serwer + agent) w środowisku dwóch maszyn wirtualnych oraz przeprowadzenie testów stresowych: obciążenie CPU/RAM, krytyczne zapełnienie dysku, twardy restart systemu i awaria agenta. Skonfigurowano hosty, szablony i triggery, a następnie zweryfikowano poprawność detekcji anomalii w czasie rzeczywistym.
Narzędzia: Zabbix Server/Agent 7.0, VirtualBox/VMware, Linux, SQL, SSH.
#siem-elastic-atomic-red-team-detection-report
Zbudowanie środowiska SIEM na bazie Elasticsearch i Kibana z telemetrią z hosta Windows (Sysmon + Winlogbeat), a następnie symulacja 4 technik ataku wg MITRE ATT&CK (T1047 WMI Recon, T1003.001 LSASS Dump, T1059.001 PowerShell Encoded Command, T1136.001 Create Account) przy użyciu Atomic Red Team. Wszystkie ataki wykryto i przeanalizowano za pomocą zapytań KQL w Kibana.
Narzędzia: Elasticsearch, Kibana, Sysmon, Winlogbeat, Atomic Red Team, PowerShell.
