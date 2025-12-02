

```bash
ONIE:/ # onie-nos-install http://10.21.0.6/sonic-broadcom-enterprise-base.bin
discover: installer mode detected.
Stopping: discover... done.
Info: Attempting http://10.21.0.6/sonic-broadcom-enterprise-base.bin ...
Connecting to 10.21.0.6 (10.21.0.6:80)
installer            100% |*******************************|  1086M  0:00:00 ETA
ONIE: Executing installer: http://10.21.0.6/sonic-broadcom-enterprise-base.bin
Verifying image checksum ... OK.
Preparing image archive ... OK.
Installing SONiC in ONIE
ONIE Installer: platform: x86_64-broadcom-r0
onie_platform: x86_64-accton_as9516_32d-r0
Partition #1 is in use.
Partition #2 is in use.
Partition #3 is available
Creating new SONiC-OS partition /dev/sda3 ...
Warning: The kernel is still using the old partition table.
The new table will be used at the next reboot.
The operation has completed successfully.
mke2fs 1.42.13 (17-May-2015)
Discarding device blocks: done
Creating filesystem with 8388608 4k blocks and 2097152 inodes
Filesystem UUID: 032df394-8f31-4aef-8948-420781ffc0af
Superblock backups stored on blocks:
        32768, 98304, 163840, 229376, 294912, 819200, 884736, 1605632, 2654208,
        4096000, 7962624

Allocating group tables: done
Writing inode tables: done
Creating journal (32768 blocks): done
Writing superblocks and filesystem accounting information: done

Installing SONiC to /tmp/tmp.P20VX9/image-4.4.3-Enterprise_Base
Archive:  fs.zip
   creating: boot/
  inflating: boot/initrd.img-5.10.0-21-amd64
  inflating: boot/grubx64.efi
  inflating: boot/shimx64.efi
  inflating: boot/mmx64.efi
  inflating: boot/vmlinuz-5.10.0-21-amd64
  inflating: boot/config-5.10.0-21-amd64
  inflating: boot/System.map-5.10.0-21-amd64
   creating: platform/
   creating: platform/x86_64-ufispace_s9300_32d-r0/
  inflating: platform/x86_64-ufispace_s9300_32d-r0/sonic-platform-ufispace-s9300-32d_1.0.0_amd64.deb
   creating: platform/x86_64-supermicro_sse_t8196-r0/
  inflating: platform/x86_64-supermicro_sse_t8196-r0/platform-modules-sse-t8196_0.1_amd64.deb
   creating: platform/x86_64-huaqin-ns8420-hq-r0/
  inflating: platform/x86_64-huaqin-ns8420-hq-r0/platform-modules-huaqin-ns8420_0.1_amd64.deb
   creating: platform/x86_64-supermicro_sse_t8164-r0/
  inflating: platform/x86_64-supermicro_sse_t8164-r0/platform-modules-sse-t8164_0.1_amd64.deb
   creating: platform/x86_64-ufispace_s6301_56st-r0/
  inflating: platform/x86_64-ufispace_s6301_56st-r0/sonic-platform-ufispace-s6301-56st_1.0.0_amd64.deb
   creating: platform/x86_64-ufispace_s7801_54xs-r0/
  inflating: platform/x86_64-ufispace_s7801_54xs-r0/sonic-platform-ufispace-s7801-54xs_1.0.0_amd64.deb
   creating: platform/x86_64-ufispace_s8901_54xc-r0/
  inflating: platform/x86_64-ufispace_s8901_54xc-r0/sonic-platform-ufispace-s8901-54xc_1.0.0_amd64.deb
   creating: platform/x86_64-ufispace_s9110_32x-r0/
  inflating: platform/x86_64-ufispace_s9110_32x-r0/sonic-platform-ufispace-s9110-32x_1.0.0_amd64.deb
   creating: platform/x86_64-ufispace_s9301_32db-r0/
  inflating: platform/x86_64-ufispace_s9301_32db-r0/sonic-platform-ufispace-s9301-32db_1.0.0_amd64.deb
   creating: platform/x86_64-ufispace_s9321_64e-r0/
  inflating: platform/x86_64-ufispace_s9321_64e-r0/sonic-platform-ufispace-s9321-64e_1.0.0_amd64.deb
   creating: platform/x86_64-ufispace_s9321_64eo-r0/
  inflating: platform/x86_64-ufispace_s9321_64eo-r0/sonic-platform-ufispace-s9321-64eo_1.0.0_amd64.deb
   creating: platform/x86_64-wistron_so_bi48b_4e-r0/
  inflating: platform/x86_64-wistron_so_bi48b_4e-r0/sonic-platform-wistron-so-bi48b-4e_1.0_amd64.deb
   creating: platform/x86_64-delta_agc032-r0/
  inflating: platform/x86_64-delta_agc032-r0/platform-modules-agc032_1.1_amd64.deb
   creating: platform/x86_64-cel_belgite-r0/
  inflating: platform/x86_64-cel_belgite-r0/platform-modules-belgite_0.9_amd64.deb
   creating: platform/x86_64-cel_silverstone_dp-r0/
  inflating: platform/x86_64-cel_silverstone_dp-r0/platform-modules-silverstone-dp_0.9_amd64.deb
   creating: platform/x86_64-cel_silverstone-r0/
  inflating: platform/x86_64-cel_silverstone-r0/platform-modules-silverstone_0.9_amd64.deb
   creating: platform/x86_64-delta_ag9032v2a-r0/
  inflating: platform/x86_64-delta_ag9032v2a-r0/platform-modules-ag9032v2a_1.1_amd64.deb
   creating: platform/x86_64-bcm_xlr_th5_svk-r0/
  inflating: platform/x86_64-bcm_xlr_th5_svk-r0/sonic-platform-brcm-xlr-gts-th5-svk_1.0_amd64.deb
   creating: platform/x86_64-bcm_xlr-r0/
  inflating: platform/x86_64-bcm_xlr-r0/sonic-platform-brcm-xlr-gts_1.0_amd64.deb
   creating: platform/x86_64-alphanetworks_scg60d0_484t-r0/
  inflating: platform/x86_64-alphanetworks_scg60d0_484t-r0/sonic-platform-alphanetworks-scg60d0-484t_1.0_amd64.deb
   creating: platform/x86_64-alphanetworks_bes2348t-r0/
  inflating: platform/x86_64-alphanetworks_bes2348t-r0/sonic-platform-alphanetworks-bes2348t_1.0_amd64.deb
   creating: platform/x86_64-alphanetworks_snj61d0_320f-r3/
  inflating: platform/x86_64-alphanetworks_snj61d0_320f-r3/sonic-platform-alphanetworks-snj61d0-320f_1.0_amd64.deb
   creating: platform/x86_64-alphanetworks_snj60d0_320f-r0/
  inflating: platform/x86_64-alphanetworks_snj60d0_320f-r0/sonic-platform-alphanetworks-snj60d0-320f_1.0_amd64.deb
   creating: platform/x86_64-alphanetworks_snj60b0_320f-r0/
  inflating: platform/x86_64-alphanetworks_snj60b0_320f-r0/sonic-platform-alphanetworks-snj60b0-320f_1.0_amd64.deb
   creating: platform/x86_64-alphanetworks_snh60b0_640f-r0/
  inflating: platform/x86_64-alphanetworks_snh60b0_640f-r0/sonic-platform-alphanetworks-snh60b0-640f_1.0_amd64.deb
   creating: platform/x86_64-alphanetworks_snh60a0_320fv2-r0/
  inflating: platform/x86_64-alphanetworks_snh60a0_320fv2-r0/sonic-platform-alphanetworks-snh60a0-320fv2_1.0_amd64.deb
   creating: platform/x86_64-micas_m2-w6520-24dc8qc-r0/
  inflating: platform/x86_64-micas_m2-w6520-24dc8qc-r0/platform-modules-micas-m2-w6520-24dc8qc_1.0_amd64.deb
   creating: platform/x86_64-micas_m2-w6510-48v8c-r0/
  inflating: platform/x86_64-micas_m2-w6510-48v8c-r0/platform-modules-micas-m2-w6510-48v8c_1.0_amd64.deb
   creating: platform/x86_64-micas_m2-w6510-48gt4v-r0/
  inflating: platform/x86_64-micas_m2-w6510-48gt4v-r0/platform-modules-micas-m2-w6510-48gt4v_1.0_amd64.deb
   creating: platform/x86_64-micas_m2-w6940-64oc-r0/
  inflating: platform/x86_64-micas_m2-w6940-64oc-r0/platform-modules-micas-m2-w6940-64oc_1.0_amd64.deb
   creating: platform/x86_64-micas_m2-w6940-128qc-r0/
  inflating: platform/x86_64-micas_m2-w6940-128qc-r0/platform-modules-micas-m2-w6940-128qc_1.0_amd64.deb
   creating: platform/x86_64-micas_m2-w6510-32c-r0/
  inflating: platform/x86_64-micas_m2-w6510-32c-r0/platform-modules-micas-m2-w6510-32c_1.0_amd64.deb
   creating: platform/x86_64-micas_m2-w6930-64qc-r0/
  inflating: platform/x86_64-micas_m2-w6930-64qc-r0/platform-modules-micas-m2-w6930-64qc_1.0_amd64.deb
   creating: platform/x86_64-micas_m2-w6920-32qc2x-r0/
  inflating: platform/x86_64-micas_m2-w6920-32qc2x-r0/platform-modules-micas-m2-w6920-32qc2x_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix7t_dnv-r0/
  inflating: platform/x86_64-quanta_ix7t_dnv-r0/sonic-platform-extreme-slx9250-32c_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix8f_dnv-r0/
  inflating: platform/x86_64-quanta_ix8f_dnv-r0/sonic-platform-extreme-slx9150-48y_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix9_bwde-r0/
  inflating: platform/x86_64-quanta_ix9_bwde-r0/sonic-platform-quanta-ix9-32x_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix8a_bwde-r0/
  inflating: platform/x86_64-quanta_ix8a_bwde-r0/sonic-platform-quanta-ix8a-bwde-56x_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix8c_bwde-r0/
  inflating: platform/x86_64-quanta_ix8c_bwde-r0/sonic-platform-quanta-ix8c-56x_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix8_rglbmc-r0/
  inflating: platform/x86_64-quanta_ix8_rglbmc-r0/sonic-platform-quanta-ix8-56x_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix7_bwde-r0/
  inflating: platform/x86_64-quanta_ix7_bwde-r0/sonic-platform-quanta-ix7-bwde-32x_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix7_rglbmc-r0/
  inflating: platform/x86_64-quanta_ix7_rglbmc-r0/sonic-platform-quanta-ix7-32x_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix4_bwde-r0/
  inflating: platform/x86_64-quanta_ix4_bwde-r0/sonic-platform-quanta-ix4-64x_1.0_amd64.deb
   creating: platform/x86_64-quanta_ix1b_rglbmc-r0/
  inflating: platform/x86_64-quanta_ix1b_rglbmc-r0/sonic-platform-quanta-ix1b-32x_1.0_amd64.deb
   creating: platform/x86_64-delta_et-6248brb-r0/
  inflating: platform/x86_64-delta_et-6248brb-r0/platform-modules-et-6248brb_1.1_amd64.deb
   creating: platform/x86_64-delta_ag5648-r0/
  inflating: platform/x86_64-delta_ag5648-r0/platform-modules-ag5648_1.1_amd64.deb
   creating: platform/x86_64-delta_ag9064-r0/
  inflating: platform/x86_64-delta_ag9064-r0/platform-modules-ag9064_1.1_amd64.deb
   creating: platform/x86_64-delta_ag9032v1-r0/
  inflating: platform/x86_64-delta_ag9032v1-r0/platform-modules-ag9032v1_1.1_amd64.deb
   creating: platform/x86_64-cls_ds4101-r0/
  inflating: platform/x86_64-cls_ds4101-r0/platform-modules-ds4101_1.0_amd64.deb
   creating: platform/x86_64-cls_ds4000-r0/
  inflating: platform/x86_64-cls_ds4000-r0/platform-modules-ds4000_1.0_amd64.deb
   creating: platform/x86_64-cls_ds3000-r0/
  inflating: platform/x86_64-cls_ds3000-r0/platform-modules-ds3000_1.0_amd64.deb
   creating: platform/x86_64-cls_ds2000-r0/
  inflating: platform/x86_64-cls_ds2000-r0/platform-modules-ds2000_1.0_amd64.deb
   creating: platform/x86_64-cls_ds1000-r0/
  inflating: platform/x86_64-cls_ds1000-r0/platform-modules-ds1000_1.0_amd64.deb
   creating: platform/x86_64-cls_ds5000-r0/
  inflating: platform/x86_64-cls_ds5000-r0/platform-modules-ds5000_0.9_amd64.deb
   creating: platform/x86_64-cel_ds2000-r0/
  inflating: platform/x86_64-cel_ds2000-r0/platform-modules-ds2000_0.9_amd64.deb
   creating: platform/x86_64-cel_silverstone_v2-r0/
  inflating: platform/x86_64-cel_silverstone_v2-r0/platform-modules-silverstone-v2_0.9_amd64.deb
   creating: platform/x86_64-cel_ds3000-r0/
  inflating: platform/x86_64-cel_ds3000-r0/platform-modules-ds3000_0.9_amd64.deb
   creating: platform/x86_64-cel_ds4101-r0/
  inflating: platform/x86_64-cel_ds4101-r0/platform-modules-ds4101_0.9_amd64.deb
   creating: platform/x86_64-cel_questone_2-r0/
  inflating: platform/x86_64-cel_questone_2-r0/platform-modules-questone2_0.9_amd64.deb
   creating: platform/x86_64-cel_seastone_2-r0/
  inflating: platform/x86_64-cel_seastone_2-r0/platform-modules-seastone2_0.9_amd64.deb
   creating: platform/x86_64-cel_e1031-r0/
  inflating: platform/x86_64-cel_e1031-r0/platform-modules-haliburton_0.9_amd64.deb
   creating: platform/x86_64-cel_seastone-r0/
  inflating: platform/x86_64-cel_seastone-r0/platform-modules-dx010_0.9_amd64.deb
   creating: platform/x86_64-accton_as9737_32db-r0/
  inflating: platform/x86_64-accton_as9737_32db-r0/sonic-platform-accton-as9737-32db_1.1_amd64.deb
   creating: platform/x86_64-accton_as9817_64d-r0/
  inflating: platform/x86_64-accton_as9817_64d-r0/sonic-platform-accton-as9817-64d_1.1_amd64.deb
   creating: platform/x86_64-accton_as9817_64o-r0/
  inflating: platform/x86_64-accton_as9817_64o-r0/sonic-platform-accton-as9817-64o_1.1_amd64.deb
   creating: platform/x86_64-accton_as4625_54t-r0/
  inflating: platform/x86_64-accton_as4625_54t-r0/sonic-platform-accton-as4625-54t_1.1_amd64.deb
   creating: platform/x86_64-accton_as4625_54p-r0/
  inflating: platform/x86_64-accton_as4625_54p-r0/sonic-platform-accton-as4625-54p_1.1_amd64.deb
   creating: platform/x86_64-accton_as4630_54npe-r0/
  inflating: platform/x86_64-accton_as4630_54npe-r0/sonic-platform-accton-as4630-54npe_1.1_amd64.deb
   creating: platform/x86_64-accton_as4630_54te-r0/
  inflating: platform/x86_64-accton_as4630_54te-r0/sonic-platform-accton-as4630-54te_1.1_amd64.deb
   creating: platform/x86_64-accton_as7315_27xb-r0/
  inflating: platform/x86_64-accton_as7315_27xb-r0/sonic-platform-accton-as7315-27xb_1.1_amd64.deb
   creating: platform/x86_64-accton_as7312_54xs-r0/
  inflating: platform/x86_64-accton_as7312_54xs-r0/sonic-platform-accton-as7312-54xs_1.1_amd64.deb
   creating: platform/x86_64-accton_as5835_54t-r0/
  inflating: platform/x86_64-accton_as5835_54t-r0/sonic-platform-accton-as5835-54t_1.1_amd64.deb
   creating: platform/x86_64-accton_as9736_64d-r0/
  inflating: platform/x86_64-accton_as9736_64d-r0/sonic-platform-accton-as9736-64d_1.1_amd64.deb
   creating: platform/x86_64-accton_as9726_32d-r0/
  inflating: platform/x86_64-accton_as9726_32d-r0/sonic-platform-accton-as9726-32d_1.1_amd64.deb
   creating: platform/x86_64-accton_as9716_32d-r0/
  inflating: platform/x86_64-accton_as9716_32d-r0/sonic-platform-accton-as9716-32d_1.1_amd64.deb
   creating: platform/x86_64-accton_as5835_54x-r0/
  inflating: platform/x86_64-accton_as5835_54x-r0/sonic-platform-accton-as5835-54x_1.1_amd64.deb
   creating: platform/x86_64-accton_as5812_54t-r0/
  inflating: platform/x86_64-accton_as5812_54t-r0/sonic-platform-accton-as5812-54t_1.1_amd64.deb
   creating: platform/x86_64-accton_as5812_54x-r0/
  inflating: platform/x86_64-accton_as5812_54x-r0/sonic-platform-accton-as5812-54x_1.1_amd64.deb
   creating: platform/x86_64-accton_minipack-r0/
  inflating: platform/x86_64-accton_minipack-r0/sonic-platform-accton-minipack_1.1_amd64.deb
   creating: platform/x86_64-accton_as4630_54pe-r0/
  inflating: platform/x86_64-accton_as4630_54pe-r0/sonic-platform-accton-as4630-54pe_1.1_amd64.deb
   creating: platform/x86_64-accton_as7726_32x-r0/
  inflating: platform/x86_64-accton_as7726_32x-r0/sonic-platform-accton-as7726-32x_1.1_amd64.deb
   creating: platform/x86_64-accton_as6712_32x-r0/
  inflating: platform/x86_64-accton_as6712_32x-r0/sonic-platform-accton-as6712-32x_1.1_amd64.deb
   creating: platform/x86_64-accton_as7716_32xb-r0/
  inflating: platform/x86_64-accton_as7716_32xb-r0/sonic-platform-accton-as7716-32xb_1.1_amd64.deb
   creating: platform/x86_64-accton_as7326_56x-r0/
  inflating: platform/x86_64-accton_as7326_56x-r0/sonic-platform-accton-as7326-56x_1.1_amd64.deb
   creating: platform/x86_64-accton_as7312_54x-r0/
  inflating: platform/x86_64-accton_as7312_54x-r0/sonic-platform-accton-as7312-54x_1.1_amd64.deb
   creating: platform/x86_64-accton_as7716_32x-r0/
  inflating: platform/x86_64-accton_as7716_32x-r0/sonic-platform-accton-as7716-32x_1.1_amd64.deb
   creating: platform/x86_64-accton_as7816_64x-r0/
  inflating: platform/x86_64-accton_as7816_64x-r0/sonic-platform-accton-as7816-64x_1.1_amd64.deb
   creating: platform/x86_64-accton_as5712_54x-r0/
  inflating: platform/x86_64-accton_as5712_54x-r0/sonic-platform-accton-as5712-54x_1.1_amd64.deb
   creating: platform/x86_64-accton_as7712_32x-r0/
  inflating: platform/x86_64-accton_as7712_32x-r0/sonic-platform-accton-as7712-32x_1.1_amd64.deb
   creating: platform/x86_64-dell_s4348f-r0/
  inflating: platform/x86_64-dell_s4348f-r0/platform-modules-s4348f_1.1_amd64.deb
   creating: platform/x86_64-dell_s3248t-r0/
  inflating: platform/x86_64-dell_s3248t-r0/platform-modules-s3248t_1.1_amd64.deb
   creating: platform/x86_64-dellemc_s5448f-r0/
  inflating: platform/x86_64-dellemc_s5448f-r0/platform-modules-s5448f_1.1_amd64.deb
   creating: platform/x86_64-delta_dds64c8-r0/
  inflating: platform/x86_64-delta_dds64c8-r0/platform-modules-dds64c8_1.1_amd64.deb
   creating: platform/x86_64-dell_z9864f-r0/
  inflating: platform/x86_64-dell_z9864f-r0/platform-modules-z9864f_1.1_amd64.deb
   creating: platform/x86_64-dell_z9664f-r0/
  inflating: platform/x86_64-dell_z9664f-r0/platform-modules-z9664f_1.1_amd64.deb
   creating: platform/x86_64-dell_e3248pxe-r0/
  inflating: platform/x86_64-dell_e3248pxe-r0/platform-modules-e3248pxe_1.1_amd64.deb
   creating: platform/x86_64-dell_e3248p-r0/
  inflating: platform/x86_64-dell_e3248p-r0/platform-modules-e3248p_1.1_amd64.deb
   creating: platform/x86_64-dellemc_z9432f_c3758-r0/
  inflating: platform/x86_64-dellemc_z9432f_c3758-r0/platform-modules-z9432f_1.1_amd64.deb
   creating: platform/x86_64-dellemc_s5224f_c3538-r0/
  inflating: platform/x86_64-dellemc_s5224f_c3538-r0/platform-modules-s5224f_1.1_amd64.deb
   creating: platform/x86_64-dellemc_n3248pxe_c3338-r0/
  inflating: platform/x86_64-dellemc_n3248pxe_c3338-r0/platform-modules-n3248pxe_1.1_amd64.deb
   creating: platform/x86_64-dellemc_n3248p_c3338-r0/
  inflating: platform/x86_64-dellemc_n3248p_c3338-r0/platform-modules-n3248p_1.1_amd64.deb
   creating: platform/x86_64-dellemc_n3248x_c3338-r0/
  inflating: platform/x86_64-dellemc_n3248x_c3338-r0/platform-modules-n3248x_1.1_amd64.deb
   creating: platform/x86_64-dellemc_n3248te_c3338-r0/
  inflating: platform/x86_64-dellemc_n3248te_c3338-r0/platform-modules-n3248te_1.1_amd64.deb
   creating: platform/x86_64-dell_s6100_c2538-r0/
  inflating: platform/x86_64-dell_s6100_c2538-r0/platform-modules-s6100_1.1_amd64.deb
   creating: platform/x86_64-dellemc_z9100_c2538-r0/
  inflating: platform/x86_64-dellemc_z9100_c2538-r0/platform-modules-z9100_1.1_amd64.deb
   creating: platform/x86_64-dell_z9100_c2538-r0/
  inflating: platform/x86_64-dell_z9100_c2538-r0/platform-modules-z9100_1.1_amd64.deb
   creating: platform/x86_64-dellemc_s5296f_c3538-r0/
  inflating: platform/x86_64-dellemc_s5296f_c3538-r0/platform-modules-s5296f_1.1_amd64.deb
   creating: platform/x86_64-dellemc_s5248f_c3538-r0/
  inflating: platform/x86_64-dellemc_s5248f_c3538-r0/platform-modules-s5248f_1.1_amd64.deb
   creating: platform/x86_64-dellemc_s5232f_c3538-r0/
  inflating: platform/x86_64-dellemc_s5232f_c3538-r0/platform-modules-s5232f_1.1_amd64.deb
   creating: platform/x86_64-dellemc_s5212f_c3538-r0/
  inflating: platform/x86_64-dellemc_s5212f_c3538-r0/platform-modules-s5212f_1.1_amd64.deb
   creating: platform/x86_64-dellemc_z9264f_c3538-r0/
  inflating: platform/x86_64-dellemc_z9264f_c3538-r0/platform-modules-z9264f_1.1_amd64.deb
   creating: platform/x86_64-dellemc_z9332f_d1508-r0/
  inflating: platform/x86_64-dellemc_z9332f_d1508-r0/platform-modules-z9332f_1.1_amd64.deb
   creating: platform/x86_64-dell_s6000_s1220-r0/
  inflating: platform/x86_64-dell_s6000_s1220-r0/platform-modules-s6000_1.1_amd64.deb
  inflating: platform/firsttime
   creating: platform/x86_64-grub/
  inflating: platform/x86_64-grub/grub-pc-bin_2.06-3~deb11u6_amd64.deb
   creating: installer-migration-hooks/
  inflating: installer-migration-hooks/08-config-profile-backup
  inflating: installer-migration-hooks/03-tpcm-version
  inflating: installer-migration-hooks/02-kernel-bootarg-pre
  inflating: installer-migration-hooks/01-local-users-pre
  inflating: installer-migration-hooks/01-kdump-pre
  inflating: installer-migration-hooks/01-dir-preservation
  inflating: installer-migration-hooks/00-cert-migrate
  inflating: sonic_version.yml
  inflating: db_migrator.py
  
```