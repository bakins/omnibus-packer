# OmniOS Packer template

Creates a vagrant box for OmniOS.

Run using `packer build template.json`

Notes:

 * A single ZFS pool (rpool) is created for the entire disk
 * The omniti-ms publisher is added by default
 * The VM is set to have 1024MB of RAM and a 40GB drive

Forked from the "official" OmniOS template from http://omnios.omniti.com/wiki.php/VagrantBaseboxes and based heavily on m/psi/packer-omnios


