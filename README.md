# Hardware-agnostic fastpath implementation.
How-to:

apply fastpath.patch with patch -p1 <
copy patches 950, 951 and 952 in /target/linux/generic/patches

run menuconfig and select kmod-fast-classifier
