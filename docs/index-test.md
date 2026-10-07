---
title: Metadata Guidelines
nav_enabled: true
nav_order: 2
permalink: /docs/first-page
---
# Overview
The Tulane University Libraries Digital Collections Metadata Guidelines (hereafter TUDC Metadata Guidelines or Metadata Guidelines) provides detailed instructions on how to create metadata for digital objects that will be ingested into the Tulane University Libraries Digital Collections. Adherence to the Metadata Guidelines is necessary to maintain and promote consistency across digital collections. Following these guidelines will improve the discoverability of digital objects, ensure a baseline of metadata quality, and increase interoperability both within the Digital Collections and with other digital libraries. The TUDC Metadata Guidelines is the most up-to-date document that outlines the standards and best practices used for metadata creation. This document updates the information previously expressed in the Tulane University Digital Library Metadata Guidelines. 

The Tulane University Libraries Digital Collections uses Metadata Object Description Schema (MODS) for its digital objects’ metadata, specifically MODS 3.7. Local rules and preferences adhere to guidelines given in the official MODS documentation whenever possible. Additional guidance on metadata creation is pulled from standards such as Resource Description and Access (RDA) and Describing Archives: A Content Standard (DACS). Due to technical limitations and local needs, some deviations from these standards do occur; these divergences are noted when applicable in the Metadata Guidelines. 

## Obligation Levels and Categories

There are a number of metadata fields listed in these guidelines, though not all are expected to appear in every metadata record. The circumstances in which to use each field are identified by the field’s obligation level, which will either be 'Mandatory', 'Mandatory if applicable', 'Recommended', or 'Recommended if applicable'. Explanations of the different obligations are provided below.

Mandatory
: field must be present in an item’s metadata record. All items, regardless of their properties, are required to use this field. All items, for example, must have a title.

Mandatory if applicable
: field must be present in an item’s metadata record if certain characteristics are met. Not all items will have a known creator, for example, but if an item’s creator has been identified, that creator’s name is required to be recorded in the metadata; if the creator is not known, that field is not required to be present in the record.

Recommended
: field is not required to be present in an item's metadata record, but its inclusion would be beneficial to the discoverability, descriptiveness, or integrity of the metadata record. 

Recommended if applicable
: field is not required to be present in an item's metadata record, but, when certain characteristics are met, its inclusion would be beneficial to the discoverability, descriptiveness, or integrity of the metadata record.

Building on the above obligation levels, metadata fields are further categorized into one of three groups: Core Metadata, Core Conditional Metadata, or Core Expanded Metadata. The main areas of the TUDC Metadata Guidelines are organized around these groupings, and explanations for each are supplied below. 

Core Metadata
: refers to all mandatory metadata fields.  

Core Conditional Metadata
: refers to all mandatory if applicable metadata fields. 

Core Expanded Metadata
: refers to all recommended and recommended if applicable metadata fields.

## Common Abbreviations
MODS
: Metadata Object Description Schema. This is the metadata schema used by the Tulane University Digital Library, Tulane Inside and Out, and Scholarship at Tulane sections of Tulane University Digital Collections. The official MODS website, maintained by the Library of Congress, can be accessed through this link.

XML
: eXtensible Markup Language. MODS metadata is expressed using this markup language. Contributors will almost never have to work directly with XML records.

TUDC
: Tulane University Libraries Digital Collections. This is an online, freely accessible resource hosted by the Tulane University Libraries that is home to distinctive content from the Tulane University community. TUDC contains seven separate sections that each hold different types of material. However, when TUDC is mentioned in the TUDC Metadata Guidelines, it refers only to three specific sections: Tulane University Digital Library, Tulane Inside and Out, and Scholarship at Tulane. The TUDC homepage can be accessed through this link. 

TUL
: Tulane University Libraries. This is the parent organization that TUDC belongs to. TUL refers to all divisions, departments, and units in the Libraries system and not just those associated with TUDC.

AD
: Alma Digital. This, in conjunction with Primo VE, is the platform used to provide public access to TUDC. AD and Primo VE have various limitations on what metadata can be displayed and how, with slight differences between them. When AD is mentioned in the TUDC Metadata Guidelines, it refers to the metadata display for both AD and Primo VE; it will be explicitly noted when a display configuration only applies to one platform. 
