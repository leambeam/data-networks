# A template repository for Data Networks course exercise documentation

Please write your documentation the following markdowns created as templates under the `/documentation/` -folder.

- [E01.md](/documentation/E01.md)
- [E02.md](/documentation/E02.md)
- [E03.md](/documentation/E03.md)
- [E04.md](/documentation/E04.md)
- [E05.md](/documentation/E05.md)
- [E06.md](/documentation/E06.md)
- [E07.md](/documentation/E07.md)
- [E08.md](/documentation/E08.md)
- [E09.md](/documentation/E09.md)
- [E10.md](/documentation/E10.md)
- [E11.md](/documentation/E11.md)
- [E12.md](/documentation/E12.md)
- [E13.md](/documentation/E13.md)
- [E14.md](/documentation/E14.md)
- [E15.md](/documentation/E15.md)
- [E16.md](/documentation/E16.md)
- [E17.md](/documentation/E17.md)

If you have additional material (pictures, topologies), please save them in the repository to the correct folder e.g. `/documentation/E01/jamk.png`

## Example markdown

### Plain text

Name: Grigory
Student number: AB0229
Student group: TIC21S1

### Image

This is a reference to an image

![](/documentation/E01/jamk.png)

### Configuration example

Either as a file

- [switch.cfg](/documentation/switch.cfg)

Or as a blockquote/snippet

```
EXOS-VM.1 # show configuration
#
# Module devmgr configuration.
#
configure snmp sysContact "https://www.extremenetworks.com/support/"
configure sys-recovery-level switch reset

#
# Module vlan configuration.
#
configure vlan default delete ports all
configure vr VR-Default delete ports 1-2
configure vr VR-Default add ports 1-2
```