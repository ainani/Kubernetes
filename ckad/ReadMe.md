Handy Required Docs:
- https://kubernetes.io/docs/reference/kubectl/overview/
- https://kubernetes.io/docs/reference/kubectl/cheatsheet/


Other Courses:
 - https://www.udemy.com/course/learn-kubernetes/?couponCode=ACCAGE0923
 - https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/?couponCode=ACCAGE0923
 - https://www.udemy.com/course/certified-kubernetes-application-developer/learn/

CNCF Examinations Links:
 - https://docs.linuxfoundation.org/tc-docs/certification/lf-handbook2
 - https://docs.linuxfoundation.org/tc-docs/certification/tips-cka-and-ckad
 - https://www.cncf.io/training/certification/ckad/
Note: Keep the code - 20KLOUD handy while registering for the CKA or CKAD exams at Linux Foundation to get a 20% discount.


Community:
- https://kodekloud.com/pages/community

Tips:
 - https://www.reddit.com/r/kubernetes/comments/13mhozb/ckad_exam_experience_and_tips/



---

| **Kind**                   | **apiVersion**                   | **Description**                                                                                      |
|----------------------------|----------------------------------|------------------------------------------------------------------------------------------------------|
| **Pod**                    | `v1`                             | The smallest and simplest Kubernetes object. Represents a single instance of a running process.      |
| **ReplicaSet**             | `apps/v1`                        | Ensures that a specified number of pod replicas are running at any given time.                       |
| **Deployment**             | `apps/v1`                        | Manages ReplicaSets to ensure that the correct number of pods are running.                           |
| **StatefulSet**            | `apps/v1`                        | Manages the deployment and scaling of a set of Pods, providing guarantees about ordering and uniqueness. |
| **DaemonSet**              | `apps/v1`                        | Ensures that all (or some) nodes run a copy of a Pod.                                                |
| **Job**                    | `batch/v1`                       | Creates one or more pods and ensures that a specified number of them successfully terminate.          |
| **CronJob**                | `batch/v1`                       | Manages time-based Job scheduling.                                                                   |
| **Service**                | `v1`                             | Exposes a set of Pods as a network service.                                                          |
| **Ingress**                | `networking.k8s.io/v1`           | Manages external access to services, usually HTTP.                                                   |
| **ConfigMap**              | `v1`                             | Provides configuration data to pods.                                                                 |
| **Secret**                 | `v1`                             | Stores sensitive information such as passwords, OAuth tokens, and SSH keys.                          |
| **PersistentVolume**       | `v1`                             | Represents a piece of storage in the cluster that has been provisioned by an administrator.          |
| **PersistentVolumeClaim**  | `v1`                             | A request for storage by a user that dynamically provisions storage resources.                       |
| **Namespace**              | `v1`                             | Provides a mechanism for isolating groups of resources within a single cluster.                      |
| **Node**                   | `v1`                             | Represents a worker node in Kubernetes.                                                              |
| **ServiceAccount**         | `v1`                             | Associates a Kubernetes Pod with a specific set of permissions.                                      |
| **Role**                   | `rbac.authorization.k8s.io/v1`   | Grants access to resources within a single namespace.                                                |
| **RoleBinding**            | `rbac.authorization.k8s.io/v1`   | Associates a Role with a set of users or groups.                                                     |
| **ClusterRole**            | `rbac.authorization.k8s.io/v1`   | Grants access to resources cluster-wide.                                                             |
| **ClusterRoleBinding**     | `rbac.authorization.k8s.io/v1`   | Associates a ClusterRole with a set of users or groups across the entire cluster.                    |
| **NetworkPolicy**          | `networking.k8s.io/v1`           | Controls the traffic flow to/from Kubernetes Pods.                                                   |
| **ResourceQuota**          | `v1`                             | Limits the amount of resources that a namespace can use.                                             |
| **LimitRange**             | `v1`                             | Specifies limits to the resource usage for containers within a namespace.                            |
| **HorizontalPodAutoscaler**| `autoscaling/v1`                 | Automatically scales the number of pods based on observed CPU utilization or other application metrics. |
| **EndpointSlice**          | `discovery.k8s.io/v1`            | A scalable API for discovering network endpoints.                                                    |
