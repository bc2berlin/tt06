<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

If OE == 0, all output pins are disabled.

Output Y[0:1] = (SEL == 0) ? A[0:1] : B[0:1]
Output Z[0:1] = (SEL == 0) ? ~A[0:1] : ~B[0:1]

Output YP and ZP are the parity of Y and Z respectively.

