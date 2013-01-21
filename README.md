The Amagi Project
=================




I´m alive... :-)

The user creates the network...





What is "Amagi Project" ?
-------------------------------

Code was first..
    
    <?xml version="1.0"?>
    <amagi>
        <target>Back to the mother</target>
        <creator>human</creator>
    </amagi>

The Amagi Project, created with the aim of spreading the values of free hardware and software,
as well as its use to create free networks.




<h3>Amagi equation</h3>
_______________________


[[ Free Hardware + Free OS ] + Free Software Apps ] + [ Free Networks ] + [ Open Data ] = Free World



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

    - are free hardware running
    - have a free operative system running
    - have free software apps running
    - are connected to a free network
    - send opendata to an Amagi Server (AMAGI Data Protocol)


Devices List :

    - Embebbed Systems ( Raspberry Pi, BeagleBoard, Arduino.. )
    - Phones
    - Tablets
    - Set Top Boxes
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

Protocol that defines communication rules and type of data transmitted between a node and an Amagi Server


What is "Amagi Server" ?
-------------------------------

A computer with Amagi Server Software running, that provides 

    - AmagiOpenData Reception Services
        
        reception of data packets in .AMA format. This paquet defines
            
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



What types of data can send a node ?
-------------------------------

No limits !! ( lie :-(), there are limits, for now...
But it´s not a problem.

You can send the next data groups to the server :


    - Identification and state data group
    - Sensors data group
    - Running Services information data group

As you want.



But, you're required to send ONLY one data group : IMALIVE

IMALIVE

The minimal data group that you need send to connect and use an Amagi Server.
Is like the beating heart of the device.
When you send He's saying 
        
    I'm alive and I'm ready.

Amagi Servers receive all this beats  

IMALIVE contains a minimum data set that the owner of the device available to everyone freely.

With this data contributes to a large network scheme, useful for improving communication among all.

The minimum packet data IMALIVE are:

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

