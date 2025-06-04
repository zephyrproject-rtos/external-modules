# External Module Integration


This repository hosts various projects and modules supporting Zephyr which can
be used with Zephyr in applications. The purpose of this repository is to
provide one places where such projects can be documented and listed with same
samples and tests related to the projects/modules.

CI will run on this repository on a regular basis providing a way to verify
that such module work with the latest zephyr tree.

Historically all those projects were considered optional in the zephyr tree.
Zephyr itself does not depend on them, however they were kept in a submanifest
for backward compatibality reasons and due to the fact that Zephyr itself had
tests and samples relying on those projects.

Goal is to move many of those project from optional to external and also to
move related tests and samples from the zephyr tree to the projects or into
this repo.
