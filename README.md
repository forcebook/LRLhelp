# LRLhelp
Lenovo G4 AMN and Rocky Linux

## Lenovo V15 G4 AMN DSDT Patches for Linux ( Rocky Linux )

### 1. DSDT Patches for Lenovo 82YU (Lenovo V15 G4 AMN) Notebook
https://github.com/forcebook/lenovo_82yu_dsdt_patches

<details>

<summary>Make some modification on your machine ...</summary>

### Linux kernel

Install latest kernel from linux https://mirrors.edge.kernel.org/pub/linux/kernel/v6.x/

```
dnf install epel-repo
dnf install kernel*
....
```

</details>



### 2. Dynamic Kernel Module to add a poll mode to the i2c-hid driver so that the touchpad of the Lenovo 82YU notebook will work on linux
https://github.com/forcebook/lenovo_82yu_i2c_hid-dkms

### 3. Dynamic Kernel Module to add a poll mode to the kbd port in the i8042 chip driver so that the keyboard of the Lenovo 82YU notebook will work on linux
https://github.com/forcebook/lenovo_82yu_i8042-dkms
