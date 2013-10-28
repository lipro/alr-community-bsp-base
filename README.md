TQ Systems's Community Yocto BSP
================================

This BSP is a community project and offer support for following processors:

* i.MX35
   - TQ System i.MX35 Embedded module (tqma35)

Quick Start Guide
-----------------

Once you have downloaded the source of all projects, you will have to
call:

    $: . ./setup-environment <build directory>

After this step, you will be with everything need for build an image.

Contributing
------------

To contribute to the development of this BSP and/or submit patches for
new boards please send the patches against the respective project as
informated bellow:

The following layers are included on this release:

 * poky: base build system and metadata
   - Path: sources/poky
   - GIT: git://git.yoctoproject.org/poky
   - Mailing list: https://lists.yoctoproject.org/listinfo/yocto

 * meta-fsl-arm: support for Freescale's processors and board
   - Path: sources/meta-fsl-arm
   - Project: https://github.com/Freescale/meta-fsl-arm
   - GIT: git://github.com/Freescale/meta-fsl-arm.git
   - Mailing list: https://lists.yoctoproject.org/listinfo/meta-freescale

 * meta-tqs-arm: support for TQ System's processors and board
   - Path: sources/meta-tqs-arm
   - Project: https://github.com/lipro/meta-tqs-arm
   - GIT: git://github.com/lipro/meta-tqs-arm.git
   - Mail: rexut95@gmail.com
