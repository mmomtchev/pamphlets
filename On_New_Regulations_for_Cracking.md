# My position on new regulations for cracking and security

## Security for consumer devices

The last few decades have seen a true explosion of network connectivity - exemplified by the exhausting the IPv4 address space. This trend hasn't even started to slow down - driven by good open-source TCP/IP stacks, cheap CPUs that possess the needed processing power to run them and cheap networking micro-controllers. Today, adding network connectivity to any electronic device produced in the hundreds of thousands of units does not add more than a few dollars to its manufacturing price and it is often a major selling feature.

On the other side, the complexity of a modern TCP/IP networking device is far beyond the understanding of any consumer. In fact, very often, different aspects of this device will fall within the fields of expertise of different R&D engineers who will need to work together to provide you with the possibility to check if the washing machine is still running from your mobile phone.

Experience has shown that security is the last concern of anyone who develops this kind of products. Interest in security usually begins with the very first breach and ensuing scandal. Consumers want cheap devices that work well. This they can tell very well. They also want security, but they can't tell if their devices are secure. This is why the usual market mechanics do not work very well for security - it becomes a horrible chain of boom-bust reactions, where consumers turn away from devices known to have been at the center of a data breach - where in fact chance plays a huge role in these events.

To further aggravate the issue, the installed base lags from the market. When a security problem is identified and fixed, it may take many years before the impacted devices disappear from people's homes.

This is why this market needs new regulations - akin to the FCC regulations for radio interference. New consumer devices providing networking features should be required to pass a simple certification process that verifies that they remain reasonably secure when being handled by the average consumer.

In order to drive the costs down, for smaller businesses, it is entirely feasible to provide *security-as-a-package* frameworks that are pre-certified.

## Possession and use of cracking tools

I have 30 years of experience working with IT security - every job I ever held since the mid-1990s had strong security aspects - with some being entirely focused on security. For all those 30 years, there has been talk of regulating the possession of cracking tools - usually by invoking their similarity with lock-picking tools. Possession of lock-picking tools is regulated in many jurisdictions, yet the low-end versions can be freely bought online. There are many tutorials on YouTube about how to use them and there are many amateurs who do this as a hobby for the sport.

There has always been lots of opposition to regulation from IT security professionals. They argue that regulating those tools will make working with or on them much more difficult. This is certainly true - computer software has went through tremendous development during the last 50 years driven by the very low entry costs. These days a computer costs next to nothing and it is everything that is needed to start improving the existing technology. When this new technology is created or improved, it becomes instantly available to copy for zero cost. **Preserving these economic specifics of IT is certainly very important.**

My personal proposition is that cracking tools are to be clearly identified as such with a standard warning. A very clear distinction should be made for network diagnostic tools. For example `ping` and `traceroute` should definitely not be labelled as cracking tools. Tor, an anonymizing tool, should also be excluded. On the other hand, tools such as `nmap`, with its half-open TCP connection scan mode, should definitely be treated as a specialized cracking tool. Same goes for tools for cracking encryption. Once those tools are clearly labelled, one might consider banning their use on certain networks. If the tools are clearly identified and banned, detecting people using them will be far easier. States who want strict controls may decide that their possession should require a prior official declaration and treat undeclared instances as unregistered firearms. I am personally very opposed to *shall issue* or even *may issue* permits, since every state that decides to follow this route, will handicap its own IT security industry without gaining anything since security does not recognize international borders.

## Backdoors and wiretapping

A backdoor should be a properly defined legal term and software makers shall be required to declare any backdoors to their customers - with a concealed backdoor being a very serious breach of contract with criminal liability. Unintentional backdoors should also carry some form of responsibility.

Use of undeclared backdoors by the state should be absolutely prohibited and considered an abusive authoritarian practice. It shall be held on the same level as arbitrary detention without due process or using state security to spy on political activists. Wiretapping should always be official, shall follow a strict judicial procedure, shall use official network protocols and APIs and shall never be mass or automated wiretapping. Same goes for using of cracking tools by the state.
