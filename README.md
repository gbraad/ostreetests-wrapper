OSTree Tests wrapper
====================


Docker container image for [OSTree tests](https://github.com/giuseppe/ostreetests) from Guiseppe Scrivano.



Registries
----------

### Gitlab

Automated builds are available at [GitLab](https://gitlab.com/gbraad/ostreetests)

  * CentOS:  
    `docker pull registry.gitlab.com/gbraad/ostreetests:centos`
  * Fedora:  
    `docker pull registry.gitlab.com/gbraad/ostreetests:fedora`


Usage
-----


#### Container based on _CentOS_

```
$ docker run --rm -ti --security-opt="label:disable" -v $PWD:/ostree registry.gitlab.com/ostreetests:centos
```

#### Container based on _Fedora_

```
$ docker run --rm -ti --security-opt="label:disable" -v $PWD:/ostree registry.gitlab.com/ostreetests:fedora
```


Thanks
------

  * Guiseppe Scrivano for `ostreetests`


Authors
-------

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://twitter.com/gbraad) |