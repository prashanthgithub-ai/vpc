# VIRTUAL PRIVATE CLOUD

VPC stands for Virtual Private Cloud. It’s a service offered by cloud providers like AWS, VPC is a virtual network that closely resembles a traditional network that you'd operate in your own data center. After you create a VPC, you can add subnets.
      
 # 1)subnets:
               Divide your VPC into subnets, which can be public or private. Public subnets are accessible from the internet, while private subnets are not.
# 2) Route Table:
                A set of rules, called routes, that determines where network traffic is directed within a VPC. Each subnet must be associated with a route table to define how traffic is routed.

# 3)Internet Gateway:
                  A VPC component that enables resources within the VPC to communicate with the internet. It allows instances in public subnets to send and receive internet traffic.   
# 4)NETWORK ADDRESS TRASULATION GATEWAY:
                                       Enables instances in private subnets to access the internet for updates and patches, while preventing unsolicited inbound traffic.

# 5)Security Groups and Network :
                                 These act as firewalls to control inbound and outbound traffic to your resources.  
# 6) NETWORK ACCESS CONTROL LISTS:
                                 which are stateful and automatically allow return traffic for allowed inbound traffic, Network ACLs are stateless. This means you must define rules for both inbound and outbound traffic separately.

# 7)VPC FLOW LOGS: 
                  VPC Flow Logs is a feature in Amazon Web Services (AWS) that allows you to capture information about the IP traffic going to and from network interfaces in your Virtual Private Cloud.
                                      
