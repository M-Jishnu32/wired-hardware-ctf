teo files are there 'confidential file' and 'TOP_SECRET.pcap'
opened the first file and saw thousands and thousands of file.....immediatly knew reading all the pcap packets was not gonna cut it
the logical idea was to crack it brute force
in pcap file command
  cntl f
  packet bytes
  bssid
got the bssid : f6:0f:6c:4d:06:7c
googled how to filter out the flags from using pcap and pass file came accross the command aircracker-ng
command: aircrack-ng -w the_secret_flag.txt -b f6:0f:6c:4d:06:7c TOP_SECRET.pcap
it gave the correct flag
wired{c4ts_4r3_c00l}
