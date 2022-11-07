# Mstar Commands

| Command | Description |
| --- | --- |
| `?` | alias for `help` |
| `CmdPerformanceTest` |  |
| `gettime` | Get the system executing time |
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
| `dcvdelete` | Delete the specific config that is in the bootargs |
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
| `usbboot` | boot from USB device |
| `ustar` | update kernal & root file system automatically by script file |
| `version` | print monitor, compiler and linker version |
| `wdt_enable` | wdt_enable n - set Watchdog timer to n secs |

	osd_create 1920 1080
	draw_rect 1 1 1920 1080 F1F2F3
	draw_pixel 400 400 FF0000
	draw_rect 300 300 10 10 00FF00
	draw_progress 600 600 FF00FF 35
	draw_string 500 500 0000FF 0 Privet
	osd_destroy
