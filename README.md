# wiperf-splunk-config

This repository is for use with WiFiNigel's wiperf script (https://github.com/wifinigel/wiperf). 
Each .conf file contains the relevent configuration required to output the results of the script to Splunk, all you need to do is install the Splunk Universal Forwarder and extract the above files into /opt/SplunkForwarder/ect/system/local/

# Notes:
In outputs.conf, you need to insert the IP address of your own splunk server
in inputs.conf you must insert a hostname which is unique, this will enable searching per sensor in Splunk.
