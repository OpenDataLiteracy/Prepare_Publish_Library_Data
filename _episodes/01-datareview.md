---
title: "Review and Data Identification"
teaching: 120
exercises: 0
questions:
- "What are Data, Data Types, Data Formats & Structures? What library-related data can you publish?"
objectives:
- "Review of intorductory data concepts and ideas for identifying library data to publish."
keypoints:
- "Definitions"
- "Library Datasets"
---
## Working Definitions

Before we begin diving into the content, we will review key terms and their definitions:

**Data**: Data are various types of digital objects playing the role of evidence. Type and role distinctions have to do with the relational nature of data. A type is rigid (such as a file format) and a role is fluid (it can change given a context). A simple example will help make this clear: I am a person. This is a type. Regardless of any external circumstances I will remain a person. I am also a professor. This is a role that I play. I might, depending on the success of my tenure case, not be a professor in the future. This is simply a professional title that I have for a small amount of time. Data have similar rigid and fluid properties - A tabular dataset will have a type of structure (rows, columns, and values). Unless we take some purposeful action to transform this data it will remain tabular as a type. But, this tabular data might be evidence of some real world phenmena - it might be set of species occurrence records, the preciptation and temperature of a particular place, etc. This evidential role can shift and change depending on who is using the data, and for what purpose.

**FAIR Data**: An emerging shorthand description for open research data - that is applicable to any sector - is the concept of F.A.I.R. FAIR data should be Findable, Accessible, Interoperable, and Reusable. This is a helpful reminder for the steps needed to make data truly accessible over the long term. 

**Data curation**: Data curation is the active and ongoing management of data throughout a lifecycle of use, including its reuse in unanticipated contexts. This definition emphasizes that curation is not one narrow set of activities, but is an ongoing *process* that takes into account both material aspects of data, as well as the surrounding community of users that employ different practices while interacting with data and information infrastructures. 

**Metadata**: Metadata is most simply a set of standardized attribute-value pairs that provide contextual information about an object or artifact. Metadata, at an abstract level, has some features which are helpful for unpacking and making sense of the ways that descriptive, technical, and administrative information become useful for a digital object playing the role of evidence. Metadata can and often does include the following:  

- Classes describe concepts that are related to a domain. A domain here means something like an area of application. For example a class of wines would include (or entail) the properties and instances for any wine. Classes are made up of instances, properties, and values (or attributes of an instance). 
- Sub-classes refine a class. A sub-class can be a more specific example of a class. Returning to our wine example, a sub-class of wines might be red, white, or rosé. Another sub-class could divide wines into sparkling or non-sparkling. The point is that a sub-class provides some way to divide or simplify the domain that a class is describing. 
- Instances are observations or concrete examples of a class or sub-class. For example, in an ontology or metadata scheme describing mammals my dog `Yael` is an instance of the sub-class Saluki. A Saluki is an instance of the sub-class Canine, which is an instance of a class of Mammals. A class or sub-class instance also has attributes or properties that define it is a member of that class or sub-class.
- Attributes are defining features of a class or sub-class, and refer to instances. An instance is a member of a class if it has all of the attributes of that class. For example, a Mammal has certain features (reproductive organs, respiratory system, etc) that define its base or necessary attributes for class membership. Canines as a sub-class have a more specific set of attributes that define membership in that sub-class. 
- Relations are the ways that we relate different instances and classes to one another. An instance or a class can be related in one or many ways. 

**Structured Metadata** Is quite literally a structure of attribute and value pairs that are defined by a scheme. Most often, structured metadata is encoded in a machine readable format like XML or JSON. Crucially, structured metadata is compliant with and adheres to a standard that has defined attributes - such as Dublin Core, EML, DDI.

**Metadata Schemas** define attributes (e.g. what do you mean by “creator” in ecology?); Suggests controls of values (e.g. dates = MM-DD-YYYY); Defines requirements for being “well-formed” (e.g. what fields are required for an implementation of the standard); and, Provide example use cases that are satisfied by the standard.

Structured metadata is, typically, differentiated by its documentation role.

- Descriptive Metadata: Tells us about objects, their creation, and the context in which they were created (e.g. Title, Author, Date)
- Technical Metadata: Tells us about the context of the data collection (e.g. the Instrument, Computer, Algorithm, or some other tool that was used in the processing or collection of the data)
- Administrative Metadata: Tells us about the management of that data (e.g. Rights statements, Licenses, Copyrights, Institutions charged with preservation, etc.)

**Unstructured Metadata** is meant to provide contextual information that is Human Readable. Unstructured metadata often takes the form of contextual information that records and makes clear how data were generated, how data were coded by creators, and relevant concerns that should be acknowledged in reusing these digital objects. Unstructured metadata includes things like codebooks, readme files, or even an informal data dictionary. 

A further important distinction we make about metadata is that it can be applied to both individual items, or collections or groups of related items. We refer to this as a distinction between **Item and Collection level metadata**.

**Expressivity vs Tractability** All knowledge organization activities are a tradeoff between how expressive we make information, and how tractable it is to manage that information. The more expressive we make our metadata, the less tractable it is in terms of generating, managing, and computing for reuse. Inversely, if we optimize our documentation for tractability we sacrifice some of the power in expressing information about attributes that define class membership. The challenge of all knowledge representation and organization activities - including metadata and documentation for data curation - is balancing expressivity and tractability.

**Normalization** literally means making data conform to a normal schema. Practically, normalization includes the activities needed for transforming data structures, organizing variables (columns) and observations (rows), and editing data values so that they are consistent, interpretable, and match best practices in a field.

**Data Quality**: From the ISO 8000 definition we assume data quality are "...the degree to which a set of characteristics of data fulfills stated requirements.” In simpler terms data quality is the degree to which a set of data or metadata are fit for use. Examples of data quality characteristics include completeness, validity, accuracy, consistency, availability and timeliness.

## Resources

Review Data 101: What is Data [slides](https://docs.google.com/presentation/d/1gXqJ7vZ_44LGrk5ZHtvpl2zGBrudn9PHYzrmGwPQk1M/edit#slide=id.p) from the [Western Pennsylvania Regional Data Center](http://www.wprdc.org/) and the [Carnegie Library of Pittsburgh](https://www.carnegielibrary.org/).

## Data Types

## Data Formats and Structures

## Identifying Library Datasets

Does your open data project match community needs? A [quiz](https://docs.google.com/forms/d/e/1FAIpQLSfcjXVLqdMQp3-3LfwBRDt9Dou7nBCkRzaaX3xnFRgWg96yuw/viewform) for finding a community-driven focus from the Sunlight Foundation.

### Identifying Open Data to Publish
*Adapted with permission from a document prepared by Kathleen Sullivan, open data literacy consultant, Washington State Library*

This following text synthesizes recommendations for getting started with open government data publishing. The recommendations reflect reliable, commonly recommended sources (listed at the end), as well as interviews conducted by Kathleen Sullivan with other open data portal creators and hosts.

**The Mantras**  
*People, issues, data*  
As Sunlight Foundation hammers home in its “Does your open data project match community needs?” [quiz](https://docs.google.com/forms/d/e/1FAIpQLSfcjXVLqdMQp3-3LfwBRDt9Dou7nBCkRzaaX3xnFRgWg96yuw/viewform), the data you choose to publish should connect to issues that people care about. Begin your publishing process by identifying the key people, the key issues, and the available data.

**Keep it Simple**  
Many guides have some version of this advice, along with suggestions to do things in small, manageable batches and avoid perfectionism. Here’s Open Data Handbook’s take:
>**Keep it simple**. Start out small, simple and fast. There is no requirement that every dataset must be made open right now. Starting out by opening up just one dataset, or even one part of a large dataset, is fine – of course, the more datasets you can open up the better.

As (Washington State’s OCIO Open Data Guy) Will Saunders has said often (advice repeated in sources like OKI’s [*Open Data Handbook*](https://opendatahandbook.org/)), overpublishing and undermanaging is the usual scenario, and it leads to disillusionment and low participation. Start small with good-quality data that’s connected to what the community cares about. Keep talking to users, improve, expand as you can, repeat. 

**Figuring out who to talk to, what to look at**
*Identify your users*  
Which people are those users in a user-centered data selection process? Below are parties suggested by various sources. How will you tap these users below?
- The general public
- Other libraries
- Community groups with particular strategic goals
- Local app developers and data activists
- Outside groups interested in libraries: State and federal agencies, non-profits, researchers, grant funders

**Identify the issues (which will lead you to the data people care about)**  
Helping people solve problems is the wave that carries any open data effort. The data published should help people do things they couldn’t do before – assess the budget impact of enacting a new policy such as fine elimination, understand hyper-local reading trends, analyze wifi speeds and usage. 

The [Sunlight Foundation quiz](https://docs.google.com/forms/d/e/1FAIpQLSfcjXVLqdMQp3-3LfwBRDt9Dou7nBCkRzaaX3xnFRgWg96yuw/viewform), [Priority Spokane’s guidelines for choosing indicators](https://drive.google.com/file/d/1wQ3ECXfN_hprAgQV0YUJmZv1k73uGDA6/view?usp=sharing) and [Socrata’s goals-people-data-outcomes](https://socrata.com/open-data-field-guide/define-clear-and-measurable-goals/) examples provide good jumping-off points for your conversations with government officials and members of the community.

## Assignment 1: User Stories + Use Cases
Throughout class we will read examples data curation work that are "user centered." Two broad techniques for developing requirements of systems that are "human centered" are through use cases, and user stories. The following exercises may be helpful in the work you plan to do this quarter in building a protocol to satisfy a community of data users.

### User Stories
User stories are a simple, but powerful way to capture requirements when doing systems analysis and development.

The level of detail, and the specific narrative style will vary greatly on the intended audience. For example, if we want to create a user story for accessing data stored in our repository we will need to think closely about different types of users, their skills, the ways they could access data, the different data they may want, etc.

This could become a very complicated user story that could be overwhelming to translate into actionable policy or features of our data repository.

Instead of trying to think through each complicated aspect of a user's need we can try to atomize a user experience. In doing so we come up with simple story about the user that tells us the "who what and why" - so that we can figure out "how" ...

*Elements*

The three most basic elements of a user story are:
- Stakeholder - the type of stakeholder might be a user, curators, administrator, etc.
- Feature - this could be a feature of a dataset, a system, or service
- Goal - what is the stakeholder trying to achieve with the feature?

*Templates*
A template for a user story goes something like this:

As a `user` I want `some feature` so that I can achieve some `goal`.

As a `data user of the QDR` I want to `find all datasets about recycling for cities in Pacific Northwest` So that I can reliably `compare recycling program policies and outcomes` for this region.

Some variations on this theme: More recent work in human centered design places the goals first - that is, it attempts to say what is trying to be done, before even saying who is trying to do it...

This is helpful for thinking about goals that may be shared across different user or stakeholder types.

This variation of a user story goes something like:

In order to achieve some business value
As a stakeholder type
I want some new system feature

*Here is your task*

Create user stories that help you understand the potential wants, needs, and desires of your designated community of users. For this first attempt - focus on user stories around data sharing.  How might you satisfy these user stories? What choices do these stories help clarify or obscure about your protocol, and your designated community?

Here is an example that can help clarify the way that user stories are assembled for the protocol: https://rochellelundy.gitbooks.io/r3-recycling-repository/content/r3Recycling/protocolReport/userCommunity.html


### Use Cases (Best Practices)
Another way to begin gathering information about users and their expectations for data are through use cases. As you read in week 5 for class the W3C has developed a template for conducting use cases for data on the web best practices. This exercise asks you to use that template to investigate best practices for data and repositories that are relevant to your quarter protocols.

The simple steps to follow:
- Read the Data on the Web Use Cases & Requirements (as part of your weekly reading) https://www.w3.org/TR/dwbp-ucr
- Identify a data collection published on the web that is relevant to your protocol.
- Develop a Use Case following the DWBP outline.

## Public Library Data


{% include links.md %}

