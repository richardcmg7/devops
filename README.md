# devops
Hi Richard. Thank you for following up on this. I reviewed in detail and have the following questions/observations. 

-	Since you will be following the ‘Git-flow’ versioning strategy, we would need to clearly define who can commit, merge or do pull requests to the release and main branches, since only they should be allowed to trigger the CI pipeline. We cannot give access to everyone to do this. 
-	I found that there are too many Organization Administrators / owners. Usually this should be no more than 2-3. Ideally only 2 (one main, one backup)
-	Access Revocation should be immediate when a person leaves. I’m not clear how this will be enforced. 

Thanks. 
