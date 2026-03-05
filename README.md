About tifffile-feedstock
========================

Feedstock license: [BSD-3-Clause](https://github.com/TileDB-Inc/tifffile-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/cgohlke/tifffile, https://github.com/conda-forge/tifffile-feedstock

Package license: BSD-3-Clause

Summary: Read and write image data from and to TIFF files.

Fork of conda-forge feedstock

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/TileDB-Inc/CI/_build/latest?definitionId=57&branchName=main">
        <img src="https://dev.azure.com/TileDB-Inc/CI/_apis/build/status/tifffile-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-tifffile-green.svg)](https://anaconda.org/tiledb/tifffile) | [![Conda Downloads](https://img.shields.io/conda/dn/tiledb/tifffile.svg)](https://anaconda.org/tiledb/tifffile) | [![Conda Version](https://img.shields.io/conda/vn/tiledb/tifffile.svg)](https://anaconda.org/tiledb/tifffile) | [![Conda Platforms](https://img.shields.io/conda/pn/tiledb/tifffile.svg)](https://anaconda.org/tiledb/tifffile) |

Installing tifffile
===================

Installing `tifffile` from the `tiledb` channel can be achieved by adding `tiledb` to your channels with:

```
conda config --add channels tiledb
conda config --set channel_priority strict
```

Once the `tiledb` channel has been enabled, `tifffile` can be installed with `conda`:

```
conda install tifffile
```

or with `mamba`:

```
mamba install tifffile
```

It is possible to list all of the versions of `tifffile` available on your platform with `conda`:

```
conda search tifffile --channel tiledb
```

or with `mamba`:

```
mamba search tifffile --channel tiledb
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search tifffile --channel tiledb

# List packages depending on `tifffile`:
mamba repoquery whoneeds tifffile --channel tiledb

# List dependencies of `tifffile`:
mamba repoquery depends tifffile --channel tiledb
```




Updating tifffile-feedstock
===========================

If you would like to improve the tifffile recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`tiledb` channel, whereupon the built conda packages will be available for
everybody to install and use from the `tiledb` channel.
Note that all branches in the TileDB-Inc/tifffile-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@ihnorton](https://github.com/ihnorton/)
* [@jdblischak](https://github.com/jdblischak/)
* [@jp-dark](https://github.com/jp-dark/)

