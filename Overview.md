**VMware Cloud on AWS:**
(VMC on AWS) is a managed cloud offering that provides dedicated VMware vSphere-based Software Defined Data Centers (SDDC) that are hosted within AWS facilities. it is a managed service.

Key Points Before Start VMS on AWS: 
1. The service utilizes facilities and hardware that are owned and managed by AWS
2. The service provides dedicated, private cloud environments in the form of an SDDC.
3. Hosts of an SDDC are dedicated to that SDDC
4. SDDCs are deployed within a *VMware-owned AWS account*, not a *customer-owned AWS account*.
5. SDDCs have high-speed access to native AWS services hosted within a separate customer-owned AWS account.
6. Native AWS services are billed to the customer-owned AWS account and are not managed by VMware.

7. Customer will not get the admin access of Hyperviser (Esxi).

**Key Takeaways of an SDDC:**

1. An SDDC is deployed on dedicated, bare-metal hosts
2. An SDDC is Deployed with standard components (ESXi, vCenter, NSX, and vSAN).
3. Billing is based on the number of hosts within the SDDC, not on the number of VMs. (Same as aws dedicated host).
4. Users have the ability to manage their workloads but have limited access to vCenter, vSAN, and NSX


