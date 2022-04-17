Intro of TRP

Check the Daily status. Wheather all the flow has been completed or not. Else we should resume the job or inform to the Respective Team.
Once came to Morning shift, first will check the Daily_Check_list that we have. And will prepare the documents for the Important flow details.
We have Four Environment. Among that we are working with teo Environment QUAL & PROD.
Here we will check the data's like Maximum Report Date has been updated or not. Else we will do the Route around as per the concepts.
Chekking the file status at S3 for both the Environment, like the files are arrived or not by the cut-off time is 3P.M IST. Else will update to the Respective team.
Start the monitoring by Every morning like is there any Yesterday's files were or not. If files there means will complete and update to the team.
Other Activities Like Manually Triggering the Jobs and Resume the Jobs at AIRFLOW.
Pusiny the files to S3 if the files were not yet Received.
End of the day, preparing the Sanity_check_Report for QUAL & PROD Environment and send to the Clients.
Currently we assign for New Task by the client, Analysing the EMR for QUAL Environment.

here end to end pipeline we going to setup.
in that, which region or which zone should create the services like s3, emr (any particular region)
client team is already processing the pipeline setup. Now they did 1st stage and third stage completed from their side, as same we also completed the 1 & 3 stage.
so, we should work the pipeline setup with them  or we should create the pipelines by ours.
In the Discussion doc KT plan, we need some more clarity on the topics, so better some one will help on these topics for better clarity.
to which team we should connect for any quries or which team we should to work co-ordinate.
once we complete the stages we need some supporting people to integrated the two services. for this we need one people to work with us like already done these service previsously.
we need one people to report our regular activities

what is our task, what is our process. what is the day to day activities

once crawler added, after that if again files has been added at s3, we need to run crawler manually to add table at athena. so how to rectify this?



###Terrafrom###
 sudo apt update
    2  sudo apt-get install wget unzip -y
    3  sudo wget https://releases.hashicorp.com/terraform/0.12.18/terraform_0.12.18_linux_amd64.zip
    4  sudo unzip terraform_0.12.18_linux_amd64.zip
    5  sudo mv terraform /usr/local/bin/
    6  terraform -v
    7  sudo apt update
    8  cd ec2/
   10  terraform init
    sudo terraform validate
   17  cd ec2/
   23  vim main.tf
   25  cat main.tf
   26  terraform init
   28  terraform -v
   30  sudo  apt upgrade terraform
   33  sudo apt install brew
   37  sudo terraform 0.12upgrade
   41  sudo mkdir eks
   42  cd eks/
   43  sudo vim mai.tf
   44   
   45  sudo apt update
   46   
   47  ls
   48  cd ec2/
   51  terraform statelist
   52  terraform state list
   61  cd ec2/
   62  ls
   64  sudo terraform state list
   65  sudo terraform import aws_instance.myfirstfile i-06358fafb71f4e657
   66  sudo terraform import aws_instance.myfirstfile1 i-06358fafb71f4e657
   68  sudo terraform import aws_instance.mynewinstance i-06358fafb71f4e657
   70  sudo terraform import aws_instance.mynewinsstance i-06358fafb71f4e657
   72  sudo terraform import aws_instance.mynewinsstance i-06358fafb71f4e657
   73  cd ec2/
   74  ls
   75  sudo terraform import aws_instance.mynewinsstance i-06358fafb71f4e657
   77  sudo terraform import aws_instance.mynewinsstance i-06358fafb71f4e657
   79  sudo terraform import aws_instance.mynewinsstance i-06358fafb71f4e657
   80  ll
   91  sudu terraform init  
   97  sudo terraform validate
   107  vim main.tf
  108  sudo rm myec2.tf
  109  vim main.tf
  113  sudo vim myfirstfile1.tf
  114  sudo terraform validate
  115  sudo terraform state list
  116  cd
  117  sudo terraform state list
  118  cd ec2/
  119  ls
  120  vi myfirstfile1.tf
  121  sudo terraform import aws_instance.myfirstfile1 i-06358fafb71f4e657
  122  ls
  123  cd ec2/
  124  ll
  125  sudo rm myfirstfile1.tf
  126  sudo vi main.tf
  127  sudo terraform import aws_instance.myfirstfile1 i-06358fafb71f4e657
  128  sudo terraform show
  129  terraform  state list
  130    -target aws_instance.myfirstfile1
  131  cd s3
  132  ls
  136  sudo vim backend 
  141  sudo terraform show
  157  sudo terraform refersh
  167  cd s3/
  175  sudo vim backend.
  180  cd s3/

  208  sudo rm -r .terraform/
  
  211    -lock=false

  213    --auto-approve
  215  sudo terraform forec-unlock DG4QH0JNNCT7FES8K2F9HLTOMFVV4KQNSO5AEMVJF66Q9ASUAAJG
 217    --auto-approve
  224  sudo terraform force-unlock e98629cc434275c7317c1238306ff2f6
  226  sudo terraform  plan
  
  
  ####SBI###
  saving acct:40315873222
priyanga1507
ppf:40316019563

sbin0004651


11642718

06/08/2021

08/11/1994

###certification Question###
How to use Variables in Ansible Playbook
how to pass varible in ansible
Ansible important modules 
how to give RBAC in ansible 
Shell scripting
how to installterraform via ansible
how to give RBAC for k8s
how to add exit resource to current terraform 
how to resize the docker imgae

k8s monitoring tool
configure TLS k8s
Helm chart 

Linux troubleshooting command

why pod is on pending stae
on whar agent jenkings pipeline running
docker diff b/w run cmd
how to attach the linx volume from 50gb to 100gb
how to create node in jenkins(windows)
kubelet purpose?
how the pods has benn sechudled
LVM linux

docker compose file
ansible-- valut, galxy, role,playbook,RBAC, passing variable,tower
terraform-- lock, remote,cloud, rollback,state file, 
k8s-- helm chart, CA, installation, secrt, pv, pvc
promothes
elasticsearch
snowflake
maven
sonarqube

how to use swap memory and its use
how to increase memory space at linux
LVM
api vs rest api

Keyskills : kubernetes,jenkins,docker,Devops
(AWS SAM)


HR@ust.com


python boto3
lamda
terraform scrpitd
Jenkins docker ansible git
kubernates
AWS
elk
nagios vs grafana
snowflake
cloud archict

SDLC vs Devops

life cyle management  ok
aws trusted advisor ok
aws inspector ok
as config ok
aws backup ok
aws x-ray ok 
aws sso
aws datasync ok
aws snowfamily ok
aws transist gateway ok
aws security hub
kms ok
code star
s3 static ok
gaurdDuty
aws cognito
saml
sse-s3 vs sse-kms, sse-c
athena
aws efa
aws sts
cloud formation
storage gateway
aws eks
data migration
step function
aws swf
cron tab
aws s3/sns
Aws RDS DynamoDb
aws certificate manager
directoty services
active directoty
create free domain
cloud9
bastion host
aws data lake

##SecDevOps###
What is the meaning of SOC?
A Security Operation Center (SOC) is a centralized function within an organization employing people, processes, and technology to continuously monitor and 
improvecan organization's security posture while preventing, detecting, analyzing, and responding to cybersecurity incidents

 Static application security testing (SAST), or static analysis,
 is a testing methodology that analyzes source code to find security vulnerabilities that make your organization's applications susceptible to attack.
 
SAST is a type of White Box security testing.  A tester using SAST examines the application from the inside, 
searching its source code for conditions that indicate that a security vulnerability might be present.
 
SAST: code analysis process to check the code for any coding design flaws which could cause an application vulnerability.
 During the analysis, it will identify different security issues like SQL injections, un-sanitized input, error handling,
 static application security testing tools don't need a running application to perform an analysis,
	they can be used early and often in the implementation phase of the software development life cycle (SDLC).
	SAST (static application security testing) is a term used to describe source code analyzers. 
	Such software checks for vulnerabilities by looking for common patterns in the application source code.
	SAST tools are designed for specific languages only and are used only if you build your own applications.
	
A dynamic analysis security testing tool, or a DAST test,  DAST is type of Black Box security testing. which an application is tested from the outside
 is an application security solution that can help to find certain vulnerabilities in web applications while they are running in production.
 (DAST) is a non functional testing process where one can assess an application using certain techniques and the end.
  DAST solutions can be integrated with CI platforms such as Jenkins.
  
  DAST (dynamic application security testing) is a term used to describe vulnerability scanners. 
  Such software tests for vulnerabilities by safely performing automatic penetration testing on a running application, with no access to its source code. 
  DAST is independent of the platform or programming language.
 
 Interactive Application Security Testing (IAST) combines the benefits of black-box and white-box methodologies. grey-box methodolog.
 IAST (interactive application security testing) is a term used to describe software that merges the functionality of DAST and SAST.
 
 Which one is best for me? DAST, SAST, or IAST?
If you build your own applications, the unique AcuSensor IAST will give you the best results. 
If you use third-party applications only (for example, WordPress), you can simply use Acunetix as a DAST tool. 
You can also use an additional SAST tool but keep in mind that SAST tools only work during development, only for specific languages, and report a lot of false positives.
