#This labs is an ssh scan and detection with 3 virtual machines, an attacker, a target and a monitor.
#first here are the ipv4 adresses on host-only

![](./images/detection_lab_ssh_scan/ip_kali.png)
![](./images/detection_lab_ssh_scan/ip_cible.png)
![](./images/detection_lab_ssh_scan/ip_monitor.png)
![](./images/detection_lab_ssh_scan/ip_kali.png)

#monitor preparation

![](./images/detection_lab_ssh_scan/monitor_capture.png)

![](./images/detection_lab_ssh_scan/monitor_promisc.png)

#tcpdump running on monitor

![](./images/detection_lab_ssh_scan/tcpdump_running.png)

#nmap scan

![](./images/detection_lab_ssh_scan/kali_nmap_scan.png)

#ssh fail on kali

![](./images/detection_lab_ssh_scan/kali_ssh_fail.png)

#failed attempts on target

![](./images/detection_lab_ssh_scan/target_failed.png)

#monitor pcap infos

![](./images/detection_lab_ssh_scan/monitor_pcap_info.png)

#wireshark captures(ssh pattern, ssh flow)

![](./images/detection_lab_ssh_scan/wireshark_ssh_patern.png)

![](./images/detection_lab_ssh_scan/wire_shark_shh_flow.png)
