This Playbook is used to SetUp Kubernetes Cluster in EC2 Instance's running on AWS cloud.

📌 Ansible Role to Configure K8S Multi-Node Cluster over AWS Cloud.
🔅 Create Ansible Playbook to launch 3 AWS EC2 Instance
🔅 Create Ansible Playbook to configure Docker over those instances.
🔅 Create Playbook to configure K8S Master, K8S Worker Nodes on the above created EC2 Instances using kubeadm.
🔅 Convert Playbook into roles and Upload those roles on your Ansible Galaxy.
🔅 Also, Upload all the YAML code over your GitHub Repository.
🔅 Create a README.md document using markdown language describing your Task in a creative manner.


✔ Requirements:

Access Key : **********
Secrete Key : ***********
Put both Key of your AWS account in the files name (aws_key.yml), and include this file name inside the Playbook


This Playbook, Launch 3 Instance's, 1 for Master node and 2 Instance's for Worker node/ After Launching, it setUp Kubernetes Cluster over those Instance's.
