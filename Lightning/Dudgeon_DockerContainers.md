# Docker images for RDKit

Using containers makes using RDKit easier and makes results easier to reproduce.

## Informatics Matters Images

Images of various RDKit releases since 2015. Docker images are built semi-autmoatically.

Basic RDKit build: [GitHub](https://github.com/InformaticsMatters/rdkit) [DockerHub](https://hub.docker.com/r/informaticsmatters/rdkit/)
RDKit + Java bindings: [Github](https://github.com/InformaticsMatters/rdkit_java) [DockerHub](https://hub.docker.com/r/informaticsmatters/rdkit_java/)
RDKit + Java + Tomcat: [GitHub](https://github.com/InformaticsMatters/rdkit_java_tomcat) [DockerHub](https://hub.docker.com/r/informaticsmatters/rdkit_java_tomcat/)
RDKit PostgreSQL cartridge: [GitHub](https://github.com/InformaticsMatters/rdkit_cartridge) [DockerHub](https://hub.docker.com/r/informaticsmatters/rdkit_cartridge/)
RDKit + Pipelines: [GitHub](https://github.com/InformaticsMatters/pipelines) [DockerHub](https://hub.docker.com/r/informaticsmatters/rdkit_pipelines/)

Example of how to use:

```
$ docker run -it --rm informaticsmatters/rdkit:Release_2016_03_1 python
Python 2.7.9 (default, Jun 29 2016, 13:08:31)
[GCC 4.9.2] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> from rdkit import Chem
>>> Chem.rdBase.rdkitVersion
'2016.03.1'
>>>
```

## RDKit images

Dockerfiles used in building RDKit releases.

https://github.com/rdkit/rdkit_containers



