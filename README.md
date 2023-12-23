<h2>Observing ICMP Traffic<h2>
<img width="787" alt="image" src="https://github.com/Jaxon-S/azure-network-protocols/assets/154096378/8c4ad078-c766-4664-a64e-7a05528ad92d">

<p>
Use Remote Desktop to connect to your Windows 10 Virtual Machine
Within your Windows 10 Virtual Machine and install Wireshark
</p>

<img width="586" alt="image" src="https://github.com/Jaxon-S/azure-network-protocols/assets/154096378/0809b896-5025-43da-a6ff-a253b1fbd38b">


<p>Open Wireshark and filter for ICMP traffic only</p>
<p>Then Retrieve the private IP address of the Ubuntu VM and attempt to ping it from within the Windows 10 VM
</p>
<img width="679" alt="image" src="https://github.com/Jaxon-S/azure-network-protocols/assets/154096378/b1fe8982-ce17-4d05-9b72-a931406e45b8">

<img width="368" alt="image" src="https://github.com/Jaxon-S/azure-network-protocols/assets/154096378/37d925ce-e956-41d5-bf66-bddd1bb4fa21">
<h1>Observe ping requests and replies within WireShark</h1>

<p></p>
<img width="612" alt="image" src="https://github.com/Jaxon-S/azure-network-protocols/assets/154096378/1548b4aa-df95-4b7e-9427-49a174babc82">

<p><h3>From The Windows 10 VM, open command line or PowerShell and attempt to ping a public website (such as www.google.com) and observe the traffic in WireShark (shown above)
</p></h3>






