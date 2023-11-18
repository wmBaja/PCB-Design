# PCB-Design

## Introduction
The **PCB-Design** and **[PCB-Parts](https://github.com/wmBaja/PCB-Parts)** repositories contain Pack Motorsports Baja's current and previous PCB projects. The two repositories are designed to be used together.

The **PCB-Design** repository should contain folders for each current project. The projects should contain KiCAD project files/folders, but NOT libraries or part files.

The **PCB-Parts** repository should contain any part or library files for the projects in PCB-Design. These part files can include KiCAD symbols or footprints, 3D models, datasheets, 

## Folder Structure
The PCB-Design and PCB-Parts repositories should be organized in a parent folder as follows:

```mermaid
    graph TD;
        A[Parent Directory]---B[PCB-Design];
        A---C[PCB-Parts];
        B---D[Project1];
        B---E[Project2];
        C---F[Project1Parts]
        C---G[Project2Parts]

        classDef default fill:white, stroke:black, stroke-width:2px;
        style B color:blue
        style C color:blue

        click B "https://github.com/wmBaja/PCB-Design" _blank;
        click C "https://github.com/wmBaja/PCB-Parts" _blank;

```

## OBD Baja 2.0 3D Model
<iframe src="https://collaborate.shapr3d.com/v/RQxqZTwWx0Oz6eKVTlwwQ" title="Shapr3D Webviewer" width="640" height="640" frameborder="0" allow="web-share; xr-spatial-tracking" loading="lazy" scrolling="no" referrerpolicy="origin-when-cross-origin" allowfullscreen></iframe>