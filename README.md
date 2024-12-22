# Netgen-installation-

## paste the commands one by one  

 ```
git clone https://github.com/RTimothyEdwards/netgen
 ```
```
cd netgen
```
```
./configure
```
```
make
```
```
make install
```

## for running netgen use following cmd in same dir but 
- __the file should be  .cir__
```
netgen -batch lvs <file _from_magic>.cir <file_from_xschem>.cir /usr/local/share/pdk/sky130A/libs.tech/netgen/sky130A_setup.tcl
```
