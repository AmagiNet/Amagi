The Amagi Project
=================




I´m alive... :-)

The user creates the network...





What is "Amagi Project" ?
-------------------------------

Code was first..
    
    <?xml version="1.0"?>
    <amagi>
        <target>Return to the mother</target>
        <creator>human</creator>
    </amagi>

The Amagi Project, created with the aim of spreading the values of free hardware and software,
as well as its use to create free networks.

But a free network must have free data.

Each device on the network should be able to release a minimum data useful to the community,
in a safe, anonymous and free.

The main step to free up a device is turn it into a opendata transmitter active.


Bring life to your device



<h3>Amagi equation</h3>
_______________________


[Free Hardware] + [Free OS]  + [Free Software Apps] + [Free Networks] + [Open Data] = Free World



                        <?xml version="1.0"?>
                        <equation>
                            <components>
                            
                                <first>     Free Hardware       </first>
                                <second>    Free OS             </second>
                                <third>     Free Software Apps  </third>
                                <fourth>    Free Networks       </fourth>
                                <fifth>     Open Data           </fifth>
                                <total>     Free World          </total>
                            
                            </components>
                        </equation>

Therefore, the project is designed to implement this formula in our real world.

The ways to apply the formula are infinite. The Amagi project is dedicated to travel and study these ways
to get a better and happy world for everyone, without exception.


Wake up and join the Amagi movement !




What is "Amagi Network Project" ?
-------------------------------


Project on building a global free mesh network AMAGI - class I

AMAGI class I : All the devices connected
    
    - Are free devices:
        - are free hardware running
        - are connected to a free network
        - have a free operative system running
        - have free software apps running
        
    - Send Opendata to an Amagi Server (AMAGI Data Protocol)
        -IMALIVE Data Packet

Due to the difficulty of obtaining real hardware and free software,
to make this possible, it is necessary to enable AMAGI - class II, III, IV.

AMAGI class II : All devices connected

    - Are open devices :
        - are connected to a free network
        - have a free operative system running
        - have free software apps running
        
    - Send Opendata to an Amagi Server (AMAGI Data Protocol)
        -IMALIVE Data Packet

AMAGI class III : All devices connected

    - Are open devices :
        - have a free operative system running
        - have free software apps running
        
    - Send Opendata to an Amagi Server (AMAGI Data Protocol)
        -IMALIVE Data Packet

AMAGI class IV : All devices connected

    - Are open devices :
        - have free software apps running
        
    - Send Opendata to an Amagi Server (AMAGI Data Protocol)
        -IMALIVE Data Packet


Devices List :

    - Embebbed Systems
        - Raspberry Pi Family
        - BeagleBoard Family
        - Arduino Family
    - Phones
        - Android
        - IOS
        - BlackBerry
        - Firefox OS
        - Others
    - Tablets
        - Android
        - IOS
        - Others
    - Set Top Boxes
    - Home Servers
    - Stations ( sensors )
    - Others

These are the initial requirements

    <?xml version="1.0"?>
    <device>
        <requirements>
            <freehardware>      </freehardware>
            <freeos>            </freeos>
            <freesoft>          </freesoft>
            <freenet>           </freenet>
            <opendata>          </opendata>
        </requirements>
    </device>


What is "Amagi Data Protocol" ?
-------------------------------

Protocol that defines communication rules and type of data transmitted between a device and an Amagi Server.

<bold>Communication Rules</bold>

- AmagiOpenRules

<bold>Data Types</bold>

- AmagiOpenData Packets
    
    - IMALIVE Packet

- AmagiCommData Packets


What is "Amagi Server" ?
-------------------------------

A computer with Amagi Server Software running, that provides 

    - AmagiOpenData Reception Services
        
        reception of data packets in AMA format. This paquet defines
            
            - Security and encryption
            - Identification
            - Data groups
            - Hosting and Backup
        
    
    - AmagiOpenData Send Services
        
        send of process data packets in multiple formats
            
            - XML
            - JSON
            - MySQL
            - RSS
            ...etc.

    
    - AmagiOpenData Front End Services
    
        web front-end service to publish web content
    
    
    - AmagiOpenData Back End Service
    
        web back-end service to administrate server



Basically,it´s a server that 

    1 identifies a node
    2 receives and stores data transfers from the node
    3 make available to the public worldwide in multiple formats


An Amagi Server have a dedicated web space for each of the devices.


What types of data can send a device ?
-------------------------------

No limits !! ( lie :-(), there are limits, for now...But it´s not a problem.

You can send the next data groups to the server :


    - Identification and state data group
    - Sensors data group
    - Running Services information data group

As you want.



But, you're required to send ONLY one data group : IMALIVE

<h5>IMALIVE: A minimal AmagiOpenData</h5>

The minimal data group that you need send to connect Amagi Network and use an Amagi Server.
Is like the beating heart of the device.
When you send He's saying 
        
    I'm alive and I'm ready.

Amagi Servers receive all this "heartbeats" and other data of devices worldwide and presents them in a web.

IMALIVE contains a minimum data set that the owner of the device available to everyone freely.

With this data contributes to create a large network scheme of free devices, useful for improving communication among all.
While your device is "beating", is alive and connected to the world's largest network of free devices.
Being able to communicate with other devices on the network, sending or receiving new information.


The minimum packet data IMALIVE :

    <?xml version="1.0"?>
        <imalive>
            <minimaldata>
            
                <IDstring>      </IDstring> // : Alphanumeric identificator
                <Name>          </Name>     // : Name of the device
                <Class>         </Class>    // : Type of device
                <Family>        </Family>   // : Groups of devices
                <Beat>          </Beat>     // : Message to the world "I´m Alive"
                <Message>       </Message>  // : Message 200 char.
            
            </minimaldata>
        </imalive>

There is not ANY PERSONAL DATA in this scheme.


<h3>RESUME</h3>

Amagi Project ----> Amagi Network Project ----> Amagi Server ----> Amagi Data Protocol ----> IMALIVE Data
