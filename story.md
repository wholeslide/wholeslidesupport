## TL;DR

#### Purpose

	To crowdfund the development of an open source iOS app for viewing high resolution virtual microscopy slides from open access content providers.

#### What are virtual slides?

	Virtual slides are high resolution digital images of microscope slides. Think "Google Maps" for biopsies, brain anatomy, and blood work. 

#### Who will use it?

	Medical Students & Instructors, Clinicians, Researchers, Anatomists 

#### Why crowdfund it?

	Absence of scalable market and slow tech innovation in MedEd => this app won't be funded without community support.

#### How will funds be used?

	85% to support 2-3 months of full time software development, 15% for development expenses and overhead. Any excess beyond target will go towards Android development.

#### How can you help?

	Individuals: Donate or beta test. 
	Small companies: Sponsor a feature. 
	Open access content providers: Let us index your content.
	Everyone: Spread the word!

## The long version

### Kickstarting medical education technology

The purpose of this Kickstarter is to support the development of an open source tablet-based virtual slide viewer for medical education. Such a product would rarely be funded as a research endeavor and has no scalable business model as a startup. This is a personal effort to put a usable tool into the hands of those that could teach with it and learn through it. 

To start from scratch would require months of research and planning. Thankfully, I won’t need to. In 2011, I released WholeSlide for iPad - a free application that allows medical students, educators, and faculty to quickly access high resolution virtual microscopy images. Students can access virtual slide data from 10+ preselected sources including several brain atlases, digital pathology providers, and medical libraries. Since then, application development has gotten easier, libraries have gotten better, and I've built up a list of experimental apps I've put together but never released. 

Drawing from this experience, I will write a new version of wholeslide from scratch - bringing anyone along that 

### What will be built?

An open source iOS app for viewing high resolution virtual microscopy slides. 

I'll start with a series of user stories and build from them a focused user interface. Unlike the original WholeSlide application, the new version will be built around a modular design with a goal of easy extensibility and customization.

![architecture diagram](https://raw.github.com/wholeslide/wholeslidesupport/master/images/architecture-diagram.png)

The backend will support a range of virtual slide servers, image formats, and annotation formats. Browser modules will be built to support a range of content providers while a common virtual slide viewer will handle efficient image rendering. 

Slide interaction modules will sit at the top of the stack providing ways to adjust the image properties, annotation details, or do something clever like link to an image search API. 

### What will it look like?

Aesthetically, the app will use a simple palette and pay homage to the great Sublime Text 2 user interface. All textures and icons will be CC, GPL-safe, or released in the public domain. 

![basic UI](https://raw.github.com/wholeslide/wholeslidesupport/master/design/concept/preview-ipad.004.jpg)

The app will borrow heavily from tabbed web browsers & text editors - supporting reorganizable tabs, split-tab views, and means to link side-by-side views. This allows a user to bring up a course outline in the left view while navigating a virtual slide in the right. 

![edu UI](https://raw.github.com/wholeslide/wholeslidesupport/master/design/concept/preview-ipad.010.jpg)

All content in the design and development processes will be made available on github.com and released under a Creative Commons Attribution-NonCommercial-ShareAlike license. 


### How can you help?

If you're an **open access content provider**, let us index your virtual slide list and course materials. Contact us via email and we'll help you make your content available through the app. We greatly appreciate the effort put in to make high quality content available - we want to help it reach a broader audience.

If you're a **virtual slide server vendor**, let us enable support for your server and annotation formats. By sponsoring the development, we'll work with you to ensure first class support of one or more server formats as well as custom views for your content. Contact us and we'll help figure out the best fit.

If you're an **educator**, work with us to build an intuitive interface to your content. Become a beta tester to get early access to each build, with new releases pushed as features get added. 

If you're a **student**, help raise awareness for this project - pass the word on to your instructors or school administrators. 

**Philanthropists and Non-profits** - Donate! In addition to providing a tool for domestic (US-based) medical education - we're actively looking at ways to get this app or an Android equivalent into the hands of medical students around the world. 

**Developers & Designers** - Volunteer. This development will be done out in the open with all content and coding committed to public github repositories. You're free at any time to branch the code and start on any features or ideas you may have. 


### Why crowdfund? Why not just make an app and charge for it? 

This option was considered but decided against for several reasons:

* The market to support such an application is small. 
* The primary customers - medical students and researchers - are already loaded with debt.
* By making the app open source and free, open access content providers, server vendors, and academic institutes can come together to produce a single great thing rather than many single-purpose applications. 

In short - this app is not being built with a sustainable business model in mind. It's something I think needs to exist even without a flush market to support it. 

### What will the funding be used for?

Approximately 8%-10% of the funds raised will go to software licenses and development costs (e.g. Apple Enterprise Developer account, hosting costs for the search engine).

The remaining will support full time effort for a single developer (me) over a 2-3 month span. Additional funds raised beyond the target will be reinvested in generating better documentation, more features, and third-party bug testing. 

## Development Timeline

#### Milestone I - Start September 15, Complete by October 30* WholeSlide code base refresh and initial release to beta testers (via enterprise distribution)* Github site is populated (private) and partners with feature role can start adding features in the form of GH issues.#### Milestone II - Start November 1, Complete by December 30* Feature additions and continued testing. Periodic releases (timeline TBD) as new features and data sources come online#### Milestone III - January 1, 2014* First public release. App goes live on store (free) and github repository becomes public. 

### Risks and Challenges

The greatest risk for this endeavor is the off chance that I am unable to finish the development according to the original timeline. Very few of the features planned are new - they've just never been put into a common open source application before. 

The greatest challenge will be driving uptake and usage of the app by medical schools. We will need champions of technology at each medical school to try using the app, provide feedback, and contribute new and better open access content for this to truly succeed. 

Building a capable application is only the first step towards building an open access content delivery mechanism.
