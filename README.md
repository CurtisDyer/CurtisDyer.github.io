# Dell CLI

The Dell CLI is similar to Cisco's IOS.

## VLAN Configuration

### Creating VLANs

Enter VLAN database

    SW01> en
    SW01# config
    SW01(config)# vlan database
    SW01(config-vlan)# vlan 20 name "Printers"
