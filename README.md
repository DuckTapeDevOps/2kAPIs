# 2kAPIs


APIs built to help run NBA2K pro-am leagues

# Tech Stack

![Alt Text](./media/images/surprise-whats-in-the-box.gif)

- Discord
- Docker
- Python
- Flask
- Terraform
- AWS
  - Lambda
  - API Gateway
    - Lambda Authroizer
  - CloudFront
    - Lambda @Edge
  - Load Balancing
    - Network Load Balancer
    - SSL Termination
  - Cognito Single Sign-on
  - Route53, VPC, Subnets
- Open Ziti/Cloud Ziti
  - BrowZer

------

## Brain Dump

![Alt Text](./media/images/ThisIsFine.jpeg)

10s lobbies
- Sign up for 10s
  - Position
	- Python Dict
		- Time stamp
		- position
		- discord/xbox name
		- Have a team?
		- Coach?
	- Auto invite to Discord channel and join via Xbox?
		- Once 10 players, 5 from each position are signed up create 2 temporary channels
			- Channel Name: |ACTIVITY|-|UID|-|HOME/AWAY|-|Timestamp|
			- Team Owner
						
		- XBL.io xbox party invites

SIBA-TV

---
![Alt Text](./media/images/dumpsterfire-dumpster.gif)

