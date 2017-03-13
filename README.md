Wi-Fi signal strength analyser
=========
A simple script to analyse Wi-Fi signal strength on Ubuntu

### About
A simple bash script that allows getting the signal level, link quality and the ping time of a device connected to the network. This script has been tested on a laptop running Ubuntu 16.04.

This script was explained in OpenSource For You- March  2017   Issue Vol. 5  No. 6.

### Usage
```shell
$ ./signalstr
```
Output will be logged in detail
```shell
$ tail -f ~/wifianalyse.log

Interface: wlp1s0    Ping Address: 127.0.0.1
        Time           Count                    Output                              Ping
[13/03/17 13:41:05] |      1  |   Link Quality=56/70 Signal level=-54 dBm  |    time=0.023 ms
[13/03/17 13:41:06] |      2  |   Link Quality=53/70 Signal level=-57 dBm  |    time=0.017 ms
[13/03/17 13:41:07] |      3  |   Link Quality=49/70 Signal level=-61 dBm  |    time=0.022 ms
[13/03/17 13:41:08] |      4  |   Link Quality=49/70 Signal level=-61 dBm  |    time=0.017 ms
[13/03/17 13:41:09] |      5  |   Link Quality=46/70 Signal level=-64 dBm  |    time=0.043 ms
```
### Meta
Kuntal Chandra – [@kuntalchandra](https://twitter.com/kuntalchandra) – chandra.kuntal@gmail.com

Distributed under the MIT license. See ``LICENSE`` for more information.
