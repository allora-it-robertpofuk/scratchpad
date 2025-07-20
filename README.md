# scratchpad

## Jenkins
Read secrets from jenkins shell console: 
```
com.cloudbees.plugins.credentials.SystemCredentialsProvider
		.getInstance()
		.getCredentials()
.forEach{println "############# ${it.id} ############"; println it.dump().replace(' ', '\n'); println "##################################################"}

```
