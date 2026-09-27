# AWS Task-4

## Objective
Implement and demonstrate AWS EC2 and EBS storage operations.

## Tasks Completed

### 1. Linux EC2 Web Server
- Launched an Ubuntu Linux EC2 instance.
- Installed and configured Apache web server.
- Verified Apache service was running.
- Verified HTTP response with status code 200.

### 2. Windows EC2 Web Server
- Launched a Windows EC2 instance.
- Installed IIS Web Server.
- Verified World Wide Web Publishing Service (W3SVC) was running.
- Verified HTTP response with status code 200.

### 3. EBS Volume
- Created a 5 GiB General Purpose SSD (gp3) EBS volume.
- Attached the EBS volume to the Linux EC2 instance.
- Verified the 5 GiB disk from Linux using `lsblk`.
- Detached the volume and attached it to the Windows EC2 instance.
- Verified the 5 GiB disk from Windows using `Get-Disk`.

### 4. EBS Snapshot
- Created an EBS snapshot from the 5 GiB volume.
- Verified the snapshot completed successfully at 100%.

### 5. Volume from Snapshot
- Created a new 5 GiB EBS volume from the completed snapshot.
- Verified the new volume was created successfully.

## AWS Services Used
- Amazon EC2
- Amazon EBS
- EBS Snapshots
- Apache HTTP Server
- Microsoft IIS

## Evidence
Screenshots demonstrating the completed tasks are included in this repository.
