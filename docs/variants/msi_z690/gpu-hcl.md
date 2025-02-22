# GPU HCL

## Contributing

Feel free to test different graphics cards and report your results via
[email](mailto:contact@dasharo.com) or submit a Pull Request to
[Dasharo documentation repository](https://github.com/Dasharo/docs) or by using
[Dasharo issues repository](https://github.com/Dasharo/dasharo-issues/issues).

If you already have reported your results and you change some hardware
configuration we would appreciate an additional HCL report.

## HCL list

GPU Hardware Compatibility List presents the GPUs tested and verified
to work with Dasharo by community. The following list does not include GPU
which is tested and verfied in 3mdeb laboratory - this information might be
found in [Hardware Matrix](hardware-matrix.md) documentation.

Legend:

* GPU name: the full name of GPU including vendor and model name.
* Memory size: total amount of GPU memory declared by vendor.
* Memory type: GPU's type of memory.
* Bandwidth: GPU's bandwidth.
* PCI-E Architecture: declared by producer generation of PCI-E architecture.
* Multi-Graphics Technology: information about support for Multi-Graphics
    Technology.

Information about GPU might be read from GPU package or documentation.

| GPU name         | Memory size | Memory type  | Bandwidth | PCI-E Gen | Multi-Graphics Technology | Results                |
|:----------------:|:-----------:|:------------:|:---------:|:---------:|:-------------------------:|:----------------------:|
| Nvidia GeForce GTX 1060   | 3072 MB  | GDDR5  | 192GB/s   | Gen3      | 1                         | [Qubes HCL reports][1] |
| MSI Radeon RX 6950 XT     | 16 GB    | GDDR6  | 576GB/s   | Gen4      | 1                         | |
| EVGA NVidia RTX 2080      | 8 GB     | GDDR6  | 448GB/s   | Gen3      | 1                         | |
| PNY NVidia RTX A5000      | 24 GB    | GDDR6  | 768GB/s   | Gen4      | 1                         | |
| Nvidia GeForce GTX 1080TI | 11264 MB | GDDR5X | x16       | Gen3      | 1                         | [Qubes HCL reports][2] |
| MSI Radeon RX 6500 XT MECH 2X 4G OC | 4 GB     | GDDR6  | x4 (x16 connector) | Gen4      | 1                         | Works only on Dasharo v1.1.0 or newer |
| MSI GeForce RTX 3060 GAMING Z TRIO LHR | 12 GB     | GDDR6  | x16   | Gen4      | 1                         | |

[1]: https://forum.qubes-os.org/t/msi-pro-z690-a-wifi-ddr4-with-alder-lake-12900k/11490/6
[2]: https://www.qubes-os.org/hcl/#msi_ms-7d25_i7-12700k_alder-lake_integrated-graphics-uhd-770-geforce-gtx-1080-ti
