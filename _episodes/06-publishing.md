---
title: "Publishing"
teaching: 30
exercises: 0
questions:
- "How and where do I publish my library dataset?"
objectives:
- "Learn the options you have for repositories."
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---
## Local Civic Data Repository

We suggest that the best first option for publishing public library datasets is the local civic data repository for your area. This might be a city, county, or state data portal. Why? Discoverability! If those seeking data about government and civic agancies can find everything from one area in one place, they will turn to that repository for their local data needs. 

The first step is to find out if your city, county, or state (start hyperlocal and work your way out to larger areas) has a civic data repository. What do local civic data repositories look like? Here are a few examples:

- [City of Seattle Open Data Repository](https://data.seattle.gov/)
- [Sauk County Open Data Repository](https://data-saukgis.opendata.arcgis.com/)
- [Maryland's Open Data Portal](https://opendata.maryland.gov/)
- [Western Pennsylvania Regional Data Center](http://www.wprdc.org/)

The City of Seattle and Maryland's repositories are built with Socrata software, Sauk County is built with ArcGIS software, and Western Pennsylvania Regional is built with CKAN software. We analyzed over 130 civic data portals and found that ArcGIS and Socrata are the most common software platforms used for civic data portals. We found smaller numbers of portals used software including: CKAN, JKAN, DKAN, Junar, OpenDataSoft, and custom software. We won't be providing instructions for how to publish on each of these specific software platforms, however we will provide advice on how to get started regardless of platform and will provide some examples of uploading data to a Socrata platform.

## Socrata Example

*Thank you to Kaitlin Throgmorton for walking us through the process of adding a dataset to the Washington State data portal hosted on the Socrata platform.*

Below we will walk you through some of the process (as of June 2020) of adding metadata to datasets on the Socrata platform. This is not meant as a tutorial because portions of this process and screen captures may change, but it will give you some insight into the publishing process on a Socrata platform. 

Sign in to the Socrata platform:

![Screenshot of Socrata Sign In Page](https://raw.githubusercontent.com/OpenDataLiteracy/Prepare_Publish_Library_Data/gh-pages/assets/img/SocrataSignIn.png)

You will either be given permission to upload datasets yourself or you will provide datasets to the platform administrator who will give you access to the datasets for creating/revising metadata. If you already have a dataset available to your for modification you will see something like this:

![Screenshot of Socrata Datasets Profile Page](https://raw.githubusercontent.com/OpenDataLiteracy/Prepare_Publish_Library_Data/gh-pages/assets/img/SocrataDatasetsProfile.png)

And you can click on the dataset in the list that you want to modify, bringing you to the dataset page:

![Screenshot of a Dataset Page](https://raw.githubusercontent.com/OpenDataLiteracy/Prepare_Publish_Library_Data/gh-pages/assets/img/SocrataDatasetEdit.png)

If you look closely and ignore the white box covering a portion of the screen, you can see that there is an "Edit" button on this page allowing you to gain access to the various data actions: Add Data, Review & Configure Data, Edit Dataset Metadata, Edit Column Metadata. 

![Screenshot of a Metadata Management Page](https://raw.githubusercontent.com/OpenDataLiteracy/Prepare_Publish_Library_Data/gh-pages/assets/img/SocrataDataActions.png)

In this example we'll show you what it looks like to edit the dataset metadata and the column metadata. We clicked on "Edit Dataset Metadata." Because we choose "Edit Dataset Metadata" we are now on the page for editing those metadata elements. If you look to the left of the screenshot, you'll see that it's easy to switch to the editing of column metadata by clicking "Column Descriptions." But let's first look at Dataset Metadata. This first screenshot show's the simple text box entry for dataset title and description. In this case, the description is optional, but we highly recommend populating this field. Any time you can add description ot oyour dataset you should. Next you can add a description of the rows in the tabular dataset. If you remember from the tidy data module, a row should be an observation of the data. Here is where you describe what that observation is. (For example, it could be an individual library, or an individual piece of library material, or a de-identified patron.)

![Screenshot of Dataset Metadata Management Page for Title and Row](https://raw.githubusercontent.com/OpenDataLiteracy/Prepare_Publish_Library_Data/gh-pages/assets/img/SocrataManageMetadataTitleRow.png)

Next you can choose from categories and tags. In this example, the adminstrator for the portal specifically requests that library data be categorized as "Culture and Community" and the tags are free form (i.e. there is no controlled vacabularly for tagging). You will need to check on the categorization and tagging specifics of the portal you are using.

![Screenshot of Dataset Metadata Management Page for Categories and Tags](https://raw.githubusercontent.com/OpenDataLiteracy/Prepare_Publish_Library_Data/gh-pages/assets/img/SocrataManageMetadataCatTags.png)

The follwoing section for licensing and attribution will be specific to your organization and the option available on your portal.

![Screenshot of Dataset Metadata Management Page for Licensing and Attribution](https://raw.githubusercontent.com/OpenDataLiteracy/Prepare_Publish_Library_Data/gh-pages/assets/img/SocrataManageMetadataLicense.png)

Next you will want to include contact information for the dataset. This will again depend on the arrangements you make with the portal administrator and your organization. In the example case, the contact information will be to the portal administrator, but your situation may be different. Attachments can include a variety of different files. In this example, you will see a little later, the data dictionary and a decoding file for the "item type" codes were added as attachments (both are .csv files).

![Screenshot of Dataset Metadata Management Page for Contact Information and Attachments](https://raw.githubusercontent.com/OpenDataLiteracy/Prepare_Publish_Library_Data/gh-pages/assets/img/SocrataManageMetadataContactAttach.png)

There is a notes section in which you can add any details you weren't able to include elsewhere. This dataset includes notes on what the attachments are and on finding more documentation in a Github repository.

![Screenshot of Dataset Metadata Management Page for Contact Information and Attachments](https://raw.githubusercontent.com/OpenDataLiteracy/Prepare_Publish_Library_Data/gh-pages/assets/img/SocrataManageMetadataNotes.png)





## Alternatives

{% include links.md %}

