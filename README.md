## Training plan 

<img src="plan.png">

### issues listing 

<img src="iss.png">

### boot process in RHEL 8/7 

<img src="bootprocess.png">

## Storage support in RHEL 

<img src="st.png">

## LInux Kernel storage Stack -- for Any application 

<img src="appst.png">

### checking storage stack 

<img src="stack.png">

### checking disk schedular and listing it 

<img src="list.png">

## storage io 

<img src="tool.png">

### Stratis in RHEL 

<img src="stratis.png">

### Installing stratisD 

<img src="stra.png">

### creating pool , fs and mount it 

<img src="create1.png">


### creating fstab for persistent boot 

<img src="fst.png">


### taking snapshot 

<img src="snap.png">

### creating a normal partition 

<img src="part.png">

### format with ext4 

<img src="ext4.png">

## E2fsck with backup superblock 

<img src="backup.png">

### removing stratis db 

<img src="rmst.png">

## LInux Kernel -- as Modular Design 

<img src="k.png">

### Exploring kernel message using dmesg

<img src="dms.png">

### /proc for kernel driver and message 

<img src="proc.png">

### exploring more filesystem 

<img src="kr.png">

### more info about driver 

<img src="dr.png">

### Kernel driver info in detail 

<img src="drr.png">

### CPU info 

<img src="cpu.png">

### more info about storage disk 

```
root@babykool:~# lsscsi -v
[0:0:0:0]    disk    ATA      Secureye SSD     6A0   /dev/sda 
  dir: /sys/bus/scsi/devices/0:0:0:0  [/sys/devices/pci0000:00/0000:00:1f.2/ata1/host0/target0:0:0/0:0:0:0]
list_ndevices: scandir: /sys/class/nvme/: No such file or directory
NVMe module may not be loaded
root@babykool:~# hdparm  -I  /dev/sda

/dev/sda:

ATA device, with non-removable media
	Model Number:       Secureye SSD                            
	Serial Number:      IT20210928256000976 
	Firmware Revision:  U0506A0 
	Media Serial Num:   
	Media Manufacturer: 
	Transport:          Serial, ATA8-AST, SATA 1.0a, SATA II Extensions, SATA Rev 2.5, SATA Rev 2.6, SATA Rev 3.0
Standards:
	Used: unknown (minor revision code 0x011b) 
	Supported: 10 9 8 7 6 5 
	Likely used: 10
Configuration:
	Logical		max	current

```




