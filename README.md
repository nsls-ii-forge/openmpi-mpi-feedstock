About openmpi-mpi
=================

Home: https://www.open-mpi.org/

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/nsls-ii-forge/openmpi-mpi-feedstock/blob/master/LICENSE.txt)

Summary: An open source Message Passing Interface implementation.

Development: https://github.com/open-mpi/ompi

Documentation: https://www.open-mpi.org/doc/

The Open MPI Project is an open source Message Passing Interface
implementation that is developed and maintained by a consortium of academic,
research, and industry partners.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=56&branchName=master">
            <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/openmpi-mpi-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_cuda_compiler_version9.2</td>
              <td>
                <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=56&branchName=master">
                  <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/openmpi-mpi-feedstock?branchName=master&jobName=linux&configuration=linux_64_cuda_compiler_version9.2" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-openmpi-green.svg)](https://anaconda.org/nsls2forge/openmpi) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/openmpi.svg)](https://anaconda.org/nsls2forge/openmpi) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/openmpi.svg)](https://anaconda.org/nsls2forge/openmpi) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/openmpi.svg)](https://anaconda.org/nsls2forge/openmpi) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-openmpi--mpicc-green.svg)](https://anaconda.org/nsls2forge/openmpi-mpicc) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/openmpi-mpicc.svg)](https://anaconda.org/nsls2forge/openmpi-mpicc) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/openmpi-mpicc.svg)](https://anaconda.org/nsls2forge/openmpi-mpicc) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/openmpi-mpicc.svg)](https://anaconda.org/nsls2forge/openmpi-mpicc) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-openmpi--mpicxx-green.svg)](https://anaconda.org/nsls2forge/openmpi-mpicxx) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/openmpi-mpicxx.svg)](https://anaconda.org/nsls2forge/openmpi-mpicxx) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/openmpi-mpicxx.svg)](https://anaconda.org/nsls2forge/openmpi-mpicxx) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/openmpi-mpicxx.svg)](https://anaconda.org/nsls2forge/openmpi-mpicxx) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-openmpi--mpifort-green.svg)](https://anaconda.org/nsls2forge/openmpi-mpifort) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/openmpi-mpifort.svg)](https://anaconda.org/nsls2forge/openmpi-mpifort) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/openmpi-mpifort.svg)](https://anaconda.org/nsls2forge/openmpi-mpifort) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/openmpi-mpifort.svg)](https://anaconda.org/nsls2forge/openmpi-mpifort) |

Installing openmpi-mpi
======================

Installing `openmpi-mpi` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `openmpi, openmpi-mpicc, openmpi-mpicxx, openmpi-mpifort` can be installed with:

```
conda install openmpi openmpi-mpicc openmpi-mpicxx openmpi-mpifort
```

It is possible to list all of the versions of `openmpi` available on your platform with:

```
conda search openmpi --channel nsls2forge
```




Updating openmpi-mpi-feedstock
==============================

If you would like to improve the openmpi-mpi recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/openmpi-mpi-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


