# Assignment 2 Submission

<!--
How to use this template:

1. Copy this file to submissions/assignment-2/<your-github-username>/submission.md
2. Replace every answer placeholder with your own answer. Delete the angle brackets too.
3. Save your four images in the same folder, with the exact file names below.
4. Do not write your full name or your student number in this file.
-->

## About me

- GitHub username: RalphEspartero3
- Section: IV-CCSAD
- IAM user name that I signed in with: ccsad-g02
- X: 108

---

## Part A. Explore

### A1. The VPC

Default VPC IPv4 CIDR:

172.31.0.0/16

Number of addresses in that CIDR:

65,536

### A2. The subnets

| Availability Zone | IPv4 CIDR |
| --- | --- |
| ap-southeast-1a | 172.31.32.0/20 |
| ap-southeast-1b | 172.31.16.0/20 |
| ap-southeast-1c | 172.31.0.0/20 |

Screenshot 1. Save it as `screenshot-1-subnets.png` in your folder. The image line below shows it.


<img width="1365" height="371" alt="screenshot-1-subnets" src="https://github.com/user-attachments/assets/98136e82-86ba-4a44-9e1d-c38c492ce390" />


### A3. Available addresses

Available IPv4 addresses in each subnet:

<answer>

Why is the number lower than 4,096?

<answer>

What uses the missing address in the subnet with the lowest number?

<answer>

### A4. The route table

| Destination | Target |
| --- | --- |
| <answer> | <answer> |
| <answer> | <answer> |

Screenshot 2. Save it as `screenshot-2-routes.png` in your folder. The image line below shows it.

![Screenshot 2: routes of the route table](screenshot-2-routes.png)

### A5. Public or private

Are the default subnets public or private? Which route proves it?

<answer>

### A6. The internet gateway

State of the internet gateway:

<answer>

What happens to the default subnets if the gateway is detached?

<answer>

### A7. NAT gateways

Number of NAT gateways:

<answer>

Can a server in a new private subnet download updates? Why?

<answer>

### A8. The network ACL

| Rule number | Source | Allow or Deny |
| --- | --- | --- |
| <answer> | <answer> | <answer> |
| <answer> | <answer> | <answer> |

How is a network ACL different from a security group?

<answer>

Screenshot 3. Save it as `screenshot-3-network-acl.png` in your folder. The image line below shows it.

![Screenshot 3: inbound rules of the network ACL](screenshot-3-network-acl.png)

### A9. The default security group

Inbound rule (type and source):

<answer>

Which resources can send traffic to an instance that uses it?

<answer>

---

## Part B. Prepare

### B1. Plan two subnets

- Public subnet CIDR: <answer>
- Private subnet CIDR: <answer>

### B2. Route tables

Route table of the public subnet:

| Destination | Target |
| --- | --- |
| <answer> | <answer> |
| <answer> | <answer> |

Route table of the private subnet:

| Destination | Target |
| --- | --- |
| <answer> | <answer> |

### B3. My VPC diagram

Tool used (Excalidraw, draw.io, Lucidchart, or paper):

<answer>

Save your diagram as `vpc-diagram.png` in your folder. The image line below shows it.

![B3: my VPC diagram](vpc-diagram.png)

### B4. Predict a change

Can you still open the web page from your laptop? Why?

<answer>

Can the instance still reach another instance in the VPC? Why?

<answer>

### B5. Place a database

Which subnet gets the database? Why?

<answer>

### B6. My question about VPCs

What is your question, and what made you think of it?

<answer>
