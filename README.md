# gh-aws-iis
Example environment to test and show a project setup for a app to be deployed in iis hosted in aws

Example application has been created with dotnet:
```
dotnet new webapp
```

Deployment is done with these steps:
* Build
* Publish
* Deploy
* Run a first request (warmup and to check if it is up)
* Run a set of end-to-end (aka webtests) on the deployed application


enale long paths
https://github.com/actions/checkout/discussions/459
Set-ItemProperty 'HKLM:\System\CurrentControlSet\Control\FileSystem' -Name 'LongPathsEnabled' -value 1