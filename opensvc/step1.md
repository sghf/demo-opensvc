Install OpenSVC Agent

`curl -o /tmp/opensvc.latest.rpm https://repo.opensvc.com/rpms/current`{{execute}}

`yum -y install /tmp/opensvc.latest.rpm`{{execute}}

`om daemon status`{{execute}}
