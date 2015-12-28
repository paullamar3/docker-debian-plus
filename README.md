# Welcome to the Debian-Plus Container

This container is built from the official Debian container but with
some additional shell scripts added. Currently there are only two
such scripts: `p_addpkgs` and `p_adduser`. These scripts let me 
streamline the *Dockerfiles* in my downstream containers. By using these
scripts I not only make my *Dockerfiles* easier to unerstand but I can
help ensure I am doing things well and consistently across all my
containers. (And later, if I figure out a better way to, for example, 
add a package or add a user, then I can simply update this image knowing
that all downstream containers will benefit from the change.

