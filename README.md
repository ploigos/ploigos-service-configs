# Ansible Collection - ploigos.service_configs

This collection enables configuration of services to work with [Ploigos](https://ploigos.github.io/ploigos-docs/). These assets can be utilized by the [Ploigos Software Factory Operator](https://github.com/ploigos/ploigos-software-factory-operator), or standalone.

Supported components appear below. See the `playbooks` directory in this collection for usage notes and examples.

### argocd
This role configures an instance of ArgoCD for use with Ploigos. After supplying the relevant properties to the playbook, invoke it with:

```bash
ansible-playbook playbooks/argocd.yml
```

### gitea
This role configures an instance of Gitea for use with Ploigos. Use a playbook like this:

If you're running this locally, the role will print out a **Gitea Access Token** that you'll need to use later. Be sure to store this somewhere safe. After supplying the relevant properties to the playbook, invoke it with:

```bash
ansible-playbook playbooks/gitea.yml
```

### jenkins
This role configures an instance of Gitea for use with Ploigos. This requires a **Gitea Access Token**. After supplying the relevant properties to the playbook, invoke it with:

```bash
ansible-playbook playbooks/jenkins.yml
```

### nexus_artifacts
This role configures an instance of Nexus for use as an artifact repository with Ploigos. After supplying the relevant properties to the playbook, invoke it with:

```bash
ansible-playbook playbooks/nexus_artifacts.yml
```

### nexus_containers
This role configures an instance of Nexus for use as a container registry with Ploigos. After supplying the relevant properties to the playbook, invoke it with:

```bash
ansible-playbook playbooks/nexus_containers.yml
```

### quay
This role configures an instance of Red Hat Quay for use with Ploigos. After supplying the relevant properties to the playbook, invoke it with:

```bash
ansible-playbook playbooks/quay.yml
```

### sonarqube
This role configures an instance of Sonarqube for use with Ploigos. After supplying the relevant properties to the playbook, invoke it with:

```bash
ansible-playbook playbooks/sonarqube.yml
``` 

### tekton
This role configures an instance of Tekton for use with Ploigos. After supplying the relevant properties to the playbook, invoke it with:

```bash
ansible-playbook playbooks/tekton.yml
```
