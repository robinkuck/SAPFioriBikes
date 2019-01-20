# SAPFioriBikes

This project showcases some of the [Map Floorplan](https://experience.sap.com/fiori-design-ios/article/map/) features of the 3.0 release of the [SAP Fiori iOS SDK](https://developer.apple.com/sap/).  Inspired by Apple's [TANDm](https://developer.apple.com/documentation/mapkit/mkannotationview/decluttering_a_map_with_mapkit_annotation_clustering) application from WWDC 2017 and the installation of [Ford GoBike](https://www.fordgobike.com/) across the bay area, `SAPFioriBikes` clusters bike stations and shows the number of bikes and eBikes at each location using the SAPFiori Map Floorplan implementation. With this application I hope I can finally track down one of the [Ford GoBike Plus](https://www.fordgobike.com/plus)!

## SAPFioriBikes iPhone

![SAPFioriBikes iPhone](./ReadMeImages/No_Legend_iPhone.png?raw=true)

## SAPFioriBikes iPhone Legend

![SAPFioriBikes iPhone Legend](./ReadMeImages/Show_Legend_iPhone.png?raw=true)

## SAPFioriBikes iPad
![SAPFioriBikes iPad](./ReadMeImages/No_Legend_iPad.png?raw=true)

## SAPFioriBikes iPad Legend

![SAPFioriBikes iPad Legend](./ReadMeImages/Show_Legend_iPad.png?raw=true)

## Getting Started

1. Download the [SAP Cloud Platform SDK for iOS](https://developers.sap.com/topics/cloud-platform-sdk-for-ios.html#details) to get necessary frameworks locally.

2. Clone the repository.

3. Add the `SAPFiori.framework` and `SAPCommon.framework` to the `Embedded Binaries` and `Linked Frameworks and Libraries`.

4. Build and Run 🚴‍

5. Read my walkthrough
      1. [FUIMapFloorplan: Getting Started](https://github.wdf.sap.corp/i860364/SAPFioriBikes/blob/master/SAPFioriBikesBlog.md)
      2. [FUIMapFloorplan: DetailPanel](https://github.wdf.sap.corp/i860364/SAPFioriBikes/blob/master/SAPFioriBikesBlogDetailPanel.md)

[//]: # (Needs external blog post link)

### Prerequisites

* Xcode 10.0+
* SAPFiori
* SAPCommon

## API References

* [SAPFiori Reference](https://help.sap.com/doc/978e4f6c968c4cc5a30f9d324aa4b1d7/3.0/en-US/Documents/Frameworks/SAPFiori/index.html)

## Built With

* [Ford GoBike System Data](https://www.fordgobike.com/system-data)
* [StellarJay](https://github.com/sstadelman/stellarjay)
* [Uber Common](https://github.com/uber-common/deck.gl-data/blob/master/website/bart.geo.json)

## Authors

* **Alex Takahashi** - *Initial work* - [alextakahashi](https://github.com/alextakahashi)

## Acknowledgments

* [TANDm](https://developer.apple.com/documentation/mapkit/mkannotationview/decluttering_a_map_with_mapkit_annotation_clustering) - Cluster Annotation Inspiration
* [README-Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
