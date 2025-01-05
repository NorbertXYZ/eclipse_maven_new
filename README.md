## The Maven repository for eclipse builds

This repository is made for the maven pacakges in the port builds of FreeBSD (x86_64 and aarch64).  The FreeBSD port is based on the repository
https://github.com/chirontt/eclipse.platform.releng.aggregator/
where the developer took my previous/first adaptations of FreeBSD and added corrections and adaptations.  Thanks to this software developer :-)

For version  / tag 4.34 I made a small "correction" in
p2/osgi/bundle/com.sun.jna/5.14.0.v20231211-1200
and added the freebsd aarch64 in MANIFEST.INF, and also copied the freebsd-aarch64 folder com/sun/jna from jna 5.15.0.
Then the compilation under aarch64 was successful.
