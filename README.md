# computer-networks-assignment-3-packet-filtering-in-software-defined-networks-solved
**TO GET THIS SOLUTION VISIT:** [Computer Networks Assignment # 3-Packet Filtering in Software Defined Networks Solved](https://www.ankitcodinghub.com/product/computer-networks-assignment-3-packet-filtering-in-software-defined-networks-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96402&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Computer Networks Assignment # 3-Packet Filtering in Software Defined Networks Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Assignment # 3: Packet Filtering in Software Defined Networks

GOAL:

Software-Defined Networking (SDN) is a recently proposed networking paradigm in which the data and control planes are decoupled from one another. One can think of the control plane as being the networks “brain”, i.e., it is responsible for making all decisions, for example, how to forward data, while the data plane is what actually moves the data. In traditional networks, both the control- and data planes are tightly integrated and implemented in the forwarding devices that comprise a network. The SDN control plane is implemented by the “controller” and the data plane by “switches”. The controller acts as the “brain” of the network and sends commands (“rules”) to the switches on how to handle traffic. OpenFlow has emerged as the de facto SDN standard and specifies how the controller, and the switches communicate as well as the rules controllers install on switches. In this assignment, the students will be exploring how to create and manage different network topologies with OpenFlow switches and SDN controllers. Especially, the students will learn on deploying ad-hoc flow rules on the OpenFlow switches via an SDN controller. This way, the switches can necessarily filter the required packets and implement a simple packet filter firewall.

Disclaimer: This assignment can be done in groups of 2 students. You may choose the same partner with whom you did the assignment#2.

Environment Setup:

You can use the prior Ubuntu VM that you used in assignment-2. However, you need to install the Mininet emulator and POX controller as per the below instructions.

Installing Mininet

~$ sudo apt install mininet

To check if it is installed properly – run the below command. This will create a simple test network and you can use “pingall” command to see if host1 can ping to host2 or not.

~$ sudo mn

Installing POX controller (through source)

~$ git clone http://github.com/noxrepo/pox ~$ cd pox

~/pox$ git checkout dart

To run pox controller, you need to run the pox.py or debug-pox.py file as below. ~/pox$ ./pox.py “your_controller_module”

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Task-1: Programming to create a custom network topology

Mininet is also programmable using the python programming language. A set of sample topologies are provided in the “assign4starter.zip”. Download and unzip this file in the Ubuntu VM and you’ll find two different directories: topo and pox. Ignore the pox directory for now (it’s used in Task-2 and above). In the topo folder there are a variety of python files. Each defines a topology, run the part1 file with command “sudo python assign4starter/topos/part1.py”. It will drop you into the CLI with the network topology defined in the python script.

<ol>
<li>1) &nbsp;Your task here is to modify part1.py to represent the following network topology
Where [x] means you create a host named x, {y} means a switch named y, and — means

there is a link between the node and the switch.
</li>
<li>2) &nbsp;After creating the above architecture, provide the two items in a part1 folder in a
compressed file: a) Your modified part1.py file; (b) Screenshots of the iperf, dump, and pingall commands (from mininet) in pdf format.
</li>
</ol>
Note: To run the part-1, you may need to install the openvswitch-testcontroller. sudo apt-get install openvswitch-testcontroller

sudo ln /usr/bin/ovs-testcontroller /usr/bin/ovs-controller

Task-2: SDN Controller using POX

In task 1, you experimented with Mininet using its internal controller. In this (and future) task, you will instead be using a custom controller to send commands to the switches. Here, we will be using the POX controller, which is written in Python. For this part, you will create a simple firewall using OpenFlow-enabled switches. The term “firewall” is derived from building construction: a firewall is a wall you place in buildings to stop a fire from spreading. In the case of networking, it is the act of providing security by not letting specified traffic pass through the firewall. This feature is good for minimizing attack vectors and limiting the network “surface” exposed to attackers.

In this part, you are provided with the Mininet topology, part2.py, to setup your network which assumes a remote controller listening on the default IP address and port number 127.0.0.1:6633. You do not need to (and should not) modify this file. The topology that this script will setup is as follows. Note that h1 and h4 are on the same subnet and a different one from h2 and h3.

For part-2, you are also provided with a skeleton POX controller (under pox folder): “part2controller.py”. This file is required to be modified to create the firewall that implements the following rules.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Then, you need to deploy this new controller and run mininet under the new topology provided in “part2.py”.

To run this part:

<ol>
<li>You need to place part2controller.py in ~/pox/ext/ directory. Then from the pox directory, run “./pox.py part2controller”</li>
<li>Ensure, in the topology program the following import statement is added: “from mininet.node import RemoteController”</li>
<li>Ensure that in the topology program’s main, mininet call uses the RemoteController: net = Mininet (topo=t, controller=RemoteController)</li>
</ol>
Note: Basically, your Firewall should allow all ARP and ICMP traffic to pass. However, any other type of traffic should be dropped. It is acceptable to flood the allowable traffic out all ports. Be careful! Flow tables match the rule with highest priority first, where priority is established based on the order rules are placed in the table. When you create a rule in the POX controller, you need to also have POX “install” the rule in the switch. This makes it so the switch “remembers” what to do for a few seconds. Do not handle each packet individually inside of the controller! Hint: To do this, look up ofp_flow_mod. The OpenFlow tutorial (specifically ” Sending OpenFlow messages with POX”) and the POX Wiki are both useful resources for understanding how to use POX.

Deliverables:

<ol>
<li>Your part2controller.py file</li>
<li>Documentation on how you deployed the controller and how you run mininet with new
topology.
</li>
<li>A screenshot of the pingall command. Note that h1 and h4 should be able to ping each
other (h2 and h3 as well), but not across subnets. Also, the iperf command should fail (as

you’re blocking IP traffic). This is realized as the command hanging.
</li>
<li>A screenshot of the output of the dpctl dump-flows command. This should contain all of
the rules you’ve inserted into your switch.
</li>
</ol>
Task-3: Firewall in real network (For graduate students)

In task 2 you have implemented a simple firewall that allowed ICMP and ARP packets but blocked all other packets. For your part 3, you will be expanding on this to implement routing between subnets and implementing firewalls for certain subnets. The idea is to simulate an actual production network.

We will be simulating a network for a small company (topology is shown in the picture below). Assume that the company has a 3-floor building, with each floor having its own switch and subnet. Additionally, we have a switch and subnet for all the servers in the data center, and a core switch

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
connecting everything together. Note that the names and IPs are not to be changed. You are provided the topology “./topos/part3.py” as well as a skeleton controller (./pox/part3controller.py).

As with part 2, you need only modify the controller only.

Your goal will be to allow traffic to be transmitted between all the hosts. In this part, you will be allowed to flood traffic on the secondary routers (s1, s2, s3, dcs31) in the same method that you did in part-2 (using a destination port of of.OFPP_FLOOD). However, for the core router (cores21) you will need to specify specific ports for all IP traffic. You may find it easiest to determine the correct destination port by using the destination IP address and source IP address, as well as the source port on the switch that the packet originated from. Additionally, to protect our servers from the untrusted Internet, we will be blocking all IP traffic from the Untrusted Host to Server 1. To block the Internet from discovering our internal IP addresses, we will also block all ICMP traffic from the Untrusted Host. In summary of your goals:

• Create a POX controller with the following features: All nodes should be able to communicate EXCEPT

o hnotrust1 cannot send ICMP traffic to h10, h20, h30, or serv1. o hnotrust1 cannot send any IP traffic to serv1.

Deliverables:

<ol>
<li>Your part3controller.py file.</li>
<li>A screenshot of the pingall command. All nodes but hnotrust should be able to send and
respond to pings.
</li>
<li>A screenshot of the iperf hnotrust1 h10 and iperf h10 serv1 commands. Though not
shown in these commands, hnotrust should not be able to transfer to serv1. It should be

able to transfer to other hosts.
</li>
</ol>
A screenshot of the output of the dpctl dump-flows command. This should contain all of the rules you’ve inserted into your switches.

What to be submitted:

<ol>
<li>A PDF formatted report with all required answers, and necessary evidences as asked above including codes, execution samples, instructions for running the programs, and references used. The filename should be formatted as “Lastname_firstname_Assign4.pdf”.</li>
<li>Well-documented source codes and README.txt in the form of one single Zip file.</li>
<li>Contribution details of both members of the team, if this assignment is done is in teams.</li>
</ol>
Submission:

Submit your assignment on Blackboard only.

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
References

<ol>
<li>POX controller manual – https://noxrepo.github.io/pox-doc/html/</li>
<li>Mininet Tutorial – http://mininet.org/walkthrough/</li>
<li>OpenvSwitch – https://docs.openvswitch.org/en/latest/</li>
</ol>
4. https://docs.pica8.com/display/PICOS2111cg/PicOS+OpenFlow+Tutorials

</div>
</div>
</div>
