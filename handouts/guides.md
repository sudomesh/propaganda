# welcome to the mesh (0 to 60 mph in 3 seconds)  
## What's the mesh? And why do we need one?  
The mesh is a decentralized network of computers (or nodes). A mesh is useful because there is no single point of failure. If an individual node goes down, the mesh network will still work. Also, because there is no central node that needs to exist for the network to function, the ownership of the network is shared between all the nodes.

## What are nodes? And how do I get one?  
In the peoplesopen.net mesh network, nodes are wireless routers (like MyNet N600s). Normally, these routers are configured to connect a LAN (your local network) to the WAN (the internet) using your ISP's infrastructure. In a mesh configuration, the routers also talk to each other, creating a third, intermediary network that we call the MAN (mesh area network). This MAN connects nodes that are physically near each other. If you'd like to host a node on the People's Open Network, please get a compatible router and flash it with the appropriate firmware build (see guide on reverse side).

## Ok, but I want to help out more?  
Glad to hear! Continue to the roles section below to see how you can get more involved.   

# roles  
Mesh networks don't happen by themselves, they require a ton of effort and a lot of collaboration. If you would like to help out, there are a few general roles that anyone (with the right motivation) can fulfill.  
## Community Organizer and/or Educator  
Are you a people person? Would you like to help our network expand and provide access to those who need it most? Use your social skills to help get the word out. Talk to neighbors and local businesses about setting up a node in their buildings. Help plan events that raise awarness of community networks. (events, outreach, press, education)  
## Legalistics and Grant Writing
Do you have expertise in law? Or are you good writer? Help us join the fight for digital liberties and equitable access to information. See more about our legal efforts at https://sudoroom.org/wiki/Mesh/Legal
## Design and UX
Are you artiscally inclined? There are multiple aspects of mesh networks that require creative design skills. Help improve our propaganda, re-design user interfaces, or create new diagrams and infographics. Current designs can be found at https://github.com/sudomesh/propaganda
## Technical Support   
Do you like scaling tall buildings? Are you a skilled troubleshooter? Help provide day-to-day management and maintenance of the mesh. Assist in the deployment of nodes and roof-mounted antennae! If you'd like to join the node mounting crew, e-mail us at nodemount@peoplesopen.net.
## Multi-talented Engineer  
Are you a hacker or programmer? Do you know how to use git? Fork our repos, modify some code (or just edit a README), and we'll potentially make you a contributor. If you'd like fulfill this role, continue to the next section to learn about the technology that drives mesh networks and how you can contribute to our many development projects. (hardware/firmware/software development, monitoring tools)  
 
# educational guides  
If you wish to become involved on a deeper level, there are a handful of educational tools that we have developed to help you acquaint yourself with mesh networks and their associated concepts.  
   
## (Learn) **Deploy an n-node virtual network ([babeld-lab](https://github.com/sudomesh/babeld-lab))** 
This will help you learn about the underlying protocol that controls the flow of information on the mesh. If you want to help troubleshoot potential conflicts in the WAN as the mesh grows, this is the guide for you!  
## (Learn) **Dig a tunnel ([tunneldigger-lab](https://github.com/sudomesh/tunneldigger-lab))** 
Tunnels are dug to connect a nodes in a mesh network with the "big" internet through one or more exit nodes. Also, the tunnels are used to propagate babeld messages to help nodes discover each other. So, in a way, nodes dig tunnels to an exit node to create a VPMS (a virtual private mesh network). The VPMS prevent ip addresses of individual node operators to be exposed on the "big" internet and help individual nodes to mesh with one another even if they are out of range.
## (Build) **Create your own physical node ([firmware flash walkthough](https://sudoroom.org/wiki/Mesh/WalkThrough))**  
This will help you learn about the deployment of our custom firmware and its associated hardware. If you want to get involved in the deployment and maintenance of indivdual nodes, want to contribute to the improvement of the firmware or hardware, or just want to deploy your own node, this is the guide for you! This process also registers your node with peoplesopen.net . 
## (Teach) **Help a friend or a neighbor work through this guide and grow the mesh network.** 
This will help build out the mesh and learn about the point-to-point wireless connections that are the backbone of any true mesh network. If you want to help build out the mesh in your community or help do the same in other communities, this is the guide for you! 
## (Improve) **Help the project evolve** 
Report and fix bugs; suggest, research, and develop new features; deploy nodes; educate your peers; improve the documentation; and perhaps start your own mesh network!
 
# ongoing projects  
* Deploying a proof-of-concept test network 
* Hosting services on the mesh, such as static copies of web pages, etherpad instance, weather reporting, local commodity exchange
* Building collaborative resource for community network projects, https://buildyourowninter.net
* Disaster Radio collaboration with Secure Scuttlebutt, https://disaster.radio 
* Garden Mesh colloboration with Counter Culture Labs, https://peoplesopen.net/gardenmesh 
* Help plan the next BYOI workshop! Maybe it could take place in your neighborhood?
