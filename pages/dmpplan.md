---
title: Data Management Plan
layout: about
permalink: /dmpplan.html
---

# Data Management Plan

## Group 2 

## Project Description

This digital collection is focused on the topic of Native Americans in the contemporary state of Oregon and general Pacific Northwest region. The collection is themed around artworks created by Natives among various tribes in these areas. The goal is to show their creativity and cultural traditions in a way that reflects their voices and perspectives. The artwork presented comes from various media, from textiles to wooden sculptures and pencil sketches. The topic of Native Americans in Oregon was due to the personal connection some of our group members have to Native American communities out East. 

We chose to theme our collection around Native art as we felt that documentation of Native American history and their lives has been centered on the colonial documenters rather than the Native Americans being documented themselves. In many museum exhibits or history projects, Native Americans are often presented through the eyes of outsiders. We thought that collecting the objects of Native Americans directly centers the Native Americans themselves and let the objects they created speak for themselves. 

The objects collected in this project were found in various GLAMs, including: The Portland Art Museum, Hallie Ford Museum of Art, The Metropolitan Museum of Art, the Oregon Historical Society Museum, and the Oregon Historical Society Research Library. Each group member was responsible for documenting at least 4 objects. 

Our process for documenting an object included downloading the digital object after following relevant copyright standards, then documenting its DublinCore metadata elements into a Google Sheet within our group’s shared Google Drive folder. Once we all added the relevant metadata for the digital objects we curated, we exported the metadata Google Sheet into a CSV file. Then, using the CollectionBuilder template in GitHub sites, we uploaded our metadata and each of the objects to their relevant folders. Since we integrated into the CollectionBuilder structure, the site was built automatically from the uploaded data.

All project data and metadata are stored in CSV files within the GitHub repository, making them freely accessible online through version-controlled, openly available source files. 
Our collection has a couple of groups or audiences that could be interested in reusing our collection, those being Native Americans, researchers such as anthropologists or art historians, and anyone from the general public interested in these images. Our collection is a benefit to these groups as we have synthesized objects from different GLAMs which could act as the beginning to a bigger project collecting all artistic objects created by Native Americans in Oregon and the surrounding Pacific Northwest.


## Roles and Responsibilities

| Group Member | Role | Responsibilities |
|--------------|------|------------------|
| Quinn | Project Manager | Quinn was responsible for managing the Google Drive folder, leading and coordinating communication, and submitting all our group projects. Quinn was skilled at using Teams and facilitating communication between each of us.|
| David | Collection Development Manager | David made the final call about what would be included in the collection and led the research topic selection and scope definition. David was skilled at helping narrow our scope and making decisive, coherent calls about what to include.|
| Hunter | Object Preservation Manager | Hunter was responsible for overseeing the storage space and documents folder, establishing the collection's file naming standard, and ensuring backup copies are available. Hunter had great organizational skills which he utilized in the folder.|
| Anna | Metadata Manager | Anna was responsible for managing the spreadsheet and ensuring our metadata follows the Dublin Core and CollectionBuilder requirements. Anna had great attention to detail, ensuring all of the given requirements were met for the metadata.|
| Conner | Repository Manager | Conner was responsible for taking notes at our meetings, leading technical troubleshooting, and managed our GitHub repository. Conner had a great technical skillset that he shared with all of us.|

## Data

### Standards and formats

We have 24 objects, all of them are stored as jpg/jpeg files, and in total take up 12.6 mb of disk space.

### License

Our project is licensed under the MIT license as open-source software.

### Documentation and Metadata

Our metadata application profile can be found [here](/objects/group2map.pdf).

The metadata for each object is located in the data section of the website and is available on the GitHub repository. The data can be downloaded from either of these locations in CSV format. The definition for each metadata field is in the data dictionary at the end of this page and in the Metadata Application Profile provided earlier.

### File Naming Standard

All file names followed our naming standard:

1. Structure of Art 

Definition: The structure that the artwork takes on in form

- Choose from: Basket, Painting, Sculpture, Textile, Bag, Clothing, Drawing

- Examples:
  - basket_
  - painting_
  - sculpture_
  - textile_
  - bag_
  - clothing_
  - drawing_

2. Numbering

Definition: A number identifying the piece of art as unique from the others of the same type

- We will not include different angles of the art, so sequencing represents where it is in the collection (ie: sculpture_01_ is the first sculpture added)

- Examples (Not exclusive to these):
  - sculpture_01_
  - bag_01_
  - basket_01_
  - basket_02_
  - sculpture_02_
  - bag_02_

3. Location of Creation

Definition: Where the object was created in oregon as listed by the GLAM

- County/municipality name, city, area 

- Examples (Not exclusive to these): 
  - \_westernoregon\_
  - \_sauvieisland\_

4. Date

Definition: Date of creation of the object 

- Format: Year. 

- If ca./circa [year], use [year] only

- Example: 
  - _1900
  - _1850

An example of our file naming standard in practice: sculpture_01_sauvieisland_1830.jpg

### Storage and Backup

Our project is stored on a Google drive shared amongst our group. The code for the website is stored in a GitHub repository and hosted on GitHub sheets. We also have the GitHub repository cloned as a local git repository on a group member's computer.

### Data Sharing

As mentioned, the data is shared through the Github repository and the website. The data used for this project may be used freely under the MIT license, and the objects can be used with proper attribution to the source GLAM. We have given citations for our project so we recommend using those for documentation of the objects, should they be used in another project.

## Privacy and Security Considerations

Our CollectionBuilder site uses openly accessible materials, and because all items are stored in GitHub and displayed publicly online, we ensured that no sensitive personal information, restricted cultural materials, or copyrighted content without permission was included. Because none of our items have restricted access we determined our collection is appropriate for open online publication. As a security measure, all of our files are hosted through GitHub Pages, which provides controlled versioning and stable public access without exposing editable backend data.


### Period of Data Retention

Hunter Everton, the Object Preservation Manager, will check any issues raised or pull requests made after December 2025. If any of the objects are missing then please raise an issue or create a pull request on the GitHub repository. Hunter and Anna both have digital copies of objects on their computers as backup. 

## Licensing and Ethical Issues

For licensing, all of the objects we have collected and organized are either in the public domain, or, the GLAM did their own rights analysis on the object and found no known copyright restrictions. We encourage those who would like to use our objects to visit the GLAM's' website which we have cited. For ethical considerations we believe as a group that the objects should be cited according to MLA or some other guidelines even if the object is in the public domain. Moreover, another ethical consideration is that the objects were created by Native groups. We believe that the rightful owners of many of these objects are the actual tribe from which they originate. Re-patriation is a topic that we are continuing to expand our knowledge about, and our digital collection aims to shed light on Native art without claiming any sort of ownership over the art. 

## Data Dictionary
Our data dictionary mainly comes from CollectionBuilder's standard as provided to us by our instructor, Kate Thornhill. 

| Field | Definition |
|-------|------------|
| objectid | A unique string with no spaces or special characters that will be used as an ID in the website. Records without an objectid will not be displayed in the collection. Records with non-unique objectid will be overwritten. |
| title | A name given to the resource. |
| date | A point or period of time associated with an event in the lifecycle of the resource. |
| description | An account of the resource. |
| subject | The topic of the resource. |
| location | A geographic location to which the resource applies. |
| source | The source field designates a related source collection or resource from which the object is derived. This field is especially relevant for digitized archival collections. In such a situation, the name of the physical archival collection would be the input for this field. |
| identifier | An unambiguous reference to the resource within a given context. |
| type | Distinguishes between types of image, sound, text, etc. using a one- or two-value input. |
| format | The digital file format of the resource or media type. |
| rights | Information about rights held in and over the resource. |
| rightsstatement | A standardized rights statement, presented as a creativecommons.org URI or rightsstatements.org URI |
| display_template | Sets the template type used for the Item page and is used in logic to choose representations in other pages. If blank the object will default to a generic item page. |
| image_alt_text | An appropriate textual description of the image_small representation of the item. The alt text corresponds to the image_small (not necessarily the file at object_location). This value will be used as the “alt” value of the image element, which is important for accessibility. |
| address | The web address to the object in the GLAM. |
| cataloger | The group member that input the object's metadata, this was created by our group to monitor which objects were entered by which group member. |
| citation | A field that our group made to enter the MLA citation of the object. |
| filename | This is the digital object's filename, including the name itself as well as the object's file extension. For externally hosted items, this may be a full URL. |
| structure | A metadata field our group created in order to have a more general category for objects to fit into. Also created for our file naming standard to be consistent and easier for group members to enter. |
