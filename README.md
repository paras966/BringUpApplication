# BringUpApplication

## Ways to bring Up the Application
- 	1. Docker Compose
- 	2. Ansible

### Docker-Compose
```
git clone https://github.com/paras966/BringUpApplication.git
docker-compose -f BringUpApplication/DockerComposeApplication.yml up
docker-compose -f BringUpApplication/DockerComposeKafkaProducer.yml up [to produce data onto kafka topic]
```

### Ansible
```
git clone https://github.com/paras966/BringUpApplication.git
ansible-playbook BringUpApplication/AnsibleApplication.yml
ansible-playbook BringUpApplication/AnsibleKafkaProducer.yml![image](https://github.com/paras966/BringUpApplication/assets/66049390/388273bf-b1f7-4513-8781-135e6b3a15bf)
```
