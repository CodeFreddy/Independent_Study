# Independent_Study

## Name: Kunpeng Xie

### 1. Introduction :
This project aims to test throughput and latency on QUIC protocol. At present, Caddy can't start with QUIC protocol successfully so all the experiments are based on the HTTPS protocol. The HTTPS certificate was just certified on localhost, so when running the test, should type in "https://localhost:8888" in Chrome.


### 2. Installation:

Caddy: https://caddyserver.com/

Data: Unzip data.zip. There are different files with different size which are used to test the throughput between caddy server and chrome.

### 3. Instruction:
1. First, start Caddy in command line: caddy -quic.
2. Second, type in "https://localhost:8888" in Chrome.
3. select which type of test you want to test.(Throughput or latency? Default is throughput testing)


