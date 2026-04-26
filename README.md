# zero-trust-network-implementation
# Zero Trust Network Implementation

## Project Title
Implementing Zero Trust Principles in a Local Network

## Objective
The objective of this project is to implement Zero Trust security principles in a local network environment by segmenting the network and enforcing strict access control policies.

Zero Trust is a security model that assumes no user or device is trusted by default, even if they are inside the network perimeter.

## Zero Trust Principles Implemented

1. Network Segmentation
2. Identity Verification
3. Least Privilege Access
4. Continuous Monitoring
5. Access Control Enforcement

## Network Segmentation Design

The network is divided into three segments:

1. Admin Network
2. User Network
3. Guest Network

Each network segment is isolated and controlled using firewall rules.

Admin Network:
- Full system access
- Management privileges

User Network:
- Limited access to internal services
- No administrative control

Guest Network:
- Internet access only
- No access to internal resources

  Technologies Used

- Firewall configuration
- Access Control Lists (ACL)
- VLAN segmentation
- Authentication policies

## Zero Trust Implementation Steps

Step 1:
Verify identity before granting access.

Step 2:
Segment the network into separate zones.

Step 3:
Apply least privilege access rules.

Step 4:
Monitor all network activity.

Step 5:
Log authentication and access attempts.

 Security Policies

- All users must authenticate before access
- Devices must be verified
- Access is restricted based on role
- Unauthorized access is blocked
- Logs are recorded for monitoring

## Conclusion

This project demonstrates how Zero Trust security principles can be applied to a local network environment to improve security through segmentation and strict access control.
