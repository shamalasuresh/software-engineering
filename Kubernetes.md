## Commands

### Resource

| Command                | Description                                       |
| ---------------------- | ------------------------------------------------- |
| `kubectl create`       | Create a resource from file, stdin, or JSON/YAML. |
| `kubectl get`          | Display one or many resources.                    |
| `kubectl describe`     | Show details of a specific resource.              |
| `kubectl delete`       | Delete resources by various selectors.            |
| `kubectl apply`        | Apply a configuration to a resource.              |
| `kubectl edit`         | Edit a resource on the server.                    |
| `kubectl exec`         | Execute a command in a container.                 |
| `kubectl logs`         | Print logs for a container in a pod.              |
| `kubectl port-forward` | Forward local ports to a pod.                     |
| `kubectl rollout`      | Manage the rollout of a resource.                 |
| `kubectl proxy`        | Run a proxy to Kubernetes API server.             |

### Node

| Command                  | Description                                |
| ------------------------ | ------------------------------------------ |
| `kubectl get nodes`      | Display nodes in the cluster.              |
| `kubectl describe nodes` | Show details of a specific node.           |
| `kubectl cordon`         | Mark node as unschedulable.                |
| `kubectl drain`          | Drain node in preparation for maintenance. |
| `kubectl uncordon`       | Mark node as schedulable.                  |
| `kubectl label`          | Update the labels on a node.               |

### Network

| Command                     | Description                                                                               |
| --------------------------- | ----------------------------------------------------------------------------------------- |
| `kubectl expose`            | Expose a replication controller, service, deployment, or pod as a new Kubernetes Service. |
| `kubectl get services`      | Display services within the cluster.                                                      |
| `kubectl describe services` | Show details of a specific service.                                                       |
| `kubectl port-forward`      | Forward local ports to a pod.                                                             |
| `kubectl proxy`             | Run a proxy to Kubernetes API server.                                                     |
| `kubectl exec`              | Execute a command in a container.                                                         |
| `kubectl run`               | Run a particular image on the cluster.                                                    |

### Namespace

| Command                       | Description                                                  |
| ----------------------------- | ------------------------------------------------------------ |
| `kubectl create namespace`    | Create a new namespace.                                      |
| `kubectl get namespaces`      | Display namespaces within the cluster.                       |
| `kubectl describe namespaces` | Show details of a specific namespace.                        |
| `kubectl delete namespace`    | Delete a namespace and its resources.                        |
| `kubectl apply -f`            | Apply a configuration to a resource in a specific namespace. |

### Pod

| Command                 | Description                                        |
| ----------------------- | -------------------------------------------------- |
| `kubectl get pods`      | Display pods in the cluster.                       |
| `kubectl describe pods` | Show details of a specific pod.                    |
| `kubectl logs`          | Print logs for a container in a pod.               |
| `kubectl exec`          | Execute a command in a container.                  |
| `kubectl port-forward`  | Forward local ports to a pod.                      |
| `kubectl attach`        | Attach to a running container.                     |
| `kubectl cp`            | Copy files and directories to and from containers. |
| `kubectl top`           | Display Resource (CPU/Memory/Storage) usage.       |

### Service

| Command                     | Description                                                                               |
| --------------------------- | ----------------------------------------------------------------------------------------- |
| `kubectl expose`            | Expose a replication controller, service, deployment, or pod as a new Kubernetes Service. |
| `kubectl create service`    | Create a new service.                                                                     |
| `kubectl get services`      | Display services within the cluster.                                                      |
| `kubectl describe services` | Show details of a specific service.                                                       |
| `kubectl delete service`    | Delete a service.                                                                         |

### Configuration

| Command            | Description                                  |
| ------------------ | -------------------------------------------- |
| `kubectl apply -f` | Apply a configuration to a resource.         |
| `kubectl diff`     | View changes in configuration.               |
| `kubectl rollout`  | Manage the rollout of a resource.            |
| `kubectl scale`    | Change the number of replicas of a resource. |
| `kubectl set`      | Set specific features on a resource.         |

### Storage

| Command                | Description                                |
| ---------------------- | ------------------------------------------ |
| `kubectl create pv`    | Create a persistent volume.                |
| `kubectl get pv`       | Display persistent volumes.                |
| `kubectl describe pv`  | Show details of a persistent volume.       |
| `kubectl delete pv`    | Delete a persistent volume.                |
| `kubectl create pvc`   | Create a persistent volume claim.          |
| `kubectl get pvc`      | Display persistent volume claims.          |
| `kubectl describe pvc` | Show details of a persistent volume claim. |
| `kubectl delete pvc`   | Delete a persistent volume claim.          |

### Secret and ConfigMap

| Command                      | Description                             |
| ---------------------------- | --------------------------------------- |
| `kubectl create secret`      | Create a secret.                        |
| `kubectl get secrets`        | Display secrets within the cluster.     |
| `kubectl describe secret`    | Show details of a specific secret.      |
| `kubectl delete secret`      | Delete a secret.                        |
| `kubectl create configmap`   | Create a config map.                    |
| `kubectl get configmaps`     | Display config maps within the cluster. |
| `kubectl describe configmap` | Show details of a specific config map.  |
| `kubectl delete configmap`   | Delete a config map.                    |

### Namespace Context

| Command                          | Description                             |
| -------------------------------- | --------------------------------------- |
| `kubectl config get-contexts`    | Display the list of contexts.           |
| `kubectl config current-context` | Show the current context.               |
| `kubectl config use-context`     | Set the current context.                |
| `kubectl config set-context`     | Set a context entry in kubeconfig.      |
| `kubectl config delete-context`  | Delete a context entry from kubeconfig. |

### Role-Based Access Control (RBAC)

| Command                        | Description                               |
| ------------------------------ | ----------------------------------------- |
| `kubectl create role`          | Create a role.                            |
| `kubectl create rolebinding`   | Create a role binding.                    |
| `kubectl get roles`            | Display roles within the cluster.         |
| `kubectl describe role`        | Show details of a specific role.          |
| `kubectl get rolebindings`     | Display role bindings within the cluster. |
| `kubectl describe rolebinding` | Show details of a specific role binding.  |
| `kubectl delete role`          | Delete a role.                            |
| `kubectl delete rolebinding`   | Delete a role binding.                    |

### DaemonSet

| Command                      | Description                             |
| ---------------------------- | --------------------------------------- |
| `kubectl get daemonsets`     | Display daemon sets within the cluster. |
| `kubectl describe daemonset` | Show details of a specific daemon set.  |
| `kubectl create daemonset`   | Create a new daemon set.                |
| `kubectl delete daemonset`   | Delete a daemon set.                    |
| `kubectl rollout daemonset`  | Manage the rollout of a daemon set.     |

### Job and CronJob

| Command                    | Description                           |
| -------------------------- | ------------------------------------- |
| `kubectl get jobs`         | Display jobs within the cluster.      |
| `kubectl describe job`     | Show details of a specific job.       |
| `kubectl create job`       | Create a new job.                     |
| `kubectl delete job`       | Delete a job.                         |
| `kubectl get cronjobs`     | Display cron jobs within the cluster. |
| `kubectl describe cronjob` | Show details of a specific cron job.  |
| `kubectl create cronjob`   | Create a new cron job.                |
| `kubectl delete cronjob`   | Delete a cron job.                    |

### StatefulSet

| Command                        | Description                               |
| ------------------------------ | ----------------------------------------- |
| `kubectl get statefulsets`     | Display stateful sets within the cluster. |
| `kubectl describe statefulset` | Show details of a specific stateful set.  |
| `kubectl create statefulset`   | Create a new stateful set.                |
| `kubectl delete statefulset`   | Delete a stateful set.                    |
| `kubectl rollout statefulset`  | Manage the rollout of a stateful set.     |

### Horizontal Pod Autoscaler (HPA)

| Command                | Description                                           |
| ---------------------- | ----------------------------------------------------- |
| `kubectl get hpa`      | Display horizontal pod autoscalers.                   |
| `kubectl describe hpa` | Show details of a specific horizontal pod autoscaler. |
| `kubectl create hpa`   | Create a new horizontal pod autoscaler.               |
| `kubectl delete hpa`   | Delete a horizontal pod autoscaler.                   |

### ServiceAccount

| Command                           | Description                                  |
| --------------------------------- | -------------------------------------------- |
| `kubectl create serviceaccount`   | Create a service account.                    |
| `kubectl get serviceaccounts`     | Display service accounts within the cluster. |
| `kubectl describe serviceaccount` | Show details of a specific service account.  |
| `kubectl delete serviceaccount`   | Delete a service account.                    |

### Network Policy

| Command                          | Description                                  |
| -------------------------------- | -------------------------------------------- |
| `kubectl get networkpolicies`    | Display network policies within the cluster. |
| `kubectl describe networkpolicy` | Show details of a specific network policy.   |
| `kubectl create networkpolicy`   | Create a new network policy.                 |
| `kubectl delete networkpolicy`   | Delete a network policy.                     |

### Volume

| Command                   | Description                         |
| ------------------------- | ----------------------------------- |
| `kubectl get volumes`     | Display volumes within the cluster. |
| `kubectl describe volume` | Show details of a specific volume.  |
| `kubectl create volume`   | Create a new volume.                |
| `kubectl delete volume`   | Delete a volume.                    |

### Pod Security Policies (PSP)

| Command                | Description                                       |
| ---------------------- | ------------------------------------------------- |
| `kubectl get psp`      | Display pod security policies within the cluster. |
| `kubectl describe psp` | Show details of a specific pod security policy.   |
| `kubectl create psp`   | Create a new pod security policy.                 |
| `kubectl delete psp`   | Delete a pod security policy.                     |

### Endpoint 

| Command                      | Description                           |
| ---------------------------- | ------------------------------------- |
| `kubectl get endpoints`      | Display endpoints within the cluster. |
| `kubectl describe endpoints` | Show details of a specific endpoint.  |
| `kubectl create endpoints`   | Create new endpoints.                 |
| `kubectl delete endpoints`   | Delete endpoints.                     |

### Certificate 

| Command                        | Description                              |
| ------------------------------ | ---------------------------------------- |
| `kubectl get certificates`     | Display certificates within the cluster. |
| `kubectl describe certificate` | Show details of a specific certificate.  |
| `kubectl create certificate`   | Create a new certificate.                |
| `kubectl delete certificate`   | Delete a certificate.                    |

### Priority and Preemption

| Command                          | Description                                  |
| -------------------------------- | -------------------------------------------- |
| `kubectl get priorityclasses`    | Display priority classes within the cluster. |
| `kubectl describe priorityclass` | Show details of a specific priority class.   |
| `kubectl create priorityclass`   | Create a new priority class.                 |
| `kubectl delete priorityclass`   | Delete a priority class.                     |

### Role and ClusterRole

| Command                        | Description                               |
| ------------------------------ | ----------------------------------------- |
| `kubectl create role`          | Create a role.                            |
| `kubectl get roles`            | Display roles within the cluster.         |
| `kubectl describe role`        | Show details of a specific role.          |
| `kubectl delete role`          | Delete a role.                            |
| `kubectl create clusterrole`   | Create a cluster role.                    |
| `kubectl get clusterroles`     | Display cluster roles within the cluster. |
| `kubectl describe clusterrole` | Show details of a specific cluster role.  |
| `kubectl delete clusterrole`   | Delete a cluster role.                    |

### Namespace Role Binding

| Command                        | Description                               |
| ------------------------------ | ----------------------------------------- |
| `kubectl create rolebinding`   | Create a role binding within a namespace. |
| `kubectl get rolebindings`     | Display role bindings within a namespace. |
| `kubectl describe rolebinding` | Show details of a specific role binding.  |
| `kubectl delete rolebinding`   | Delete a role binding within a namespace. |

### Custom Resource Definition (CRD)

| Command                | Description                                    |
| ---------------------- | ---------------------------------------------- |
| `kubectl get crd`      | Display Custom Resource Definitions (CRDs).    |
| `kubectl describe crd` | Show details of a specific CRD.                |
| `kubectl create crd`   | Create a new Custom Resource Definition (CRD). |
| `kubectl delete crd`   | Delete a Custom Resource Definition (CRD).     |

### Horizontal Pod Autoscaler (HPA)

| Command                                    | Description                                |
| ------------------------------------------ | ------------------------------------------ |
| `kubectl get horizontalpodautoscaler`      | Display Horizontal Pod Autoscalers (HPAs). |
| `kubectl describe horizontalpodautoscaler` | Show details of a specific HPA.            |
| `kubectl create horizontalpodautoscaler`   | Create a new HPA.                          |
| `kubectl delete horizontalpodautoscaler`   | Delete an HPA.                             |

### Resource Quota

| Command                          | Description                                 |
| -------------------------------- | ------------------------------------------- |
| `kubectl get resourcequotas`     | Display resource quotas within the cluster. |
| `kubectl describe resourcequota` | Show details of a specific resource quota.  |
| `kubectl create resourcequota`   | Create a new resource quota.                |
| `kubectl delete resourcequota`   | Delete a resource quota.                    |

### PersistentVolumeClaim (PVC)

| Command                                  | Description                      |
| ---------------------------------------- | -------------------------------- |
| `kubectl get persistentvolumeclaims`     | Display PVCs within the cluster. |
| `kubectl describe persistentvolumeclaim` | Show details of a specific PVC.  |
| `kubectl create persistentvolumeclaim`   | Create a new PVC.                |
| `kubectl delete persistentvolumeclaim`   | Delete a PVC.                    |

### Event

| Command                  | Description                        |
| ------------------------ | ---------------------------------- |
| `kubectl get events`     | Display events within the cluster. |
| `kubectl describe event` | Show details of a specific event.  |

### Ingress

| Command                    | Description                           |
| -------------------------- | ------------------------------------- |
| `kubectl get ingress`      | Display ingresses within the cluster. |
| `kubectl describe ingress` | Show details of a specific ingress.   |
| `kubectl create ingress`   | Create a new ingress.                 |
| `kubectl delete ingress`   | Delete an ingress.                    |

### Pod Disruption Budget (PDB)

| Command                                | Description                      |
| -------------------------------------- | -------------------------------- |
| `kubectl get poddisruptionbudgets`     | Display PDBs within the cluster. |
| `kubectl describe poddisruptionbudget` | Show details of a specific PDB.  |
| `kubectl create poddisruptionbudget`   | Create a new PDB.                |
| `kubectl delete poddisruptionbudget`   | Delete a PDB.                    |

### LimitRange

| Command                       | Description                             |
| ----------------------------- | --------------------------------------- |
| `kubectl get limitranges`     | Display LimitRanges within the cluster. |
| `kubectl describe limitrange` | Show details of a specific LimitRange.  |
| `kubectl create limitrange`   | Create a new LimitRange.                |
| `kubectl delete limitrange`   | Delete a LimitRange.                    |

