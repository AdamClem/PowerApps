# PowerApps - 2nd Explosive Ordnance Disposal Company

This space showcases two PowerApps that I've built for 2nd Explosive Ordnance Disposal Company. The main function of this PowerApp is to catalog ordnance items that have explosive hazards removed and are stored in our library. There are several explosive safety regulations that must be followed. Each year we have inspections and spot checks to ensure compliance.

## Introduction
Both of these PowerApps are built using a model-driven design. These two PowerApps have saved dozens of hours for each item that is processed by streamlining the process of inducting a new item, modifying details, and/or uploading an attachment.

## Ordnance Library
The Ordnance Library is fed by two different SharePoint Online lists. These lists are split into ordnance items transferred outside of our organization and those that are retained within our building. This also helps alleviate the limitation of PowerApps maximum limit of 2000 rows.

### Features
**Ordnance Item Lookup**: Allows a user to find an ordnance item within our building. It can be searched by it's nomenclature, serial number, or location. Each of our shelves are labeled so that items on specific shelves can be found. This is vital for inspection as the inspector will select a shelf and pick several items and inspect the documentation.

**Modify Details**: Users can upload photos into the PowerApp that are then posted into SharePoint and serve as the thumbnail. If a user is looking via SharePoint online instead of needing to memorize each item by it's nomenclature a thumbnail will greatly help in finding the item.

**Generate Inert Certification**: The biggest time drain in adding an ordnance item is completing the inert certification paperwork. This requires multiple fields and two signatures. The application will generate an inert cert that is printed and can be wet signed or with a digital signature.
