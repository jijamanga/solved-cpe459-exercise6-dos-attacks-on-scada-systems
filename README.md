Download Link: https://assignmentchef.com/product/solved-cpe459-exercise6-dos-attacks-on-scada-systems
<br>
A Denial-of-Service (DoS) attack is when an attacker causes a temporarily or indefinitely disrupting services of a host by flooding the target with a massive traffic. This exercise has four parts to design and implement DoS attacks on a SCADA system.

<ol>

 <li>Use Hping3 to perform each a LAND attack and a SYN flood attack.</li>

 <li>Use Metasploit to conduct a SYN flood attack.</li>

 <li>Analyze the performance of a SYN flood with Hping3 and with Metasploit.</li>

</ol>

<h1>2         Before Starting</h1>

It is essential that you use the system you have created from the previous assignments on this homework. You will need Wireshark on your host machine for this assignment.

<h2>2.1        Network Architecture Requirement</h2>

You must have the network architecture below before starting this assignment:

<h1>3         Using Hping3 to create DoS attacks</h1>

Your goal is to create a DoS attack against the PLC using Hping3 and observe the results in Wireshark. Kali Linux comes with Hping3 pre-installed; so, you <strong>do not</strong> need to install it. <strong>You will need to perform these tasks to answer the post exercise questions.</strong>

<h2>3.1         Create a LAND attack</h2>

Your DoS attack should follow these requirements:

<ol>

 <li>This DoS attack will send 3000 packets.</li>

 <li>Set the size of the payload to be 100 bytes.</li>

 <li>Make sure the packet type is SYN.</li>

 <li>The attack will occur on port 502 and the source port will equal 80.</li>

 <li>You want to preserve the source port and to spoof the attacker address.</li>

 <li>Open the terminal and conduct an Hping3 DoS attack.</li>

 <li>Open Wireshark choose eth0 and check your results.</li>

</ol>

<h2>3.2        Create a SYN flood attack</h2>

Using the same tool as Part #1 (Hping3), your goal is to perform a SYN flood attack against the PLC. Open Wireshark choose eth0 and check your results.

<h1>4         Using Metasploit to create a DoS attack</h1>

Metasploit is a powerful framework that you can use to perform many types of attacks. Your task is to execute a SYN flood attack against the PLC using this tool. <strong>You will need to perform these tasks to answer the post exercise questions.</strong>

<ol>

 <li>Kali Linux comes with Metasploit pre-installed; so, you <strong>do not</strong> need to install it.</li>

 <li>Open Wireshark choose eth0 and check your results.</li>

</ol>

<h1>5         Post Exercise Report</h1>

<h2>5.1        What is a LAND attack? What can this do to a system?</h2>

<h2>5.2        If a computer is a victim of a LAND attack how would you recover? How can we prevent this attack? Justify your answer.</h2>

<h2>5.3        You created two DoS attacks in part 3. Briefly describe what you observed in Wireshark.</h2>

<h2>5.4        Note any differences in between what you saw in Wireshark for part 3 and part 4. If there are not any, clearly state so.</h2>

<h2>5.5        In parts 3 and 4, you have performed the same attack using two different tools. In both cases, you verified the success of the attacks using Wireshark. During each attack, why does the HMI in ScadaBR appear to still run? In other words, how is it that ScadaBR can keep up with the SYN Flood attack?</h2>





