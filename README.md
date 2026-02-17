# Active Directory Home Lab

## Overview
This lab simulates a small enterprise network using Active Directory.

## Objectives
- Install Windows Server
- Configure AD DS
- Join Windows client to domain
- Apply Group Policy

## Environment
- Hypervisor: VirtualBox
- OS: Windows Server 2025, Windows 11, pfSense
- Services: Active Directory DS, DNS
- Network: Internal + NAT

## Architecture
![Network Diagram](diagrams/network-diagram.pdf)

## Implementation
1. Installed Windows Server
2. Promoted to Domain Controller
3. Joined Windows client to domain
4. Created users and OUs

## Validation
- Client joined to domain
- User logged in successfully
- GPO applied

## Issues & Fixes
**Issue:** Domain join failed  
**Fix:** Corrected DNS settings  

## What I Learned
- DNS is critical for AD
- GPO enforces security policies

## Next Steps
- Configure firewall
- Add monitoring
