## FleetDM CI/CD pipeline

## Step 0: Generate TLS private key and public cert
1. `openssl req -x509  -new -nodes -keyout conf/tls/tls.key -out conf/tls/tls.crt -config conf/tls/tls.conf`

## Step 1: Spin up stack
1. `docker stack deploy -c docker-compose-all.yml fleetdm_cicd`
1. `

## References
* [StackOverFlow - How to remove double-quotes in jq output for parsing json files in bash? [duplicate]](https://stackoverflow.com/questions/44656515/how-to-remove-double-quotes-in-jq-output-for-parsing-json-files-in-bash)
* [The Most Common OpenSSL Commands](https://www.sslshopper.com/article-most-common-openssl-commands.html)
* [JWT/OIDC Auth Method (API)](https://www.vaultproject.io/api/auth/jwt#jwks_ca_pem)
* [Authenticating and Reading Secrets With Hashicorp Vault](https://docs.gitlab.com/ee/ci/examples/authenticating-with-hashicorp-vault/)
* [Gitlab Docker - Install GitLab using Docker Compose](https://docs.gitlab.com/omnibus/docker/#install-gitlab-using-docker-compose)
* [Gitlab - NGINX settings - Redirect HTTP requests to HTTPS](https://gitlab.com/gitlab-org/omnibus-gitlab/blob/master/doc/settings/nginx.md#redirect-http-requests-to-https)
* [Using external secrets in CI](https://docs.gitlab.com/ee/ci/secrets/#configure-your-vault-server)
* [StackOverFlow - How to exit if a command failed?](https://stackoverflow.com/questions/3822621/how-to-exit-if-a-command-failed)
* [Unix and Linux: Redirect Error Output To null Command](https://www.cyberciti.biz/faq/unix-linux-redirect-error-output-to-null-command/)
* [jq: print key and value for each entry in an object](https://stackoverflow.com/questions/34226370/jq-print-key-and-value-for-each-entry-in-an-object)
* [Vault - KV Secrets Engine - Version 2](https://www.vaultproject.io/docs/secrets/kv/kv-v2)
* [sgreben/apk flags.md](https://gist.github.com/sgreben/dfeaaf20eb635d31e1151cb14ea79048)
* [FleetCTL releases](https://github.com/fleetdm/fleet/releases)
* [Extract filename and extension in Bash](https://stackoverflow.com/questions/965053/extract-filename-and-extension-in-bash)
* [Terminating a script in PowerShell](https://stackoverflow.com/questions/2022326/terminating-a-script-in-powershell)
* [compare two strings in if-then-else statement](https://social.technet.microsoft.com/Forums/lync/en-US/63b77100-85e1-40d1-afdc-26cc825dc911/compare-two-strings-in-ifthenelse-statement?forum=winserverpowershell)
* [How to compare the contents of two string objects in PowerShell](https://stackoverflow.com/questions/18772063/how-to-compare-the-contents-of-two-string-objects-in-powershell)
* [Set a locally scoped Environment Variable](https://www.tachytelic.net/2019/03/powershell-environment-variables/)
* [DEVOPS TALES: INSTALL/SETUP GITLAB + GITLAB RUNNERS ON DOCKER, WINDOWS, LINUX AND MACOS](https://holdmybeersecurity.com/2021/02/19/devops-tales-install-setup-gitlab-gitlab-runners-on-docker-windows-linux-and-macos/)
* [DockerHub - Windows](https://hub.docker.com/_/microsoft-windows)
* [[Docker on Windows] Cannot execute .exe files inisde nanoserver container (Security policies?)](https://social.msdn.microsoft.com/Forums/en-US/4d12df17-e803-4b12-ac82-6df99eb774cc/docker-on-windows-cannot-execute-exe-files-inisde-nanoserver-container-security-policies?forum=windowscontainers)
* [Powershell: Installing MSI files](https://powershellexplained.com/2016-10-21-powershell-installing-msi-files/)
* [Osquery downloads](https://osquery.io/downloads/official/4.6.0)
* [StackOverFlow - Can I get “&&” or “-and” to work in PowerShell?](https://stackoverflow.com/questions/563600/can-i-get-or-and-to-work-in-powershell)
* [StackOverFlow - Redirecting output to $null in PowerShell, but ensuring the variable remains set](https://stackoverflow.com/questions/5881174/redirecting-output-to-null-in-powershell-but-ensuring-the-variable-remains-set)
* [StackOverFlow - Iterating through key names from a PSCustomObject](https://stackoverflow.com/questions/18779762/iterating-through-key-names-from-a-pscustomobject)
* [StackOverFlow - How to check if file has valid JSON syntax in Powershell](https://stackoverflow.com/questions/17034954/how-to-check-if-file-has-valid-json-syntax-in-powershell)
* [Github - Palantir - osquery-configurations](https://github.com/palantir/osquery-configuration)
* [JSON basics for IT professionals](http://techgenix.com/json-with-powershell/)
* []()
* []()
* []()
* []()
* []()