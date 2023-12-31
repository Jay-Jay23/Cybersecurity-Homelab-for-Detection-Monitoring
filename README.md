# Cybersecurity Homelab For Detection & Monitoring

<p>This home lab has components and tools similar to large-scale infrastructures. Although this will be at a relatively small scale, which will allow me to be able to apply the knowledge gained in a real-world large-scale/enterprise infrastructure</p>

# Network Topology

<img src="https://github.com/Jay-Jay23/Cybersecurity-Homelab-for-Detection-Monitoring/blob/main/images/network%20topology.png" alt="topology">

# Content
<ul>
  <li>VMware Workstation/ VM Virtual box setup</li>
  <li>Setting up Kali Linux as an attack machine</li>
  <li>Setting up Windows 10 client</li>
  <li>Setting a Windows Server as a Domain Controller</li>
  <li>Configuring pfSense firewall for Network Segmentation & Security</li>
  <li>Configuring Security Onion as an all-in-one IDS, Security Monitoring, and Log Management solution</li>
  <li>Configuring Splunk</li>
</ul>


## VMware Workstation/ VM Virtual box setup
- VMware Workstation is a line of Desktop Hypervisor products which lets users run virtual machines, containers and Kubernetes clusters, go throw the following turtorial [VMware Setup](https://www.youtube.com/watch?v=Yc13ixD87G4&pp=ygURaW5zdGFsbGluZyB2bXdhcmU%3D) to get started
- VirtualBox is also a free and feature-rich alternative Hypervisor from Oracle. If you cannot afford the VMware license, VirtualBox is equally good. [Virtual box Setup](https://www.youtube.com/watch?v=-vnQOBRn8BA&pp=ygUjaW5zdGFsbGluZyB2aXJ0dWFsYm94IG9uIHdpbmRvd3MgMTA%3D)
- Both setup are beginner friendly even and will allow you to have a hypervisor ready 

## Setting up Kali Linux as an attack machine
- Kali Linux will be used as an attack machine to propagate different forms of offensive actions against our Active Directory and the other machines attached to it.
- Go to the [official Kali website](https://www.kali.org/get-kali/#kali-platforms) to download a pre built image, allowing for kali linux install without altering the host OS and pick the image based on your installed hypervisor
<img src="https://github.com/Jay-Jay23/Cybersecurity-Homelab-for-Detection-Monitoring/blob/main/images/Get%20Kali.png" alt="kali download">

- After downloading the VM file, all you’ll need to do is to click on the .vmx file from the Kali Folder you downloaded and it will automatically load up the default Kali image in VMware.
<img src="https://github.com/Jay-Jay23/Cybersecurity-Homelab-for-Detection-Monitoring/blob/main/images/kali%20setup.png" alt="kali download">

- After powering on, use this command to change the default password to a more secure one of your choice:
> passwd
<img src="https://github.com/Jay-Jay23/Cybersecurity-Homelab-for-Detection-Monitoring/blob/main/images/kali%20login.png" alt="kali login">

- Then Kali machine is ready for use.

## Setting up Windows 10 

## Setting a Windows Server as a Domain Controller

    
    
   
    
    
    
