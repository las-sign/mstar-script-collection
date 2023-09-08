# Mstar Commands

| Command | Description |
| --- | --- |
| `?` | alias for `help` |
| `ac` | Set a new config to the bootargs |
| `aesdma` | Do the aesdma command |
| `audio_preinit` | Init audio driver |
| `auto_flash` | Do auto flash image |
| `auto_tftp` | Do auto-address tftp |
| `base` | print or set address offset |
| `bdinfo` | Print Board Info structure |
| `bin2emmc` | Read bin file and restore it to emmc |
| `boot` | Boot default, i.e., run 'bootcmd' |
| `bootargs_set` | Set info exchange and set to boot args |
| `bootcheck` | Do boot check |
| `bootd` | Boot default, i.e., run 'bootcmd' |
| `bootlogo` | Display Logo_Music |
| `bootm` | Boot application image from memory |
| `bootmusic` | play music |
| `bootp` | Boot image via network using BOOTP/TFTP protocol |
| `checkUsbModeSwitch` |  |
| `checkVersion` | Check current verison and upgrade image version |
| `checkfile` | check file exist in u disk,and set the partition |
| `checkstr` | check_str_resume |
| `checktee` | Check TEE binary |
| `chkmiusetting` | Check MIU setting |
| `cleanallenv` | Clean all environment variables to persistent storage |
| `cmp` | Memory compare |
| `cnstar` | Do net update from the specified file that is in oad partition |
| `config2env` | Set config to environment |
| `config_raw_io` | Config the target device for raw I/O |
| `coninfo` | Print console devices and information |
| `costar` | Do oad update from the specified file that is in oad partition |
| `cp` | Memory copy |
| `crc32` | Checksum calculation |
| `createMbootBak` | Create mbootbak partition |
| `ctv_factory_mode_check` | Factory mode to check usb files and do test |
| `custar` | Do usb update from the specified file that is in usb |
| `dbg` | Set debug message level. Default level is INFO |
| `dbtable_init` | Let data  is ready (logo, music, panel, ursa) |
| `dbtable 1` | Update config |
| `dc` / `dcvdelete` | Delete the specific config that is in the bootargs |
| `delay` | delay time, time unit is ms |
| `destroy_logo` | Stop logo display |
| `dhcp` | boot image via network using DHCP/TFTP protocol |
| `dont_overwrite` | This serial apis are for protecting the specific partitions are overwrited. ex: customer This cmd is used to register which partition should not be overwrite |
| `dont_overwrite_free` | This serial apis are for protecting the specific partitions are overwrited. ex: customer This cmd is used to free all registered partitions |
| `dont_overwrite_init` | This serial apis are for protecting the specific partitions are overwrited. ex: customer This cmd is used to init this function |
| `dont_overwrite_switch` | This serial apis are for force write and re-create partitions. This cmd is used to disable dont_overwrite function |
| `draw_jpg` | blt_jpg - Blt JPG |
| `draw_pixel` | draw a pixel with color |
| `draw_progress` | |
| `draw_rect` | draw rect with color **draw_rect 10 10 100 100 999999** |
| `draw_string` | draw_string - draw string with color **draw_string "Hello" 10 10 999999 0** |
| `du` | Disable UART |
| `ebist` | PHY loopback test |
| `echo` | echo args to console |
| `editenv` | edit environment variable |
| `edump` | EMAC Register settings dump |
| `eloopback` | Long loopback test |
| `emmc` | eMMC sub system |
| `emmcbin` | emmcbin - dump emmc and restore it to fat usb disk |
| `emmcbootbin` | dump emmc boot partition and write it to fat usb disk |
| `env` | environment handling commands |
| `envload` | reload the nand environment |
| `epd` | emac power down |
| `estart` | EMAC start |
| `ewavetest` | EMAC wave test |
| `exit` | exit script |
| `ext2load` | load binary file from a Ext2 filesystem |
| `ext2ls` | list files in a directory (default /) |
| `ext4filesize` | get file size from a Ext4 filesystem |
| `ext4load` | load binary file from a Ext4 filesystem |
| `ext4ls` | list files in a directory (default /) |
| `ext4partload` | part load binary file from a Ext4 filesystem |
| `factory_check_usb_files` | check usb files, enter diffrrent mode |
| `false` | do nothing, unsuccessfully |
| `fastboot` | enter fastboot mode |
| `fatfilesize` | load binary file from a dos filesystem |
| `fatinfo` | print information about filesystem |
| `fatload` | load binary file from a dos filesystem |
| `fatls` | list files in a directory (default /) |
| `fatpartload` | load binary file from a dos filesystem |
| `fatwrite` | write binary file to a dos filesystem |
| `filelist` | Dump the file list. |
| `filelisttest` | This command is only for file list test |
| `filepartload` | load part of a file to RAM |
| `filepartloadSeg` | load a seg part of file to RAM |
| `flashbin` | dump/restore emmc or nand flash data to/from flash.bin |
| `force_overwrite` | This serial apis are for force write and re-create partitions. This cmd is used to register which partition should force overwrite |
| `force_overwrite_init` | This serial apis are for force write and re-create partitions. This cmd is used to register which partition should force overwrite |
| `get_mmap` | get memory info from supernova's mmap |
| `gettime` | Get the system executing time |
| `go` | start application at address 'addr' |
| `gpio` | GPIO Command: |
| `help` | print command description/usage |
| `i2c` | I2C sub-system |
| `if_boot_to_pm` | if boot to PM |
| `iminfo` | print header information for application image |
| `imxtract` | extract a part of a multi-image |
| `initDbgLevel` | Initial varaible 'dbgLevel' |
| `init_raw_io` | init raw_io module |
| `ir_delay` | delay 300ms for IR detect. |
| `itest` | return true/false on integer compare |
| `kernelProtect` | Protect kernel |
| `kernelProtectBist` | Protect kernel bist |
| `led` | See led commands |
| `loadb` | load binary file over serial line (kermit mode) |
| `loadenv` | loadenv   - load env for nand |
| `loads` | load S-Record file over serial line |
| `loadspi` | load data from SPI |
| `loady` | load binary file over serial line (ymodem mode) |
| `loop` | infinite loop on address range |
| `lz4` | LZ4 decompress |
| `m2e` | Restore the address and len to env from supernova's mmap |
| `macaddr` | setup EMAC MAC addr |
| `mbootver_set` | setmbootver - for customer show in factory menu |
| `mbup` | mboot upgrade |
| `md` | memory display |
| `memtest` | Get the performance of memory |
| `miuProtect` | Protect miu |
| `mm` | memory modify (auto-incrementing address) |
| `mmc` | MMC sub system |
| `mmcbininfo` | Valid block num in each partition |
| `mmcinfo` | display MMC info |
| `mmcreg` | mmcreg show ext-csd |
| `modelinfo` | check model info if need sync to sync dbpool |
| `mscompress7` | Compress or decompress lzma files |
| `msg` | print string - msg [string] |
| `mstar` | update kernal & root file system automatically by script file |
| `mstar_usb` | MStar USB Driver Porting |
| `mtest` | simple RAM read/write test |
| `multi2optee` | For Multi Optee Image writting to EMMC |
| `mversion` | show changelist - mversion |
| `mw` | memory write (fill) |
| `nm` | memory modify (constant address) |
| `nstar` | update softwave system automatically via net |
| `nuttxProtect` | Protect nuttx |
| `osd_create` | create osd layer **osd_create create w 1980 h 1080** |
| `osd_destroy` | destroy osd layer |
| `osd_flush` | flush canvas to screen |
| `ostar` | update softwave system automatically via oad |
| `ota_zip_check` | do OTA zip package check |
| `panel_init` | init panel by panel.ini |
| `panel_post_init` | backligth on - backlight on |
| `panel_pre_init` | init panel by panel.ini |
| `ping` | send ICMP ECHO_REQUEST to network host |
| `pm51` | pm51 command: pm51 [option] |
| `pmProtect` | runtime pm Protect  - Protect runtime PM |
| `pop_raw_io_config` | pop raw_io last config |
| `printenv` | print environment variables |
| `push_raw_io_config` | push raw_io current config |
| `qhb_check` | run QHB flag check |
| `raw_io_status` | get raw_io status |
| `raw_read` | Read the raw datas that store in the target device. You have to execute 'config_raw_io' before using this cmd |
| `raw_write` | Write the raw datas that store in the target device. You have to execute 'config_raw_io' before using this cmd |
| `readArmFw` | read Nuttx to malloc buffer |
| `readOptee` | core1 run at Nuttx |
| `recovery_wipe_partition` | do recovery wipe data or cache |
| `reset` | Perform RESET of the CPU |
| `riu` | riu command |
| `run` | run commands in an environment variable |
| `sar` | sar Command: |
| `saveenv` | save environment variables to persistent storage |
| `sd_sysrecovery` | SberDevices sysrecovery command, burn $targets with sdsr images |
| `setenv` | set environment variables |
| `showboard` | Show board information |
| `showtb` | Show register command table.    -  showtb [stage] |
| `showvar` | print local hushshell variables |
| `showversion` | Show version |
| `sleep` | delay execution for some time |
| `smc` | jump to arm_trusted_firmware |
| `source` | run script from memory |
| `sparse_write` | do sparse image writing to target flash type. |
| `spi2usb` | Read data from spi to usb |
| `sync_mmap` | Sync the some id's address and len to env and bootargs from supernova's mmap |
| `test` | minimal test like /bin/sh |
| `testmode` | set testmode into bootargs. |
| `tftpboot` | boot image via network using TFTP protocol |
| `true` | do nothing, successfully |
| `udstar` | Execute the script file that is stored in usb disk |
| `unlockcmi` | unlock cmi transfer board   -  unlock |
| `update_mode` | get/set update_mode |
| `updatemiureg` | Call driver to update miu setting |
| `usb` | USB sub-system |
| `usb2spi` | write data from usb to spi |
| `usb_bin_check` | do usb bin document check. |
| `usb_partial_upgrade_to_emmc` | partial upgrade from USB to eMMC |
| `usb_super_upgrade_to_emmc` | super upgrade from USB to eMMC |
| `usbboot` | boot from USB device |
| `ustar` | update kernal & root file system automatically by script file |
| `version` | print monitor, compiler and linker version |
| `wdt_enable` | wdt_enable n - set Watchdog timer to n secs |

## ac
**ac** - set a new config to the bootargs

*Usage:*

`ac [config] [content]`

*For example:*

`ac autotest true`



## aesdma
**aesdma** - do the aesdma command

*Usage:*

`aesdma <cmd type>`

*For example:*

`aesdma performance` - do the aesdma performance test

*Commands:*

`aesdma performance <algo> <cipher mode>` #default: (byte) = (128, 256, 512, 1024, etc).

`aesdma performance <algo> <cipher mode> 0`

`aesdma performance aes cbc`

`aesdma performance des ctr`

`aesdma performance taes ecb`

`aesdma performance aes ctr 0`

`aesdma performance aes ecb 0`

`aesdma performance <algo> <cipher mode> <byte>`

`aesdma performance aes ctr 128`

`aesdma performance aes cts_cbc 256`

`aesdma performance aes cts_ecb 512`

`aesdma performance <algo> <cbcs/cens>`

`aesdma performance <algo> <cbcs/cens> <byte>` #default: (crypted block, skipped block) = (1:9)

`aesdma performance <algo> <cbcs/cens> <byte> <crypted block> <skipped block>`

`aesdma performance aes cbcs`

`aesdma performance aes cens 0`

`aesdma performance aes cbcs 400`

`aesdma performance aes cbcs 0 2 1`

`aesdma performance aes cens 1024 2 5`



## audio_preinit
**audio_preinit** - Init audio driver

*Usage:*

`audio_preinit`



## auto_flash
**auto_flash** - do auto flash image

*Usage:*

`auto_flash [flash_type] [flash_command] [partitionname] ([empty_skip]<0/1>)`

*For example:*

`auto_flash mmc write.p MBOOT`



## auto_tftp
**auto_tftp** - do auto-address tftp

*Usage:*

`auto_tftp [image_name]`

*For example:*

`auto_tftp mboot.bin`



## base
**base** - print or set address offset

*Usage:*

`base` - print address offset for memory commands

`base off` - set address offset for memory commands to 'off'



## bdinfo
**bdinfo** - print Board Info structure

*Usage:*

`bdinfo`



## bin2emmc
**bin2emmc** - read bin file and restore it to emmc

*Usage:*

`bin2emmc [usbportnum] [pad] [binname] [offset/partitionname]`



## boot
**boot** - boot default, i.e. run 'bootcmd'

*Usage:*

`boot`



## bootargs_set
**bootargs_set** - Set info exchange and set to boot args

*Usage:*

`bootargs_set`



## bootcheck
**bootcheck** - Do boot check

*Usage:*

`bootcheck`



## bootd
**bootd** - boot default, i.e. run 'bootcmd'

*Usage:*

`bootd`



## bootlogo
**bootlogo** - Display Logo_Music

*Usage:*

`bootlogo`



## bootm
**bootm** - boot application image from memory

*Usage:*

`bootm [addr [arg ...]]` - boot application image stored in memory

Passing arguments 'arg ...' when booting a Linux kernel, 'arg' can be the address of an initrd image

*Sub-commands:*

| Command | Description |
| :--- | :--- |
| `start [addr [arg ...]]` | |
| `loados`  | load OS image |
| `cmdline` | OS specific command line processing/setup |
| `bdt`     | OS specific bd_t processing |
| `prep`    | OS specific prep before relocation or go |
| `go`      | start OS |

The sub-commands to do part of the bootm sequence must be issued in the order below (it's ok to not issue all sub-commands)



## bootmusic
**bootmusic** - play music

*Usage:*

`bootmusic`



## bootp
**bootp** - boot image via network using BOOTP/TFTP protocol

*Usage:*

`bootp [loadAddress] [[hostIPaddr:]bootfilename]`



## checkUsbModeSwitch
**checkUsbModeSwitch** - check usb mode switch

*Usage:*

`checkUsbModeSwitch`



## checkVersion
**checkVersion** - check current verison and upgrade image version

*Usage:*

`checkVersion <name> <verision>`



## checkfile
**checkfile** - check file exist in u-disk and set the partition

*Usage:*

`checkfile <Dir>` - check a file in U-disk Dir exist or not



## checkstr
**checkstr** - check_str_resume

*Usage:*

`checkstr`



## checktee
**checktee** - Check TEE binary

*Usage:*

`checktee <BINAddr>`



## chkmiusetting
**chkmiusetting** - Check MIU setting

*Usage:*

`chkmiusetting` - do_chkmiusetting ${SCRIPTROOT}



## cleanallenv
**cleanallenv** - cleanall environment variables to persistent storage

*Usage:*

`cleanallenv` - clean all env

`cleanallenv net` - clean all env except the network update env



## cmp
**cmp** - memory compare

*Usage:*

`cmp [.b, .w, .l] addr1 addr2 count`



## cnstar
**cnstar** - do net update from the specified file that is in oad partition

*Usage:*

`cnstar`



## config2env
**config2env** - Set config to environment

*Usage:*

`config2env`



## config_raw_io
**config_raw_io** - Config the target device for raw I/O

*Usage:*

`config_raw_io SPI`

`config_raw_io NAND [partition] [volume]`

`config_raw_io MMC [volume]`

If you don't input any parameters, uboot would use the default settings



## coninfo
**coninfo** - print console devices and information

*Usage:*

`coninfo`



## costar
**costar** - do oad update from the specified file that is in oad partition

*Usage:*

`costar`



## cp
**cp** - memory copy

*Usage:*

`cp [.b, .w, .l] source target count`



## cp
**cp** - memory copy

*Usage:*

`cp [.b, .w, .l] source target count`



## crc32
**crc32** - checksum calculation

*Usage:*

`crc32 address count [addr]` - compute CRC32 checksum [save at addr]



## createMbootBak
**createMbootBak** - emmc create mbootbak partition

*Usage:*

`createMbootBak` - create MBOOTBAK partition for mboot backup



## ctv_factory_mode_check
**ctv_factory_mode_check** - factory mode to check usb files and do test

*Usage:*

`ctv_factory_mode_check`



## custar
**custar** - do usb update from the specified file that is in usb

*Usage:*

`custar`



## dbg
**dbg** - set debug message level. Default level is INFO

*Usage:*

`dbg [Level]`

Level: 'DISABLE', 'ERROR', 'INFO', 'TRACE', 'DEBUG', 'BOOTTIME'



## dbtable_init
**dbtable_init** - let data is ready (logo, music, panel, ursa)

*Usage:*

`dbtable_init`



## dc
**dc** (dcvdelete) - delete the specific cofig that is in the bootargs

*Usage:*

`dc [config]`

*For example:*

`dc autotest`



## delay
**delay** - delay time, time unit is ms

*Usage:*

`delay [time]`



## destroy_logo
**destroy_logo** - Stop logo display

*Usage:*

`destroy_logo`



## dhcp
**dhcp** - boot image via network using DHCP/TFTP protocol

*Usage:*

`dhcp [loadAddress] [[hostIPaddr:]bootfilename]`



## dont_overwrite
**dont_overwrite** - This serial apis are for protecting the specific partitions are overwrited. ex: customer

This cmd is used to register which partition should not be overwrite

*Usage:*

`dont_overwrite [partition name]`



## dont_overwrite_free
**dont_overwrite_free** - This serial apis are for protecting the specific partitions are overwrited. ex: customer

This cmd is used to free all registered partitions.

*Usage:*

`dont_overwrite_free`



## dont_overwrite_init
**dont_overwrite_init** - This serial apis are for protecting the specific partitions are overwrited. ex: customer

This cmd is used to init this function

*Usage:*

`dont_overwrite_init`



## dont_overwrite_switch
**dont_overwrite_switch** - This serial apis are for force write and re-create partitions.

This cmd is used to disable dont_overwrite function.

*Usage:*

`dont_overwrite_switch [enable/disable]`



## draw_jpg
**draw_jpg** (blt_jpg) - Blt JPG

*Usage:*

`draw_jpg`



## draw_pixel
**draw_pixel** - draw a pixel with color

*Usage:*

`draw_pixel [x] [y] [color]`

x: in Dec, y: in Dec, color: in Hex



## draw_progress
**draw_progress** - draw progressbar

*Usage:*

`draw_progress [x] [y] [color] [percent]`

x: in Dec, y: in Dec, color: in Hex, percent: in Dec



## draw_rect
**draw_rect** - draw rect with color

*Usage:*

`draw_rect [x] [y] [w] [h] [color]`

x: in Dec, y: in Dec, w: in Dec, h: in Dec, color: in Hex



## draw_string
**draw_string** - draw string with color

*Usage:*

`draw_string [string] [x] [y] [color] [attr]`

string: in char, x: in Dec, y: in Dec, color: in Hex

attr: align attrib - (0: left, 1: middle, 2: right)



## du
**du** - Disable UART

*Usage:*

`du`



## ebist
**ebist** - PHY loopback test

*Usage:*

`ebist ebist`



## echo
**echo** - echo args to console

*Usage:*

`echo [args..]`

\c suppresses newline



## editenv
**editenv** - edit environment variable

*Usage:*

`editenv [name]` - edit environment variable 'name'



## edump
**edump** - EMAC Register settings dump

*Usage:*

`edump`



## eloopback
**eloopback** - Long loopback test

*Usage:*

`eloopback`



## emmc
**emmc** - eMMC sub system

*Usage:*

| Command | Description |
| :--- | :--- |
| `emmc emmc info` | lists CSD & ExtCSD on eMMC |
| `emmc init count` | reset & init eMMC for count loops |
| `emmc test count` | verify eMMC & board signals for count loops |
| `emmc speed` | show eMMC speed sdr or ddr mode @ driver layer |
| `emmc t_table <ddr/hs200/hs400/erase/dump>` | build timing table |
| `emmc mode <sdr/best>` | SDR or choose best mode |
| `emmc clk` | set ClkRegVal |
| `emmc cis` | check or erase |
| `emmc pwr_cut init [addr][start block]` | eMMC Power Cut Init |
| `emmc pwr_cut test [addr][start block]` | eMMC Power Cut Test |
| `emmc reset [0/1]` | toggle eMMC reset pin |
| `emmc rpmb key` | program the authentication key |
| `emmc rpmb write [addr] [size] [start block]` | authenticated data write |
| `emmc rpmb read  [addr] [size] [start block]` | authenticated data read |
| `emmc rpmb test` | verify eMMC rpmb |
| `emmc rpmb getcnt` | get eMMC write counter |



## emmc_self_adaption
**emmc_self_adaption** - allocate the reset of emmc space to userdata partition

*Usage:*

`emmc_self_adaption`



## emmcbin
**emmcbin** - dump emmc and restore it to fat usb disk

*Usage:*

`emmcbin [usbportnum] [pad] [binname] [offset/partitionname] [dumpsize]`

if pad=0, dump the valid data of user area, FORCT.DEF & LEAP.DEF which are used for mass production

if [offset/partitionname] & [dumpsize] equal to 0 or NULL - dump entire emmc include boot1, boot2, user area



## emmcbootbin
**emmcbootbin** - dump emmc boot partition and write it to fat usb disk

*Usage:*

`emmcbootbin [usbportnum] [partitionname]`



## env
**env** - environment handling commands

*Usage:*

| Command | Description |
| :--- | :--- |
| `env default -f` | reset default environment |
| `env edit name` | edit environment variable |
| `env export [-t \| -b \| -c] addr [size]` | export environment |
| `env import [-d] [-t \| -b \| -c] addr [size]` | import environment |
| `env print [name ...]` | print environment |
| `env run var [...]` | run commands in an environment variable |
| `env save` | save environment |
| `env set [-f] name [arg ...]` | - |



## envload
**envload** - reload the nand environment

*Usage:*

`envload`



## epd
**epd** - emac power down

*Usage:*

`epd XX XX XX XX XX XX`



## estart
**estart** - EMAC start

*Usage:*

`estart reset` - reset EMAC controller

`estart start` - start EMAC controller



## ewavetest
**ewavetest** - EMAC wave test

*Usage:*

`ewavetest [num]`

num: 1 - 100M, 2 - 10M



## exit
**exit** - exit script

*Usage:*

`exit`



## ext2load
**ext2load** - load binary file from a Ext2 filesystem

*Usage:*

`ext2load <interface> <dev[:part]> [addr] [filename] [bytes]`

Load binary file 'filename' from 'dev' on 'interface' to address 'addr' from ext2 filesystem



## ext2ls
**ext2ls** - list files in a directory (default /)

*Usage:*

`ext2ls <interface> <dev[:part]> [directory]`

List files from 'dev' on 'interface' in a 'directory'



## ext4filelist
**ext4filelist** - list files in a directory (default /)

*Usage:*

`ext4filelist <interface> <dev[:part id/name]> [directory] [addr] [pinodenum]`

List files from 'dev' partition 'part' on 'interface' in a 'directory', write to buffer



## ext4filesize
**ext4filesize** - get file size from a Ext4 filesystem

*Usage:*

`ext4filesize <interface> <dev[:part id/name]> [filename] [addr]`

Get file 'filename' size from 'dev' partition 'part' on 'interface' to address 'addr'



## ext4load
**ext4load** - load binary file from a Ext4 filesystem

*Usage:*

`ext4load <interface> <dev[:part id/name]> [addr] [filename] [bytes]`

Load binary file 'filename' from 'dev' partition 'part' on 'interface' to address 'addr' from ext4 filesystem



## ext4ls
**ext4ls** - list files in a directory (default /)

*Usage:*

`ext4ls <interface> <dev[:part id/name]> [directory]`

List files from 'dev' partition 'part' on 'interface' in a 'directory'



## ext4partload
**ext4partload** - part load binary file from a Ext4 filesystem

*Usage:*

`ext4partload <interface> <dev[:part id/name]> [addr] [filename] [offset] [bytes]`

Load binary file 'filename' from 'dev' partition 'part' on 'interface' to address 'addr' from ext4 filesystem



## factory_check_usb_files
**factory_check_usb_files** - check usb files, enter diffrrent mode

*Usage:*

`factory_check_usb_files`



## false
**false** - do nothing, unsuccessfully

*Usage:*

`false`



## fastboot
**fastboot** - enter fastboot mode

*Usage:*

`fastboot [args..]`



## fatfilesize
**fatfilesize** - load binary file from a dos filesystem

*Usage:*

`fatfilesize <interface> <dev[:part]> <filename> <filesize>`

Load binary file 'filename' from 'dev' on 'interface' to address 'addr' from dos filesystem



## fatinfo
**fatinfo** - print information about filesystem

*Usage:*

`fatinfo <interface> <dev[:part]>`

Print information about filesystem from 'dev' on 'interface'



## fatload
**fatload** - load binary file from a dos filesystem

*Usage:*

`fatload <interface> <dev[:part]>  <addr> <filename> [bytes]`

Load binary file 'filename' from 'dev' on 'interface' to address 'addr' from dos filesystem



## fatls
**fatls** - list files in a directory (default /)

*Usage:*

`fatls <interface> <dev[:part]> [directory]`

List files from 'dev' on 'interface' in a 'directory'



## fatpartload
**fatpartload** - fatpartload - load binary file from a dos filesystem

*Usage:*

`fatpartload <interface> <dev[:part]>  <addr> <filename> <offset> [bytes]`

Load binary file 'filename' from 'dev' on 'interface' to address 'addr' from dos filesystem



## fatwrite
**fatwrite** - fatwrite - write binary file to a dos filesystem

*Usage:*

`fatwrite <interface> <dev[:part]>  <addr> <filename> [bytes]`

Load binary file 'filename' from 'dev' on 'interface' to address 'addr' from dos filesystem



## filelist
**filelist** - Dump the file list

*Usage:*

`filelist`



## filelisttest
**filelisttest** - This command is only for file list test

*Usage:*

`filelisttest`



## filepartload
**filepartload** - load part of a file to RAM

*Usage:*

`filepartload <addr> <filename> [bytes]`

Load file 'filename' to address 'addr'



## filepartloadSeg
**filepartloadSeg** - load a seg part of file to RAM

*Usage:*

`filepartloadSeg [interface(hex)] [device(hex)] [addr(hex)] [filename(hex)] [offset(hex)] [bytes(hex)]`



## flashbin
**flashbin** - dump/restore emmc or nand flash data to/from flash.bin

*Usage:*

`flashbin [binname] [dump/restore] [valid] [partitionname]`

*Comments:*

 * [valid] has effect on flash.bin when dump flash with the last partition:
   * when valid=1, only dump the last partition's valid data.
   * when valid=0, dump the last partition's entire data.
 * when dump flash without the last partition or restore flash, [valid] has no effect whether 1 or 0.
 * [partitionname] is a optional parameter, default is the whole flash without [partitionname].
 * when dump flash, flash.bin should be saved as ntfs3g/exfat supported file.
   * when restore flash, flash.bin should be stored in a usb storage device with ntfs/exfat format.



## force_overwrite
**force_overwrite** - This serial apis are for force write and re-create partitions.

This cmd is used to register which partition should force overwrite

*Usage:*

`force_overwrite [partition name]`



## force_overwrite_init
**force_overwrite_init** - This serial apis are for force write and re-create partitions.

This cmd is used to register which partition should force overwrite

*Usage:*

`force_overwrite_init`



## get_mmap
**get_mmap** - get memory info from supernova's mmap

*Usage:*

`get_mmap [ID]`

`get_mmap -l` - list all IDs that are list in mmap.ini

*For example:*

`get_mmap E_MMAP_ID_COMPROCESSOR`

#define E_MMAP_ID_COPROCESSOR_AVAILABLE  0x0000000000




## gettime
**gettime** - Get the system executing time

*Usage:*

`gettime`



## go
**go** - start application at address 'addr'

*Usage:*

`go addr [arg ...]` - start application at address 'addr' passing 'arg' as arguments



## gpio
**gpio** - GPIO Command:

*Usage:*

| Command | Description |
| :--- | :--- |
| `gpio`                              | (for 2nd parameter, you must type at least 3 characters) |
| `gpio output <gpio#> <1/0>`         | ex: `gpio output 169 1` |
| `gpio input/get <gpio#>`            | ex: `gpio input 10` (gpio 10 set as input) |
| `gpio toggle <gpio#>`               | ex: `gpio tog 49` (toggle) |
| `gpio state <gpio#>`                | ex: `gpio sta 49` (get i/o status(direction) & pin status) |
| `gpio list [num_of_pins]`           | ex: `gpio list 10` (list GPIO1~GPIO10 status) |
| `gpio check <gpio#> <IN/OUT> <1/0>` | ex: `gpio check 10 OUT 0` (check i/o status(direction) & pin status) |



## help
**help** - print command description/usage

*Usage:*

`help` - print brief description of all commands
`help command` - print detailed usage of 'command'



## i2c
**i2c** - I2C sub-system

*Usage:*

| Command | Description |
| :--- | :--- |
| `i2c crc32 chip address[.0, .1, .2] count` | compute CRC32 checksum |
| `i2c dev [dev]` | show or set current I2C bus |
| `i2c loop chip address[.0, .1, .2] [# of objects]` | looping read of device |
| `i2c md chip address[.0, .1, .2] [# of objects]` | read from I2C device |
| `i2c mm chip address[.0, .1, .2]` | write to I2C device (auto-incrementing) |
| `i2c mw chip address[.0, .1, .2] value [count]` | write to I2C device (fill) |
| `i2c nm chip address[.0, .1, .2]` | write to I2C device (constant address) |
| `i2c probe` | show devices on the I2C bus |
| `i2c read chip address[.0, .1, .2] length memaddress` | read to memory |
| `i2c reset` | re-init the I2C Controller |
| `i2c speed [speed]` | show or set I2C bus speed |



## if_boot_to_pm
**if_boot_to_pm** - if boot to PM

*Usage:*

`if_boot_to_pm`



## iminfo
**iminfo** - print header information for application image

*Usage:*

`iminfo addr [addr ...]`

Print header information for application image starting at address 'addr' in memory; this includes verification of the image contents (magic number, header and payload checksums)



## imxtract
**imxtract** - extract a part of a multi-image

*Usage:*

`imxtract addr part [dest]`

Extract <part> from legacy image at <addr> and copy to <dest>



## initDbgLevel
**initDbgLevel** - Initial varaible 'dbgLevel'

*Usage:*

`initDbgLevel`



## init_raw_io
**init_raw_io** - init raw_io module

*Usage:*

`init_raw_io`



## ir_delay
**ir_delay** - delay 300ms for IR detect

*Usage:*

`ir_delay`



## itest
**itest** - return true/false on integer compare

*Usage:*

`itest [.b, .w, .l, .s] [*]value1 <op> [*]value2`



## kernelProtect
**kernelProtect** - Protect kernel

*Usage:*

`kernelProtect`



## kernelProtectBist
**kernelProtectBist** - Protect kernel bist

*Usage:*

`kernelProtectBist`



## led
**led** - See led commands

*Usage:*

`led mbx [pattern]` - (only for 51 booting)

`led time [delay time]` - delay

`led stop` - stop led



## loadb
**loadb** - load binary file over serial line (kermit mode)

*Usage:*

`loadb [offs] [baud]`

Load binary file over serial line with offset 'offs' and baudrate 'baud'



## loadenv
**loadenv** - load env for nand

*Usage:*

`loadenv`



## loads
**loads** - load S-Record file over serial line

*Usage:*

`loads [offs]`

Load S-Record file over serial line with offset 'offs'



## loadspi
**loadspi** - load data from SPI

*Usage:*

`loadspi XX XX XX XX XX XX`



## loady
**loady** - load binary file over serial line (ymodem mode)

*Usage:*

`loady [offs] [baud]`

Load binary file over serial line with offset 'off' and baudrate 'baud'



## loop
**loop** - infinite loop on address range

*Usage:*

`loop [.b, .w, .l] address number_of_objects`



## lz4
**lz4** - LZ4 decompress

*Usage:*

`lz4 -d [src_addr] [src_len] [dest_addr] [dest_len]`



## m2e
**m2e** - Restore the address and len to env from supernova's mmap

*Usage:*

`m2e [ID] [n1] [n2]`

*For example:*

ID: E_MMAP_ID_PM51_USAG

n1: This is an name of env, this env store the addr for ID

n2: This is an name of env, this env store the len for ID



## macaddr
**macaddr** - setup EMAC MAC addr

*Usage:*

`macaddr XX XX XX XX XX XX`



## mbootver_set
**mbootver_set** (setmbootver) - for customer show in factory menu

*Usage:*

`mbootver_set [v]`



## mbup
**mbup** - mboot upgrade

*Usage:*

`mbup [mboot dram buffer addr] [mboot size]`



## md
**md** - memory display

*Usage:*

`md [.b, .w, .l] address [# of objects]`



## memtest
**memtest** - Get the performance of memory

*Usage:*

`memtest` - Get the performance of memory



## miuProtect
**miuProtect** - Protect miu

*Usage:*

`miuProtect`



## mm
**mm** - memory modify (auto-incrementing address)

*Usage:*

`mm [.b, .w, .l] address`



## mmc
**mmc** - MMC sub system

*Note:*
 
enh_attr = 0: no slc mode 1: using slc mode

ext_attr = 0: no attr 1: system code 2: Non-persisent

relwr_attr = 0: disable 1: enable reliable write

*Usage:*

| Command | Description |
| :--- | :--- |
| `mmc read[.boot\|.gp] [bootpart\|gppart] addr blk# size` | read from mmc boot part to addr |
| `mmc write[.boot\|.gp] [bootpart\|gppart] addr blk# size [empty_skip: 0-disable, 1-enable]` | write from addr to mmc boot part |
| `mmc readall` | read all blocks for device internal ecc check |
| `mmc crcall` | read all blocks and calculate crc32 |
| `mmc read.p addr partition_name size` | read from mmc user part to addr |
| `mmc read.p.continue addr partition_name offset size` | continue read |
| `mmc write.p addr partition_name size [empty_skip:0-disable,1-enable]` | write from addr to mmc user part |
| `mmc write.p.continue addr partition_name offset size [empty_skip: 0-disable, 1-enable]` | continue write |
| `mmc rescan` | rescan mmc partitions |
| `mmc part[.gp]` | lists available [GP] partition on current mmc device |
| `mmc look [name]` | lists specific partition info on mmc |
| `mmc dev [dev] [part]` | show or set current mmc device [partition] |
| `mmc list` | lists available devices |
| `mmc create [name] [size]` | create/change mmc partition [name] |
| `mmc create.gp part_no size enh_attr ext_attr relwr_attr` | create/change eMMC GP partition No.[part_no(0~3)] with size and enhance/extended/reliable_write attribute |
| `mmc create.enhusr start_addr size enha_attr relwr_atrr` | create/change eMMC enhance user partition(slc mode) from start_addr with size and enhance/reliable_write attribute |
| `mmc create.complete` | complete eMMC gp, enhance user, reliable write partition setting |
| `mmc remove [name]` | remove mmc partition [name] |
| `mmc rmgpt[.all]` | clean all mmc partition table |
| `mmc slc size relwr` | set slc in the front of user area, 0xffffffff means max slc size |
| `mmc ecsd` | print ecsd register of emmc |
| `mmc setecsd num mask value` | set value to num of ecsd according to mask |
| `mmc size` | print the mmc size info |
| `mmc slcchk` | check the slc/mlc mode of emmc |
| `mmc relwrchk` | check the reliable write configuration of emmc |
| `mmc slcrelwrchk` | check the slc/mlc mode and reliable write configuration of emmc |
| `mmc unlzo Addr Length Part_Name [empty_skip: 0-disable, 1-enable]` | decompress lzo file and write to mmc partition |
| `mmc erase[.boot] bootpart [blk#] [size]` | erase partition (boot area) |
| `mmc erase.p partition_name` | erase partition (user area) |
| `mmc erase` | erase all blocks in device |
| `mmc erase customer` | erase all blocks except MBOOT partition and MPOOL partition |
| `mmc dd mmc2usb/usb2mmc [portnum] [pad]` | dump/restore emmc raw data |
| `mmc alignsize` | check the alignment size of slc partition |
| `mmc trim_test [chunk_size] [loop_count]` | test read/write performance after trim enabled |
| `mmc clonepart [src] [dst]` | clone <src> partition to <dst> |
| `mmc writeprotect.boot2` | enable writeprotect about boot2 partition |




## mmcbininfo
**mmcbininfo** - Valid block num in each partition

*Usage:*

`mmcbininfo [usbportnum]`




## mmcinfo
**mmcinfo** - display MMC info

*Usage:*

`mmcinfo` - device number of the device to dislay info of



## mmcreg
**mmcreg** - mmcreg show ext-csd

*Usage:*

`mmcreg <dev num>` - device number of the device to dislay info of



## modelinfo
**modelinfo** - check model info if need sync to sync dbpool

*Usage:*

`modelinfo`



## mscompress7
**mscompress7** - Compress or decompress lzma files

*Usage:*

`mscompress7 lzma <e|d> <index> Src_Address Src_Length Dst_Address`

e: encode file, d: decode file, <index> start to (de)compress position



## msg
**msg** - print string

*Usage:*

`msg [string]`



## mstar
**mstar** - update kernel & root file system automatically by script file

*Usage:*

`mstar [script_file_name]`

Set CmdAbort = 0 in env to ignore the abort when cmd error



## mstar_usb
**mstar_usb** - MStar USB Driver Porting

*Usage:*

`mstar_usb`



## mtest
**mtest** - simple RAM read/write test

*Usage:*

`mtest [start [end [pattern [iterations]]]]`



## multi2optee
**multi2optee** - For Multi Optee Image writting to EMMC

*Usage:*

`multi2optee multi2optee [address] [partition] [size]`



## mversion
**mversion** - show changelist

*Usage:*

`mversion`



## mw
**mw** - memory write (fill)

*Usage:*

`mw [.b, .w, .l] address value [count]`



## nm
**nm** - memory modify (constant address)

*Usage:*

`nm [.b, .w, .l] address`



## nstar
**nstar** - update softwave system automatically via net

*Usage:*

`nstar`



## nuttxProtect
**nuttxProtect** - Protect nuttx

*Usage:*

`nuttxProtect [start addr] [end addr]`



## osd_create
**osd_create** - create osd layer

*Usage:*

`osd_create [w(dec)] [h(dec)]`



## osd_destroy
**osd_destroy** - destroy osd layer

*Usage:*

`osd_destroy`



## osd_flush
**osd_flush** - flush canvas to screen

*Usage:*

`osd_flush`



## ostar
**ostar** - update softwave system automatically via oad

*Usage:*

`ostar`



## ota_zip_check
**ota_zip_check** - do OTA zip package check

*Usage:*

`ota_zip_check` - check 'update_signed.zip' in usb_disk

`ota_zip_check emmc abspath` - check abspath in emmc



## panel_init
**panel_init** - init panel by panel.ini

*Usage:*

`panel_init [option]`

-s : static init : panel init para from uboot

-d : dynamic init : panel init para from SN



## panel_post_init
**panel_post_init** - backlight on

*Usage:*

`panel_post_init`



## panel_pre_init
**panel_pre_init** - init panel by panel.ini

*Usage:*

`panel_pre_init [option]`

-s : static init : panel init para from uboot

-d : dynamic init : panel init para from SN



## ping
**ping** - send ICMP ECHO_REQUEST to network host

*Usage:*

`ping [pingAddress]`



## pm51
**pm51** - pm51 command

*Usage:*

`pm51 [option]`

| Command | Description |
| :--- | :--- |
| `pm51 stop` | stop 51 processor |
| `pm51 start` | start 51 processor |
| `pm51 readpc` | get 51 program counter |
| `pm51 standby` | standby |



## pmProtect
**pmProtect** - Protect runtime PM

*Usage:*

`pmProtect`



## pop_raw_io_config
**pop_raw_io_config** - pop raw_io last config

*Usage:*

`pop_raw_io_config`



## printenv
**printenv** - print environment variables

*Usage:*

`printenv` - print values of all environment variables

`printenv name ...` - print value of environment variable 'name'



## push_raw_io_config
**push_raw_io_config** - push raw_io current config

*Usage:*

`push_raw_io_config`



## qhb_check
**qhb_check** - run QHB flag check

*Usage:*

`qhb_check`



## raw_io_status
**raw_io_status** - get raw_io status

*Usage:*

`raw_io_status`



## raw_read
**raw_read** - Read the raw datas that store in the target device

You have to execute 'config_raw_io' before using this cmd

*Usage:*

`raw_read [dram addr] [offset] [len]` - unit:bytes



## raw_write
**raw_write** - Write the raw datas that store in the target device

You have to execute 'config_raw_io' before using this cmd

*Usage:*

`raw_write [dram addr] [offset] [len]` - unit:bytes



## readArmFw
**readArmFw** - read Nuttx to malloc buffer

*Usage:*

`readArmFw`



## readOptee
**readOptee** - core1 run at Nuttx

*Usage:*

`readOptee`



## recovery_wipe_partition
**recovery_wipe_partition** - do recovery wipe data or cache


*Usage:*

`recovery_wipe_partition [name]`



## reload_mac
**reload_mac** - Reload mac address from supernova to env

*Usage:*

`reload_mac`


## reset
**reset** - Perform RESET of the CPU

*Usage:*

`reset`



## riu
**riu** - riu command

*Usage:*

`riu wword [target][value]`

`riu rword [target]`

`riu wbyte [target][value]`

`riu rbyte [target]`

`riu bit   [target][bit][(1/0)]`



## run
**run** - run commands in an environment variable

*Usage:*

`run var [...]` - run the commands in the environment variable(s) 'var'



## sar
**sar** - sar Command:

*Usage:*

`sar [0-base, SAR0~SAR5]`

`sar <ch#>` : ex: `sar 0` // read sar channel 0



## saveenv
**saveenv** - save environment variables to persistent storage

*Usage:*

`saveenv`



## setMtkBT
**setMtkBT** - load mtk bt patch, and set woble

*Usage:*

`setMtkBT`



## setenv
**setenv** - set environment variables

*Usage:*

`setenv name value ...` - set environment variable 'name' to 'value ...'

`setenv name` - delete environment variable 'name'



## showboard
**showboard** - Show board information

*Usage:*

`showboard`



## showtb
**showtb** - Show register command table

*Usage:*

`showtb [stage]`

0:ALL, 1:MsInit, 2:MsProcess, 3:MsToKernel



## showvar
**showvar** - print local hushshell variables

*Usage:*

`showvar` - print values of all hushshell variables
`showvar name ...` - print value of hushshell variable 'name'



## showversion
**showversion** - Show version

*Usage:*

`showversion`




## sleep
**sleep** - delay execution for some time

*Usage:*

`sleep [N]` - delay execution for N seconds (N is decimal!)



## smc
**smc** - jump to arm_trusted_firmware

*Usage:*

`smc`



## source
**source** - run script from memory

*Usage:*

`source [addr]`

Run script starting at addr, a valid image header must be present



## sparse_write
**sparse_write** - do sparse image writing to target flash type

*Usage:*

`sparse_write [flash_type] [dram_addr] [partitionname] [image_size]`



## spi2usb
**spi2usb** - Read data from spi to usb

*Usage:*

`spi2usb [spi offset] [length] [output file name]`



## sync_mmap
**sync_mmap** - Sync the some id's address and len to env and bootargs from supernova's mmap

*Usage:*

`sync_mmap`



## test
**test** - minimal test like /bin/sh

*Usage:*

`test [args..]`



## testmode
**testmode** - set testmode into bootargs

*Usage:*

`testmode [mode]`

Mode: autotest, moduletest, hsl, mdebugtest



## tftpboot
**tftpboot** - boot image via network using TFTP protocol

*Usage:*

`tftpboot [loadAddress] [[hostIPaddr:]bootfilename]`



## true
**true** - do nothing, successfully

*Usage:*

`true`



## udstar
**udstar** - Execute the script file that is stored in usb disk

*Usage:*

`udstar [script_file_name]`

If you don't input a file name, udstar will use the defatult (/MstarDebug.script) file name



## unlockcmi
**unlockcmi** - unlock cmi transfer board

*Usage:*

`unlockcmi`



## update_mode
**update_mode** - get/set update_mode

*Usage:*

`update_mode <g/s> [EN_UPDATE_MODE]`

EN_UPDATE_MODE: 'EN_UPDATE_MODE_NONE', 'EN_UPDATE_MODE_TFTP', 'EN_UPDATE_MODE_USB', 'EN_UPDATE_MODE_OAD', 'EN_UPDATE_MODE_NET', 'EN_UPDATE_MODE_USB_WITH_SEG_DECRYPTED', 'EN_UPDATE_MODE_NET_WITH_SEG_DECRYPTED'



## updatemiureg
**updatemiureg** - Call driver to update miu setting

*Usage:*

`updatemiureg` - By Env MIU0(1)_GROUP_PRIORITY



## usb
**usb** - USB sub-system

*Usage:*

| Command | Description |
| :--- | :--- |
| `usb reset [dev]` | reset (rescan) USB controller |
| `usb start [dev]` | start (scan) USB controller |
| `usb stop [f]` | stop USB [f]=force stop |
| `usb tree` | show USB device tree |
| `usb info [dev]` | show available USB devices |
| `usb storage` | show details of USB storage devices |
| `usb dev [dev]` | show or set current USB storage device |
| `usb part [dev]` | print partition table of one or all USB storage devices |
| `usb read addr blk# cnt` | read `cnt' blocks starting at block `blk#' to memory address `addr' |
| `usb write addr blk# cnt` | write `cnt' blocks starting at block `blk#' from memory address `addr' |
| `usb wait [time]` | set usb connection detection waiting time (ms) |



## usb2spi
**usb2spi** - write data from usb to spi

*Usage:*

`usb2spi [spi offset] [length] [intput file name]`



## usb_bin_check
**usb_bin_check** - do usb bin document check.

*Usage:*

`usb_bin_check`



## usb_partial_upgrade_to_emmc
**usb_partial_upgrade_to_emmc** - partial upgrade from USB to eMMC

*Usage:*

`usb_partial_upgrade_to_emmc`



## usb_super_upgrade_to_emmc
**usb_super_upgrade_to_emmc** - super upgrade from USB to eMMC

*Usage:*

`usb_super_upgrade_to_emmc`



## usbboot
**usbboot** - boot from USB device

*Usage:*

`usbboot [loadAddr] [dev:part]`



## ustar
**ustar** - update kernal & root file system automatically by script file

*Usage:*

`ustar [script_file_name]`

When use this command at first use usb start then use ustar



## version
**version** - print monitor, compiler and linker version

*Usage:*

`version`



## wdt_enable
**wdt_enable** - set Watchdog timer

*Usage:*

`wdt_enable [n]` - set Watchdog timer to n secs

# OSD Example

	osd_create 1920 1080
	draw_rect 1 1 1920 1080 F1F2F3
	draw_pixel 400 400 FF0000
	draw_rect 300 300 10 10 00FF00
	draw_progress 600 600 FF00FF 35
	draw_string 500 500 0000FF 0 Privet
	osd_destroy
