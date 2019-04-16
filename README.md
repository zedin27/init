# init
Introduction to DevOps material

## Notes that I learned through my reading and doing this project

* IPv4 has **2^32**, which approximately 4.2 billion possible addresses. The address format is **x.x.x.x**, where *x = 0 to 255*

* The prefix of the address format is the first high-bit notation is called **network prefix**, and the remaining bits are called **rest field, host identifier, or interface identifier**.

* IPv6 uses hex format in the numbers (16). Therefore, the total number of  bits is *128*, which there are **340 undecillion** possible addresses for IPv6. An undecillion is 10 to the power of 36 **(10,000,000,000,000,000,000,000,000,000,000,000,000)** would look like. But 340 undecillion? imagine how it would look like.

* `ip` command does not work on OSX machines. Instead of `ip`, use the `ipconfig <commands> <args>` where `<command>` is one of `waitall`, `getifaddr`, `ifcount`, `getoption`, `getpacket`, `getv6packet`, `set`, `setverbose`(?)

* `awk` pattern-directed scanning and processing language.

* `grep` searches patterns in each file separated by newline characters and prints each line after it matches.

* `init` in Unix-like computer operating systems is the first process started during booting a computer system, which is the daemon process that continues until it shuts down.

* A *MAC* (media access control) is an unique identifier assigned to the network interface controller.

* `dig` stands for (domain information groper) that performs DNS lookups and display the queries.

* `Docker` is an encapsulation environment that runs outside of the main boot.

* `Docker` separates applications from infrastructure using container technology, similar to how virtual machines separate the operating system from bare metal.

* When starting a new Debian machine, make sure to do some `apt update && apt install procps` to get the `uptime` command

* cmtl vs service commands when it comes to ssh (**secure shell**)

* To start the first container, use the command: `docker start -a -i ` \``docker ps -q -l`\`

* IP addresses varies depending in the computer at the lab you are in. To find your IP address, check on the `ifconfig` at the en0 inet section.
