A-dock
======

Docker-like Linux containers for ARM appliances

ad hoc

created or done for a particular purpose as necessary.
"the discussions were on an ad hoc basis"

haddock

The haddock (Melanogrammus aeglefinus) is a marine fish distributed on both sides of the North Atlantic. Haddock is a popular food fish and is widely fished commercially.

Introduction
------------

A-dock is a project very similar to and based on Docker, but applied to ARM appliances.

The idea is - similarly to Docker - to facilitate the deployment of applications on diverse hardware, except in this case we are not talking about server hardware or the Cloud, but low-power, mass-manufactured ARM devices running Linux. Also, whereas in the case of Docker the applications deployed are usually multiple interconnected Web apps, in the case of A-dock the idea is to deploy a single appliance-type application per A-dock container.

Just like Docker on which it is based, the A-dock project uses Go as its programming language. Although A-dock is based on Docker, it is not a fork of it, since its purpose is fundamentally different. Docker really caters to developers working on Web apps and companies that host these apps on "heavy iron" server hardware or virtual machines in local or remote data centers ("the Cloud"). A-dock is concerned with deployment of appliance-type applications at the other extreme of the computing spectrum i.e. mass-produced, low power, often diminutive ARM devices - the kind of devices that are usually called "embedded".

Embedded applications development has usually been narrowly associated with dedicated or custom hardware, even when running some form of Linux on the embedded platform, restricting the deployment to a single kind of device or at best to a small selection of compatible devices. A-dock containers are designed to isolate the appliance-type applications development process from the hardware platform on which these applications will be deployed. The usually rather steep learning curve associated with embedded development is avoided in a good part. Also, the hardware/firmware developers of mass-produced ARM devices can focus their efforts on providing a cost-effective, reliable and A-dock container compatible ARM Linux platform, and not have to redesign a different platform for each new appliance application.

So in a way, A-dock containers provide a new paradigm for embedded applications development, separating the appliance application development from the appliance hardware and firmware/system software platforms development.
