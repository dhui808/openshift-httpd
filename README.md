# openshift-httpd
Apache HTTP Server (httpd) Sample Application for OpenShift

oc new-app --as-deployment-config --name hola openshift/httpd:latest~https://github.com/dhui808/openshift-httpd

oc expose service/hola
