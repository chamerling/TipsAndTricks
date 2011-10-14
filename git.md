# Git Tips

## Fix certificate problems

### Problem 
> new-host-4:gitrepo chamerling$ git clone https://forge.ebmwebsourcing.com/gitrepotdejean/WS-STAR-LIBRARIES/commons.git
> Cloning into commons...
> error: SSL certificate problem, verify that the CA cert is OK. Details:
> error:14090086:SSL routines:SSL3_GET_SERVER_CERTIFICATE:certificate verify failed while accessing https://forge.ebmwebsourcing.com/gitrepotdejean/WS-STAR-LIBRARIES/commons.git/info/refs

### Solution
*export GIT_SSL_NO_VERIFY=true*