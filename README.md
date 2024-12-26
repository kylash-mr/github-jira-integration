# github-jira-integration
A sample github repo used for integrating personal jira account and creating workflows


# Key things to Note:
1.Add the Github app in Jira under Apps->Explore More apps.\
2.Once added, give Jira access to the target Github account and repositories for Jira to manage on our behalf.\
3.Once the repos are connected, We can create a new branch directly from Jira.\
4.When working on a new file related to a Jira issue, first create a branch based on the Jira Issue ID(Eg. <Jira-Issue-ID>-<Issue-Description>) and then committing a new file, include the Jira Issue Id in the commit message for Jira to track.(Eg. `git commit -m "<Jira-Issue-ID> <message>"`).\
5.To integrate deployements into Jira, follow the same steps as above. Create a github actions workflow and use include the  Issue ID in commit message to enable Jira tracking.

# Sample Snapshots:
![image](https://github.com/user-attachments/assets/851a6776-3f24-418a-9eb9-f6bfd5addcb5)

![image](https://github.com/user-attachments/assets/ff0a6120-11f9-446e-a775-785443aa6fca)

![image](https://github.com/user-attachments/assets/d863840b-a176-4a39-bccb-b3d6e99fdfbc)

![image](https://github.com/user-attachments/assets/6fe3b6d9-b29a-4164-8d3c-dd2bbcd9400c)

![image](https://github.com/user-attachments/assets/abaa5c70-7862-498d-8863-bfc88b3cd1af)
