# COPY-A-DIRECTORY-FROM-A-LOCAL-MACHINE-TO-A-VIRTUAL-MACHINE-IN-MICROSOFT-AZURE-USING-THE-CLI

* Grab the IP addresses for a particular VM.

``` 
az vm list-ip-addresses -g <RESOURCE-GROUP> -n <VIRTUAL-MACHINE-NAME> 
```

* Copy the directory.

```scp -r <SOURCE-DIR> [ADMIN-NAME]@[PUBLIC-IP]:<TARGET-DIR> ```
