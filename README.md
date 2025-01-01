# Virtual Machine Manager

 
Blazing fast VM manager, that just works.

<p align="center" width="100%">
    <img width="270px" src="https://github.com/j0shua-daniel/images/blob/main/favcon.png?raw=true"> 
</p>

[Website](https://jr-om-cs-try.trycloudflare.com/) & [Wiki](https://jr-om-cs-try.trycloudflare.com/wiki/)

## Install:

Run `alias "sudo"="doas"` in your terminal if you use `doas`. 

[Install & Setup VM packages](https://jr-om-cs-try.trycloudflare.com/wiki/#install-vm-packages)

```
git clone https://github.com/j0shua-daniel/vm-mgr
cd vm-mgr
chmod +x setup
./setup
```

## Usage:

```
vm-mgr
```
You will see this: 
```
1) Start a VM
2) Create a VM
3) Delete a VM
4) Help
5) Quit
Option:
```
Type "2" to create your first vm!

## Compaired to alternatives.

1. vm-mgr is more easy to use than just qemu.
2. vm-mgr allows set ram to be below 64MB unlike virt-manager & gnome-boxes.
3. vm-mgr allows cpu threads up to 255, while on others (bar qemu itself) you can only go up to what is on your pc.
4. vm-mgr is cli unlike virt-manager, gnome-boxes, virtualbox and cockpit.
5. vm-mgr is **planning** to have support for BSD unlike gnome-boxes.

## Todo:

- [ ] Add BSD support.
- [x] Make menus more clear.
- [x] Fix bugs.
- [ ] Bridge the network.
- [ ] Enable starting created vms without disks and only isos/imgs.
- [x] Add *.img support.

