# AryaBootstrap
### AryaBootstrap is a bootstrap with dual layout align support and, used for LTR and RTL web design. (bootstrap rtl 4.5.3)
Based on Bootstrap Ver 4.5.3

> [NuGet Package](https://www.nuget.org/packages/AryaBootstrap/)

![AryaBootstrap | آریا بوت استرپ](images/AryaBootstrap.jpg)

### Build responsive, mobile-first projects on the web with the world’s most popular front-end component library.

AryaBootstrap is an open source toolkit for developing with HTML, CSS, and JS. Quickly prototype your ideas or build your entire app with our templates, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery. This Version of AryaBootstrap is based on Bootstrap Ver 4.5.3 and all bootstrap feature is provided.

### Installation

Installation AryaBootstrap is as simple as Bootstrap.

#### 1. First of all, Download the AryaBootstrap، [GitHub](http://github.com/mRizvandi/AryaBootstrap) or [NuGet](https://www.nuget.org/packages/AryaBootstrap/).

Extract the files and folders, copy Css and Js folders to your project.

#### 2. Add Css file to your pages

Add Css file link to your page like the below HTML code:

```
<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css" /> 
```

#### 3. Add Js files to your page

Some bootstrap components need bootstrap.js for doing well on the page. and they used jQuery library. so you have to add jQuery (slim version is enuogh) file before add bootstrap js file.

Bootstrap used popper.js to provide grid system and you have to add popper.js after jQuery file.

At the end, you have to add Bootstrap.js

```
<script type="text/javascript" src="js/jquery.slim.min.js"></script>
<script type="text/javascript" src="js/popper.min.js"></script>
<script type="text/javascript" src="js/bootstrap.min.js"></script>
```

Also, you can use the bootstrap CDN files insted use of downloaded files:

```
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js" integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s" crossorigin="anonymous"></script>
```

#### 4. Latest and Important Step

Add "dir" property to your "html" tag. use **dir="rtl"** for RTL layout and **dir="ltr"** for LTR layout.

```
<html dir="rtl">
```

**Everything is Done!** run your project and enjoy the rtl bootstrap.

Check the AryaBootstrap Website, there are some sample and articles (Persian Version).

### [AryaBootstrap Website](http://abs.aryavandidad.com)


### Old and Other Version
[AryaBootstrap 4.4.1](https://github.com/mRizvandi/AryaBootstrap-4.4.1)

[AryaBootstrap 4.3.1](https://github.com/mRizvandi/AryaBootstrap-4.3.1)


#### Persian Version is also avilable at [Persian ReadMe](https://github.com/mRizvandi/AryaBootstrap/blob/master/README.md)
