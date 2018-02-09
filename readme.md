

# D.R.A.K.E.
### Design Resources Assets Kits & Elements

* A graphic design repository for [CIRDLES](https://cirdles.org) projects.*

Logos and the style guidelines for those logos can be found in the directory [*logos/*](https://github.com/CIRDLES/DRAKE/tree/master/logos)

Assets and graphics for presentations can be found in the directory [*assets/*](https://github.com/CIRDLES/DRAKE/tree/master/assets)

Files relating to the UI can be found in the directory
[*ui/*](https://github.com/CIRDLES/DRAKE/tree/master/ui)

Files relating to physical designs ( hats, stickers, rack cards,  etc ) can be found in the directory [*goods/*](https://github.com/CIRDLES/DRAKE/tree/master/goods)



### Naming Conventions for Logos
All logos, except for ET_Redux and SESAR, have four different logos. Each type of logo is in three different file formats. All file format and logo types have the dimensions 300px x 300px

The naming convention for each logo type is defined by the following regex expression
``` regex
project_name + logo_type +  \. + file_extension  
```

The four logo types are:
* Main logos = ''
* Logos without a hexagonal background = 'SansHex'
* Logos without the name of the project = 'SansText'
* Logos without a hexagonal background nor project name 'SansHexText'

Each logo type is in the following formats:
* Portable Network Graphics = png
* Scalable Vector Graphics = svg
* Icon = ico

#### Example
If you had a logo for _project_ Ipsum _without hexagon_ as a png file then the file will be called
```
IpsumSansHex.png
```
