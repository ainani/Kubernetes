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

Certification Students Tips:
 - https://www.linkedin.com/pulse/my-ckad-exam-experience-atharva-chauthaiwale/
 - https://medium.com/@harioverhere/ckad-certified-kubernetes-application-developer-my-journey-3afb0901014
 - https://github.com/lucassha/CKAD-resources


## Which Certification Should You Choose?
1. Certified Kubernetes Application Developer (CKAD)

Description: The CKAD certification is designed for professionals who are responsible for building, deploying, and configuring cloud-native applications on Kubernetes. It validates your ability to design, build, and deploy applications in a Kubernetes environment.

Key Focus Areas:

    Application Design and Build: Creating containerized applications using best practices.
    Application Deployment: Deploying applications using Kubernetes primitives.
    Configuration: Managing configuration and secrets.
    Multi-Container Pods: Understanding and implementing multi-container pod designs.
    Observability: Monitoring application health and logs.
    Services & Networking: Exposing applications via services.
    State Persistence: Managing stateful applications and persistent volumes.

Ideal for:

    Application Developers: Who want to efficiently use Kubernetes for deploying and managing applications.
    DevOps Engineers: Focused on deploying and managing applications in production environments.
    Software Architects: Designing scalable and resilient application architectures on Kubernetes.

Benefits:

    Demonstrates proficiency in deploying and managing applications on Kubernetes.
    Enhances understanding of cloud-native application patterns.
    Validates skills in modern application deployment methodologies.
    Improves employability in roles requiring Kubernetes application expertise.

2. Certified Kubernetes Administrator (CKA)

Description: The CKA certification is aimed at professionals who manage and administer Kubernetes clusters. It validates your skills in installing, configuring, and managing production-grade Kubernetes clusters.

Key Focus Areas:

    Cluster Installation and Configuration: Setting up Kubernetes clusters from scratch.
    Infrastructure Management: Managing nodes and networking components.
    Workloads and Scheduling: Deploying and managing workloads, understanding scheduling.
    Services and Networking: Configuring cluster networking and services.
    Storage: Managing persistent storage in Kubernetes.
    Troubleshooting: Identifying and resolving issues within the cluster.
    Security: Implementing role-based access control, network policies, and securing cluster components.

Ideal for:

    System Administrators: Responsible for maintaining Kubernetes infrastructure.
    DevOps Engineers: Managing and automating infrastructure operations.
    Site Reliability Engineers (SREs): Ensuring reliability and performance of Kubernetes clusters.
    Infrastructure Architects: Designing and overseeing Kubernetes infrastructure setups.

Benefits:

    Demonstrates deep understanding of Kubernetes cluster operations.
    Validates capability to manage and troubleshoot complex Kubernetes environments.
    Enhances skills in ensuring security and reliability of applications at the infrastructure level.
    Increases opportunities in roles focused on Kubernetes infrastructure management.

### Which Certification Should You Choose?
For a Python Developer:

    CKAD is more suitable as it focuses on application development and deployment within Kubernetes environments.
    It aligns well with developing, containerizing, and deploying Python applications using Kubernetes.
    Enhances your ability to build scalable, resilient, and cloud-native applications.
    Provides practical skills in managing application lifecycles and utilizing Kubernetes features effectively.

For a Python Architect:

    CKAD is beneficial for understanding how to design and deploy applications optimally on Kubernetes.
    CKA can also be valuable if your role involves making decisions about infrastructure, ensuring that applications run smoothly in production, and understanding the underlying Kubernetes architecture.
    Consider pursuing both certifications to gain comprehensive knowledge spanning both application development and infrastructure management, which is particularly useful for architects responsible for end-to-end system design and implementation.

### Additional Considerations

    Career Goals:
        If you aim to specialize in DevOps or full-stack development, understanding both application and infrastructure aspects (CKAD and CKA) can be highly advantageous.
        For roles focused purely on application development, CKAD suffices.

    Market Demand:
        Kubernetes skills are in high demand, and having either certification enhances your employability.
        Assess the specific requirements of the roles you are targeting.

    Complementary Certifications:
        Cloud Provider Certifications: AWS Certified Developer, Google Cloud Professional Cloud Developer, or Azure Developer Associate can complement your Kubernetes certifications.
        Python-Specific Certifications: Such as the PCEP (Certified Entry-Level Python Programmer) or PCAP (Certified Associate in Python Programming) can demonstrate your proficiency in Python.
        DevOps Certifications: Like the Docker Certified Associate or Certified Jenkins Engineer can further strengthen your profile.

    Practical Experience:
        Alongside certifications, hands-on experience is crucial. Engage in personal or open-source projects deploying Python applications on Kubernetes to solidify your skills.
        Contribute to community projects or case studies showcasing your ability to solve real-world problems.

### Conclusion

#### Recommendation:

    Start with CKAD to solidify your application development and deployment skills on Kubernetes, which directly complements your role as a Python Developer.
    Pursue CKA later if you find yourself increasingly involved in infrastructure decisions or wish to broaden your expertise towards a more DevOps or architectural role.

#### Action Plan:

    Enroll in CKAD preparation courses and utilize practice labs to gain hands-on experience.
    Work on projects that involve deploying Python applications using Kubernetes to apply your learning.
    Evaluate your career progression and interests after completing CKAD to decide if pursuing CKA aligns with your goals.
    Keep learning and stay updated with the latest trends and updates in both Python development and Kubernetes ecosystems.


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
