# fgci-meta- packages
Meta-rpms for the FGCI nodes.

all.packages are common packages that goes into all variants.

Generate ready .rpms using the ./generate script.

Each .packages file should only contain lines like:
Requires: packagename 

that can be immediately included into a RPM .spec file.

For a new release, edit the file "config" to bump the version and/or release version. 
Also update the "changelog" file with the changes that have been done.




Author: Ulf Tigerstedt <ulf.tigerstedt@csc.fi>

