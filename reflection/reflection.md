1. Which cloud provider did you choose, and why?

&#x09;I chose AWS since I find it the easiest to use.



2\. What resource did you create?

&#x09;I created a S3 bucket.

3\. What does the provider block do in Terraform?

&#x09;It tells terraform which Cloud provider to connect to like AWS as well as which region to connect to.



4\. What is the purpose of the resource block?

&#x09;It sets the resource type so terraform knows what to make and what settings to apply.

&#x09;

5\. Why should you review terraform plan before running terraform apply?

&#x09;It shows exactly what its going to do, it might make changes you don't want. Reviewing this can

&#x09;Can stop unexpected things from being created or changed.



6\. What happened when you ran terraform destroy?

&#x09;It listed the objects it planned to destroy, then after saying yes it deletes the resources it

&#x09;showed me. It then sends a confirmation of deletion.



7\. What error or challenge did you encounter, if any, and how did you troubleshoot it?

&#x09;I didn't know how to setup a user so I could give the CLI access to make changes to AWS.

&#x09;I was able to figure it out in the end after learning how to set it up.



8\. What is one benefit of using Infrastructure as Code instead of manually creating cloud resources?

&#x09;It makes deployment consistent, that way I can quickly replicate things. All the information can

&#x09;be defined in a file rather than going through multiple pages.

