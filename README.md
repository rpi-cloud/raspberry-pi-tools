raspberry-pi-tools
==================

Helpful Raspberry Pi Tools and Scripts.

### Usage

To use those scripts just clone the repository to your Raspberry Pi.


```
git clone https://github.com/afritzler/raspberry-pi-tools.git
```

Ideally you want to add this directory to your `$PATH` or copy the executables into your `/usr/local/bin` folder.

To add the commands to you `PATH` and append it to your `.bashrc` file

```
cd raspberry-pi-tools
./utils/add_to_path
```

### List of Commands

* `pi-temp`: Displays the current CPU and GPU temperature

```
CPU temp=56.2'C
GPU temp=56.8'C
```

* `pi-motd`: MOTD script

```
   .~~.   .~~.    Saturday, 21 February 2015, 11:06:19 AM
  '. \ ' ' / .'   Linux 3.18.7+ armv6l GNU/Linux
   .~ .~~~..~.
  : .~.'~'.~. :   Uptime.............: 0 days, 13h53m39s
 ~ (   ) (   ) ~  Memory.............: 208292kB (Free) / 445740kB (Total)
( : '~'.~.'~' : ) Load Averages......: 2.36, 2.18, 1.73 (1, 5, 15 min)
 ~ .~ (   ) ~. ~  Running Processes..: 89
  (  : '~' :  )   IP Addresses.......: 192.168.2.109 and 72.123.134.1
   '~ .~~~. ~'    Weather............: 3°C, Sunny
       '~'
```

License and Authors
-------------------
Authors: Andreas Fritzler

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this software except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
