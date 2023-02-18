
# <center> **ECASLab at DKRZ**  </center>


```{figure} images/ecas_logo.png
:width: 100px
:figclass: margin
```
```{figure} images/dkrz.png
:width: 100px
:figclass: margin
```
The **E**NES **C**limate **A**nalytics **S**ervice instance at DKRZ. \
for the impatiant: go to the [](getstarted.md) introduction. \
an overview of all ENES ECAS instances is provided at the [IS-ENES portal](https://is.enes.org/sdm-climate-analytics-data/)

## What is ECASLab 

ECASLab provides services to access and analyse climate model data at the data centers where the data is stored. It thus enabled data proximate data analysis without the need to move large amounts of data. 
```{image} images/ecas-vis.png
:alt: fishy
:class: bg-primary mb-1
:width: 300px
:align: center
```
## The ECASLab data pool
```{figure} images/databases.png
:width: 100px
:figclass: margin
```
DKRZ provides the largest online accessible climate model data pool in Europe. Data collections provided include CMIP5, CMIP6 and CORDEX as well as other important climate model data sets (e.g. ERA).


DKRZ also provides associated data catalogs which are directly exploitable within e.g. the jupyterhub instance. 


## The Jupyterhub interface

```{figure} images/jupyter.png
:width: 120px
:figclass: margin
```

The Jupyterhub instance at DKRZ allows you to use different pre-defined computational environments (jupyter kernels) with all core climate data analytics libraries integrated. It is also possible to activate your own kernels. 
The Jupyterhub instance has direct access to the data pool and supports catalog based data search and access. 

## The Web Processing Service (WPS) interface

```{figure} images/wps.png
:width: 120px
:figclass: margin
```

A Web Processing Service supports data access to the data pool involving oftenly needed pre-processing (e.g. data sub-selection, data regridding). 
This service can be used from the juypterhub interface. 
The WPS interface also provides data to the Copernicus data store where a subset of the data pool is accessible as well. 

## Cloud based data sharing 

```{figure} images/cloud.png
:width: 120px
:figclass: margin
```

To share data the ECAS instance at DKRZ can exploit a SWIFT cloud storage.
Also some data sub-collections are directly hosted on the cloud and can be directly exploited remotely (e.g. from the EOSC D4Science VRE). 


For more details please have a look at: 

```{tableofcontents}
```
