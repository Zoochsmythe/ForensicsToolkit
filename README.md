# Zach's Forensics Toolkit
Zach's Forensics Toolkit is a list of tools and their descriptions to aid in digital forensics and incident response tasks. These tools will help responders investigate cyber crime and assist in the foresnics process. Each of these tools are open-source and free to use. Links to their official documentation, as well as links to download are provided. 

![Image of CrowdStrike](https://s3.amazonaws.com/awsmp-logos/CrowdStrike-02042016.png)
CrowdStrike CrowdResponse is a lightweight Windows console application designed to aid in the gathering of system information for incident response and security engagements. The application contains numerous modules, each of them invoked by providing specific command line parameters to the main application.

Crowd Response results may be viewed in a variety of ways, particularly when leveraging CrowdStrike’s CRconvert. By default, output from Crowd Response is provided in an XML file. CRconvert will flatten this XML to CSV, TSV or HTML, if desired. The various format options were created to support the different needs and analysis preferences of the end user. list of tools to aid in digital forensics and incident response and their descriptions.
### Modules
`@dirlist` - The Dirlist module is the directory-listing module. It handles file hashing, disply creation/modification/access times of files, verifying and displaying digital signature information and more. 

`@pslist` - The pslist module is the active running process listing module. It can verify the digital signature of the process executable, obtain process command line, obtain detailed PE file information for each process executable and much more.

`@yara` - The YARA module is probably the most useful module for forensic investigations. YARA is a tool that helps malware researchers find and identify malware samples. With the YARA module, investigators can: 

* Scan memory of all currently active running processes
* Scan on-disk files of all currently active running processes
* Download YARA rule files from a provided URL
* Control target path recursion depth
* Utilize a target path exclusion/inclusion regular expression filter that acts on the full path name
* Use a file target wildcard mask to limit processing to specific file name components
* Option to only show positive hits
* Option to specify YARA rule file name mask
* Utilize a YARA file inclusion regular expression filter that acts on the full path name
* Scan all loaded module files of active processes
* Operate on a single process ID
* Optional recursion into provided YARA rules directory

#### Download: https://www.crowdstrike.com/resources/community-tools/crowdresponse/

![Image of WireShark](https://i1.wp.com/ape-360.com/wp-content/uploads/2019/02/Wireshark-e1550856586947.png?fit=520%2C245&ssl=1)
Wireshark is a network packet analyzer that captures network packets and tries to display that packet data as detailed as possible. As a forensic analyst, it is a powerful tool to analyze any malicious activity happening on the network from a compromised computer. 

### How to use Wireshark
You can download and install wireshark on both Windows and Linux and use it to capture network traffic on a machine. You can also import an existing pcap file to wireshark to see the nework traffic of the compromised machine. Within Wireshark you can customize what fields you see and also filter what types of packets are displayed. For a in-depth guide on the different packet filter options visit https://wiki.wireshark.org/DisplayFilters

#### Download: https://www.wireshark.org/download.html
