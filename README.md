# Issue tracking

## Known issues

There is a table that should go here.

## Fixed issues

### Version 2.12
#### Version2.12.0

| Internal ID | Description  | Release Version  |
| :----------- | :---------------- | ----------------------|
| RUN-5676    | When Interactive Jupyter notebook workloads that contain passwords are cloned, the password is exposed in the displayed CLI command. | Fixed in 2.9.0<br />Fixed in 2.10.1<br />Fixed in 2.12.0 |
| RUN-5457    | When using the Home environment variable in conjunction with the ran-as-user option in the CLI, the Home environment variable is overwritten with the user's home directory.  | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5370    | It is possible to submit two jobs with the same node-port. | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5314    | When you apply an inference deployment via a file, the allocated GPUs are displayed as 0 in the deployments list. | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5284    | When workloads are deleted while the cluster synchronization is down, there might be a non-existent Job shown in the user interface. The Job cannot be deleted. | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5160    | In some situations, when a Job is deleted, there may be leftover Kubernetes ConfigMaps in the system. | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5154    | In some cases, an error "failed to load data" can be seen in the graphs showing on the Job sidebar. | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5145    | The default Kubernetes "priority Class" for deployments is the same as the priority class for interactive jobs. | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5039    | In some scenarios, Dashboards may show "found duplicate series for the match group" error. | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-4941    | The scheduler is wrongly trying to schedule jobs on a node, where there are allocated GPU jobs at an "ImagePullBackoff" state. This causes an error of "UnexpectedAdmissionError". | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-4574    | The role "Researcher Manager" is not displayed in the access control list of projects. | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-4554    | Users are trying to login with single-sign-on get a "review profile" page. | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-4464    | Single HPO (hyperparameter optimization) workload is displayed in the Job list user interface as multiple jobs (one for every pod). | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |

### Version 2.10

#### Version 2.10.1

| Internal ID | Description                                                                                                                                                                       | Release Version        |
| :----------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------- |
| RUN-5676    | When Interactive Jupyter notebook workloads that contain passwords are cloned, the password is exposed in the displayed CLI command.                                              | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5457    | When using the Home environment variable in conjunction with the ran-as-user option in the CLI, the Home environment variable is overwritten with the user's home directory.      | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5370    | It is possible to submit two jobs with the same node-port.                                                                                                                        | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5314    | When you apply an inference deployment via a file, the allocated GPUs are displayed as 0 in the deployments list.                                                                 | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5284    | When workloads are deleted while the cluster synchronization is down, there might be a non-existent Job shown in the user interface. The Job cannot be deleted.                   | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5160    | In some situations, when a Job is deleted, there may be leftover Kubernetes ConfigMaps in the system                                                                              | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5154    | In some cases, an error "failed to load data" can be seen in the graphs showing on the Job sidebar.                                                                               | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5145    | The default Kubernetes "priority Class" for deployments is the same as the priority class for interactive jobs.                                                                   | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-5039    | In some scenarios, Dashboards may show "found duplicate series for the match group" error                                                                                         | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-4941    | The scheduler is wrongly trying to schedule jobs on a node, where there are allocated GPU jobs at an "ImagePullBackoff" state. This causes an error of "UnexpectedAdmissionError" | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-4574    | The role "Researcher Manager" is not displayed in the access control list of projects.                                                                                            | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-4554    | Users are trying to login with single-sign-on get a "review profile" page.                                                                                                        | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
| RUN-4464    | Single HPO (hyperparameter optimization) workload is displayed in the Job list user interface as multiple jobs (one for every pod).                                               | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12 |
