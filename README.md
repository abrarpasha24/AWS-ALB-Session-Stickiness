# AWS-ALB-Session-Stickiness
Application Load Balancer (ALB) - Session Stickiness

This repo is about the steps involved in working with ALB session stickiness using an ALB-managed session cookie called AWSALB. It involves several key steps:

# Step 1: APPLY CloudFormation (CFN) Stack
# Step 2: Verify the webserver is running on each instance
# Step 3: Access the load balancer using the DNS Name
# Step 4: Enable session stickiness by navigating to the Target Group.
# Step 5: Verify that your session is locked to one instance and explore the session cookie
# Step 6: Shutdown the instance and confirm you are locked to another instance
# Step 7: Disable Stickiness and confirm sessions are distributed again
