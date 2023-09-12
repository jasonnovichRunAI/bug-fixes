# Changelog 2.13

## Version 2.13.56

### Known issues

None

### Fixed issues

| Internal ID | Description  | Release&nbsp;&nbsp;&nbsp;Version  |
| :---------- | :-------- | :------------ |
| RUN-5676    | When Interactive Jupyter notebook workloads that contain passwords are cloned, the password is exposed in the displayed CLI command.                                               | Fixed in 2.9.0<br/>Fixed in 2.10.1<br/>Fixed in 2.12.23 |
| RUN-5457    | When using the Home environment variable in conjunction with the ran-as-user option in the CLI, the Home environment variable is overwritten with the user's home directory.       | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-5370    | It is possible to submit two jobs with the same node-port.                                                                                                                         | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-5314    | When you apply an inference deployment via a file, the allocated GPUs are displayed as 0 in the deployments list.                                                                  | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-5284    | When workloads are deleted while the cluster synchronization is down, there might be a non-existent Job shown in the user interface. The Job cannot be deleted.                    | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-5160    | In some situations, when a Job is deleted, there may be leftover Kubernetes ConfigMaps in the system.                                                                              | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-5154    | In some cases, an error "failed to load data" can be seen in the graphs showing on the Job sidebar.                                                                                | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-5145    | The default Kubernetes "priority Class" for deployments is the same as the priority class for interactive jobs.                                                                    | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-5039    | In some scenarios, Dashboards may show "found duplicate series for the match group" error.                                                                                         | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-4941    | The scheduler is wrongly trying to schedule jobs on a node, where there are allocated GPU jobs at an "ImagePullBackoff" state. This causes an error of "UnexpectedAdmissionError". | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-4574    | The role "Researcher Manager" is not displayed in the access control list of projects.                                                                                             | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-4554    | Users are trying to login with single-sign-on get a "review profile" page.                                                                                                         | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |
| RUN-4464    | Single HPO (hyperparameter optimization) workload is displayed in the Job list user interface as multiple jobs (one for every pod).                                                | Fixed in 2.9<br/>Fixed in 2.10.1<br/>Fixed in 2.12       |

## Version 2.13.11

### Known issues

None

### Fixed issues

| Internal ID | Description  | Release&nbsp;&nbsp;&nbsp;Version |
| :---------- | :----------------------- | :------------------------------------------------- |
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

## Version 2.13.7

### Release date

July 2023

#### Release content

<!-- RUN-10803 -->
* Added filters to the historic quota ratio widget on the *Quota management* dashboard.

#### Fixed issues

| Internal ID | Description  |
| ---------------------------- | ---- |
| RUN-11080 | Fixed an issue in OpenShift environments where log in via SSO with the `kubeadmin` user, gets blank pages for every page. |
| RUN-11119 | Fixed an issue where values that should be the *Order of priority* column are in the wrong column. |
| RUN-11120 | Fixed an issue where the *Projects* table does not show correct metrics when Run:ai version 2.13 is paired with a Run:ai 2.8 cluster. |
| RUN-11121 | Fixed an issue where the wrong over quota memory alert is shown in the *Quota management* pane in project edit form. |
| RUN-11272 | Fixed an issue in OpenShift environments where the selection in the cluster drop down in the main UI does not match the cluster selected on the login page. |

## Version 2.13.4

### Release date

July 2023

#### Fixed issues

| Internal ID | Description |
|-----------|--------------|
| RUN-11089 | Fixed an issue when creating an environment, commands in the *Runtime settings* pane and are not persistent and cannot be found in other assets (for example in a new *Training*). |

## Version 2.13.1

### Release date

July 2023

#### Release content

<!-- RUN-11024 -->
* Made an improvement so that occurrences of labels that are not in use anymore are deleted.

#### Fixed issues

N/A

## Version 2.13.0

### Known issues

| Internal ID | Description            |
| :---------- | :---------------------------------- |
| RUN-11005 | Incorrect error messages when trying to run `runai` CLI commands in an OpenShift environment. |
| RUN-11009 | Incorrect error message when a user without permissions to tries to delete another user. |

### Fixed issues

| Internal ID | Description                                                                                                                                |
| :---------- | :----------------------------------------------------------------------------------------------------------------------------------------- |
| RUN-9039    | Fixed an issue where in the new job screen, after toggling off the preemptible flag, and a job is submitted, the job still shows as preemptible. |
| RUN-9323    | Fixed an issue with a non-scaleable error message when scheduling hundreds of nodes is not successful.                                     |
| RUN-9324    | Fixed an issue where the scheduler did not take into consideration the amount of storage so there is no explanation that pvc is not ready. |
| RUN-9902    | Fixed an issue in OpenShift environments, where there are no metrics in the dashboard because Prometheus doesn’t have permissions to monitor the `runai` namespace after an installation or upgrade to 2.9. |
| RUN-9920    | Fixed an issue where the `canEdit` key in a policy is not validated properly for itemized fields when configuring an interactive policy.   |
| RUN-10052   | Fixed an issue when loading a new job from a template gives an error until there are changes made on the form.   |
| RUN-10053   | Fixed an issue where the Node pool column is unsearchable in the job list.                                                                 |
| RUN-10422   | Fixed an issue where node details show running workloads that were actually finished (successfully/failed/etc.).                         |
| RUN-10500   | Fixed an issue where jobs are shown as running even though they don't exist in the cluster.                                                |
| RUN-10813   | Fixed an issue in adding a `data source` where the path is case sensitive and didn't allow uppercase. |
