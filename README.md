# bd3m to glTF Converter
This script converts **bd3m** ( 3D Tiles ) files into **glTF** format, supporting the containing **.glb** &amp; **.bin** if available.

This works with the help of the [pygltflib python module](https://gitlab.com/Epic_Wink/pygltflib) 

#### Requirements :
```
pip install pygltflib
```

#### Usage :
```
usage: b3dm2glTF.py [-h] [-i INPUT] [-o OUTPUT]

options:
  -h, --help            show this help message and exit
  -i INPUT, --input INPUT
                        Input file or folder name
  -o OUTPUT, --output OUTPUT
                        Output file or folder name
```
#### Results : 

This script will output the desired **.gltf** file and a **.json** file that contains the b3dm header and truncates it up until the start of the glTF header, with that the **.glb** and **.bin** if available on the 3D Tiles file.

![image](https://github.com/SofianeHamlaoui/bd3m2glTF/assets/16967174/6b1ab0ed-c3a7-430f-8b0b-6f5845adfd86)
