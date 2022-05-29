# Virtual machine image for artifact evaluation

This repository contains the virtual machine (VM) image for running artifact evaluation experiments.
The image contains, in an already configured form: Blockaid, the three applications, and experiment scripts.

To run the Blockaid experiments, see the [artifact evaluation instructions](https://github.com/blockaid-project/artifact-eval/), which explain (1) whether you need to download the VM image, and (2) if so, how to use the image.

The VM image is located in the assets of [this release](https://github.com/blockaid-project/ae-vm-image/releases/tag/osdi22ae) as a multi-part zip file; the total size is roughly 6.5 GB. To obtain the image, download all parts and unzip, e.g., using [7-Zip](https://www.7-zip.org/):
```
$ 7z x blockaid-ae-vm.z01
```
