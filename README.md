# Guidelines on how to name repositories in GitHub at AITS

***
Here are some suggested guidelines on how to create repository names that are descriptive and searchable. 

Repository names should be use *lower case* letters and be delimited by *dashes*

***
### Use 'src' as prefix for source code repositories

src-&lt;language>-&lt;functional area: optional>-&lt;project name>

Some examples using SVN locations:

https://svn.admin.uillinois.edu/svn/aits/ColdFusion/projects/Research/PIPortal ==>>
src-cf-research-piportal

https://svn.admin.uillinois.edu/svn/aits/VBNet/projects/AVSL ==>>
src-vbnet-avsl

https://svn.admin.uillinois.edu/svn/aits/java/projects/HumanResources/HRFE ==>>
src-java-hr-hrfe

Examples: **src-java-student, src-java-hrfe, src-cf-nessie, src-net-avsl, etc.**

***
### Use 'deploy' as prefix for repositories for deployed artifacts
In SVN a location for HRFrontEnd deployed artifacts would be: */aits/configs/applications/Environments/Test/Applications/hrfe/*

Other application types batch, integration, web.

Examples: **deploy-nonprod-web-hrfe, deploy-prod-web-hrfe**

***
### Use 'proj' as prefix for repositories for projects (not affiliated with source code)
Example: **proj-sdlc**

***
### Use 'www' as prefix for repositories with web content
Examples: **www-banner, www-aits, www-flycmi**

***
### Use 'scripts' as prefix for repositories that are primarily to store scripts
Examples: **scripts-db, scripts-sqlserver, scripts-kafka** 

***
### Use 'product' as prefix for repositories containing artifacts for vended products
Examples: **product-midpoint, product-banner, product-siteminder**

***
### Use 'temp' as prefix for repositories that are used for sandbox purposes
Examples: **temp-issues-testing, temp-banner**
