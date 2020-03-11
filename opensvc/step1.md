Download and install OpenSVC Agent

`curl -o /tmp/opensvc.latest.rpm https://repo.opensvc.com/rpms/current`{{execute}}

`yum -y install /tmp/opensvc.latest.rpm`{{execute}}

Ccheck for proper daemon behaviour:

`om daemon status`{{execute}}
