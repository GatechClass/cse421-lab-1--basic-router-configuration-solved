# cse421-lab-1--basic-router-configuration-solved
**TO GET THIS SOLUTION VISIT:** [CSE421 Lab 1- Basic Router Configuration Solved](https://mantutor.com/product/cse421-solved-2/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113561&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE421 Lab 1- Basic Router Configuration  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
Lab 1.5.2: Basic Router Configuration

Topology Diagram

Addressing Table

Device Interface IP Address Subnet Mask Def. Gateway

R1 Fa0/0 192.168.1.1 255.255.255.0 N/A

S0/0/0 192.168.2.1 255.255.255.0 N/A

R2 Fa0/0 192.168.3.1 255.255.255.0 N/A

S0/0/0 192.168.2.2 255.255.255.0 N/A

PC1 N/A 192.168.1.10 255.255.255.0 192.168.1.1

PC2 N/A 192.168.3.10 255.255.255.0 192.168.3.1

Learning Objectives

Upon completion of this lab, you will be able to:

• Cable a network according to the Topology Diagram.

• Erase the startup configuration and reload a router to the default state.

• Perform basic configuration tasks on a router.

• Configure and activate Ethernet interfaces.

• Test and verify configurations.

• Reflect upon and document the network implementation.

Scenario

In this lab activity, you will create a network that is similar to the one shown in the Topology Diagram. Begin by cabling the network as shown in the Topology Diagram. You will then perform the initial router configurations required for connectivity. Use the IP addresses that are provided in the Topology Diagram to apply an addressing scheme to the network devices. When the network configuration is complete, examine the routing tables to verify that the network is operating properly. This lab is a shorter version of Lab 1.5.1: Cabling a Network and Basic Router Configuration and assumes you are proficient in basic cabling and configuration file management.

Task 1: Cable the Network.

Cable a network that is similar to the one in the Topology Diagram. The output used in this lab is from 1841 routers. You can use any current router in your lab as long as it has the required interfaces as shown in the topology. Be sure to use the appropriate type of Ethernet cable to connect from host to switch, switch to router, and host to router. Refer to Lab 1.5.1: Cabling a Network and Basic Router Configuration if you have any trouble connecting the devices. Be sure to connect the serial DCE cable to router R1 and the serial DTE cable to router R2.

Answer the following questions:

What type of cable is used to connect the Ethernet interface on a host PC to the Ethernet interface on a switch? ________________________ Copper Straight Through

What type of cable is used to connect the Ethernet interface on a switch to the Ethernet interface on a router? __________________________ Copper Straight Through

What type of cable is used to connect the Ethernet interface on a router to the Ethernet interface on a host PC? _________________________ Copper Cross-Over

Task 2: Erase and Reload the Routers.

Step 1: Establish a terminal session to router R1.

Refer to Lab 1.5.1, “Cabling a Network and Basic Router Configuration,” for review of terminal emulation and connecting to a router.

Step 2: Enter privileged EXEC mode.

Router&gt;enable Router#

Step 3: Clear the configuration.

To clear the configuration, issue the erase startup-config command. Press Enter when prompted to [confirm] that you really do want to erase the configuration currently stored in NVRAM.

Router#erase startup-config

Erasing the nvram filesystem will remove all files! Continue? [confirm] [OK]

Erase of nvram: complete Router#

Step 4: Reload configuration.

When the prompt returns, issue the reload command. Answer no if asked to save changes.

What would happen if you answered yes to the question, “System configuration has been modified. Save?”

Answer “yes”: Saves the current configuration, ensuring changes persist after reload._______________________________________________________________________________

Answer “no”: Discards the current configuration changes, reverting to the previous saved configuration on reload._______________________________________________________________________________

The result should look something like this:

Router#reload

System configuration has been modified. Save? [yes/no]: no

Proceed with reload? [confirm]

Press Enter when prompted to [confirm] that you really do want to reload the router. After the router finishes the boot process, choose not to use the AutoInstall facility, as shown:

Would you like to enter the initial configuration dialog? [yes/no]: no

Would you like to terminate autoinstall? [yes]: [Press Return]

Press Enter to accept default.

Press RETURN to get started!

Task 3: Perform Basic Configuration of Router R1.

Step 1: Establish a HyperTerminal session to router R1.

Step 2: Enter privileged EXEC mode.

Router&gt;enable Router#

Step 3: Enter global configuration mode.

Router#configure terminal

Enter configuration commands, one per line. End with CNTL/Z.

Router(config)#

Step 4: Configure the router name as R1.

Enter the command hostname R1 at the prompt.

Router(config)#hostname R1 R1(config)#

Step 5: Disable DNS lookup.

Disable DNS lookup with the no ip domain-lookup command.

R1(config)#no ip domain-lookup

R1(config)#

Why would you want to disable DNS lookup in a lab environment?

_______________________________________________________________________________ Disabling DNS lookup prevents delays from mistyped commands and simplifies configuration

_______________________________________________________________________________ making it easier and faster for users to test and learn.

What would happen if you disabled DNS lookup in a production environment?

_______________________________________________________________________________ Disabling DNS lookup can disrupt hostname resolution, affecting network management, logging

_______________________________________________________________________________ and other services that rely on DNS

Step 6: Configure the EXEC mode password.

Configure the EXEC mode password using the enable secret password command. Use class for the password.

R1(config)#enable secret class

R1(config)#

Why is it not necessary to use the enable password password command?

_______________________________________________________________________________ Enable password does not encrypt the password, but enable secret does encrypt the password.

_______________________________________________________________________________ That’s why enable password is not necessary.

Step 7: Configure a message-of-the-day banner.

Configure a message-of-the-day banner using the banner motd command.

R1(config)#banner motd &amp;

Enter TEXT message. End with the character ‘&amp;’. ********************************

!!!AUTHORIZED ACCESS ONLY!!!

********************************

&amp;

R1(config)#

When does this banner display?

_______________________________________________________________________________ The Message-of-the-Day (MOTD) banner displays when anyone connects to the router via the console port.

Why should every router have a message-of-the-day banner?

_______________________________________________________________________________ It acts as a deterrent to unauthorized users by clearly stating that access is restricted to authorized personnel only.

Step 8: Configure the console password on the router.

Use cisco as the password. When you are finished, exit from line configuration mode.

R1(config)#line console 0

R1(config-line)#password cisco

R1(config-line)#login

R1(config-line)#exit

R1(config)#

Step 9: Configure the password for the virtual terminal lines.

Use cisco as the password. When you are finished, exit from line configuration mode.

R1(config)#line vty 0 4

R1(config-line)#password cisco

R1(config-line)#login

R1(config-line)#exit

R1(config)#

Step 10: Configure the FastEthernet0/0 interface.

Configure the FastEthernet0/0 interface with the IP address 192.168.1.1/24.

R1(config)#interface fastethernet 0/0

R1(config-if)#ip address 192.168.1.1 255.255.255.0

R1(config-if)#no shutdown

%LINK-5-CHANGED: Interface FastEthernet0/0, changed state to up %LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/0, changed state to up

R1(config-if)#

Step 11: Configure the Serial0/0/0 interface.

Configure the Serial0/0/0 interface with the IP address 192.168.2.1/24. Set the clock rate to 64000.

Note: The purpose of the clock rate command is explained in Chapter 2: Static Routes.

R1(config-if)#interface serial 0/0/0

R1(config-if)#ip address 192.168.2.1 255.255.255.0

R1(config-if)#clock rate 64000

R1(config-if)#no shutdown

R1(config-if)#

Note: The interface will be activated until the serial interface on R2 is configured and activated

Step 12: Return to privileged EXEC mode.

Use the end command to return to privileged EXEC mode.

R1(config-if)#end R1#

Step 13: Save the R1 configuration.

Save the R1 configuration using the copy running-config startup-config command.

R1#copy running-config startup-config

Building configuration…

[OK] R1#

What is a shorter version of this command? ________________________ R1#write

Task 4: Perform Basic Configuration of Router R2.

Step 1: For R2, repeat Steps 1 through 9 from Task 3.

Step 2: Configure the Serial 0/0/0 interface.

Configure the Serial 0/0/0 interface with the IP address 192.168.2.2/24.

R2(config)#interface serial 0/0/0

R2(config-if)#ip address 192.168.2.2 255.255.255.0

R2(config-if)#no shutdown

%LINK-5-CHANGED: Interface Serial0/0/0, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to up R2(config-if)#

Step 3: Configure the FastEthernet0/0 interface.

Configure the FastEthernet0/0 interface with the IP address 192.168.3.1/24.

R2(config-if)#interface fastethernet 0/0

R2(config-if)#ip address 192.168.3.1 255.255.255.0

R2(config-if)#no shutdown

%LINK-5-CHANGED: Interface FastEthernet0/0, changed state to up %LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/0, changed state to up

R2(config-if)#

Step 4: Return to privileged EXEC mode.

Use the end command to return to privileged EXEC mode.

R2(config-if)#end R2#

Step 5: Save the R2 configuration.

Save the R2 configuration using the copy running-config startup-config command.

R2#copy running-config startup-config

Building configuration…

[OK] R2#

Task 5: Configure IP Addressing on the Host PCs.

Step 1: Configure the host PC1.

Configure the host PC1 that is attached to R1 with an IP address of 192.168.1.10/24 and a default gateway of 192.168.1.1.

Step 2: Configure the host PC2.

Configure the host PC2 that is attached to R2 with an IP address of 192.168.3.10/24 and a default gateway of 192.168.3.1.

Task 6: Verify and Test the Configurations.

Step 1: Verify that routing tables have the following routes using the show ip route command.

The show ip route command and output will be thoroughly explored in upcoming chapters. For now, you are interested in seeing that both R1 and R2 have two routes. Both routes are designated with a C. These are the directly connected networks that were activated when you configured the interfaces on each router. If you do not see two routes for each router as shown in the following output, proceed to Step 2.

R1#show ip route

Codes: C – connected, S – static, R – RIP, M – mobile, B – BGP

D – EIGRP, EX – EIGRP external, O – OSPF, IA – OSPF inter area

N1 – OSPF NSSA external type 1, N2 – OSPF NSSA external type 2 E1 – OSPF external type 1, E2 – OSPF external type 2 i – IS-IS, su – IS-IS summary, L1 – IS-IS level-1, L2 – IS-IS level-2 ia – IS-IS inter area, * – candidate default, U – per-user static route o – ODR, P – periodic downloaded static route

Gateway of last resort is not set

C 192.168.1.0/24 is directly connected, FastEthernet0/0

C 192.168.2.0/24 is directly connected, Serial0/0/0

————————

R2#show ip route

Codes: C – connected, S – static, R – RIP, M – mobile, B – BGP

D – EIGRP, EX – EIGRP external, O – OSPF, IA – OSPF inter area

N1 – OSPF NSSA external type 1, N2 – OSPF NSSA external type 2 E1 – OSPF external type 1, E2 – OSPF external type 2 i – IS-IS, su – IS-IS summary, L1 – IS-IS level-1, L2 – IS-IS level-2 ia – IS-IS inter area, * – candidate default, U – per-user static route o – ODR, P – periodic downloaded static route

Gateway of last resort is not set

C 192.168.2.0/24 is directly connected, Serial0/0/0

C 192.168.3.0/24 is directly connected, FastEthernet0/0

Step 2: Verify interface configurations.

Another common problem is router interfaces that are not configured correctly or not activated. Use the show ip interface brief command to quickly verify the configuration of each router’s interfaces. Your output should look similar to the following:

R1#show ip interface brief

Interface IP-Address OK? Method Status Protocol

FastEthernet0/0 192.168.1.1 YES manual up up

FastEthernet0/1 unassigned YES unset administratively down down

Serial0/0/0 192.168.2.1 YES manual up up

Serial0/0/1 unassigned YES unset administratively down down Vlan1 unassigned YES manual administratively down down

————————

R2#show ip interface brief

Interface IP-Address OK? Method Status Protocol

FastEthernet0/0 192.168.3.1 YES manual up up

FastEthernet0/1 unassigned YES unset administratively down down

Serial0/0/0 192.168.2.2 YES manual up up

Serial0/0/1 unassigned YES unset down down Vlan1 unassigned YES manual administratively down down

If both interfaces are up and up, then both routes will be in the routing table. Verify this again by using the show ip route command.

Step 3: Test connectivity.

Test connectivity by pinging from each host to the default gateway that has been configured for that host.

From the host attached to R1, is it possible to ping the default gateway? __________ Yes From the host attached to R2, is it possible to ping the default gateway? __________ Yes

If the answer is no for any of the above questions, troubleshoot the configurations to find the error using the following systematic process:

1. Check the PCs.

Are they physically connected to the correct router? (Connection could be through a switch or directly.) ____________ Yes

Are link lights blinking on all relevant ports? ____________ Yes

2. Check the PC configurations.

Do they match the Topology Diagram? ____________ Yes

3. Check the router interfaces using the show ip interface brief command.

Are the interfaces up and up? ____________ Yes

If your answer to all three steps is yes, then you should be able to successfully ping the default gateway.

Step 4: Test connectivity between router R1 and R2.

From the router R1, is it possible to ping R2 using the command ping 192.168.2.2? ____________ Yes

From the router R2, is it possible to ping R1 using the command ping 192.168.2.1? ____________ Yes

If the answer is no for the questions above, troubleshoot the configurations to find the error using the following systematic process:

1. Check the cabling.

Are the routers physically connected? ____________ Yes Are link lights blinking on all relevant ports? ____________ Yes

2. Check the router configurations.

Do they match the Topology Diagram? ____________ Yes

Did you configure the clock rate command on the DCE side of the link? ____________ Yes

3. Check the router interfaces using the show ip interface brief command.

Are the interfaces “up” and “up”? ____________ Yes

If your answer to all three steps is yes, then you should be able to successfully ping from R2 to R1 and from R2 to R3.

Task 7: Reflection

Step 1: Attempt to ping from the host connected to R1 to the host connected to R2.

This ping should be unsuccessful.

Step 2: Attempt to ping from the host connected to R1 to router R2.

This ping should be unsuccessful.

Step 3: Attempt to ping from the host connected to R2 to router R1.

This ping should be unsuccessful.

What is missing from the network that is preventing communication between these devices?

________________________________________________________________________________ The routing information is not correct that’s why it is preventing communication between these devices.

________________________________________________________________________________ By configuring routing information correctly the routers will be able to route packets between the networks connected to R1 and R2

Task 8: Documentation

On each router, capture the following command output to a text (.txt) file and save for future reference.

• show running-config

• show ip route

• show ip interface brief

If you need to review the procedures for capturing command output, refer to Lab 1.5.1, “Cabling a

Network and Basic Router Configuration.”

Task 9: Clean Up
