# ocp-demo-bit

# Apache HTTP Server (httpd) S2I Sample Application

```sh
$ minishift start
$ minishift console
$ oc new-project demo
$ oc project demo
$ oc login
$ oc login -u developer
$ oc new-app centos/httpd-24-centos7~https://github.com/bigg01/ocp-demo-bit

$ oc get svc
$ oc expose svc/ocp-demo-bit
$ oc get route
NAME           HOST/PORT                                 PATH      SERVICES       PORT       TERMINATION   WILDCARD
ocp-demo-bit   ocp-demo-bit-demo.192.168.99.100.nip.io             ocp-demo-bit   8080-tcp                 None

```


