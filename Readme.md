Develop a cli application that brings up auto-scalable Nginx servers installed in a VPC.
Guidelines:
● This task is expected to be run against AWS
● Use terraform to perform this task. Ensure you generate the template programmatically.
 ● Feel free to use any language you are comfortable with
 ● Submit the code via access to a private git repository or zip file attachment.
 ● Provide a README (how to install, use, design decisions, etc.)
 ● I should be able to follow the README and launch this in my AWS The cli should,
 ● show the progress/logs on issuing the command
 ● have the facility to specify for the instance type. Use your judgment for other additional configuration options
 ● print the Application load balancer URL as output. On visiting the URL, we should be able to view the default Nginx page
 ● create the setup that c an autoscale
 ● handle credentials missing or any other error gracefully (and not crash)
Example:
myNginxCommand --name nginx1 --vpcId XXXXXXXXXXXXXXXX --instanceType t2.medium --subnetId XXXXXXXXXX --securityGroup XXXXXXXXXX (please add more arguments as you see fit)