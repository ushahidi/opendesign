# TenFour the OSS crisis communication tool is ready for design contributions.

When you’re any kind of designer coming into an existing project, the first thing you typically do is get familiar with the product, brand, and users of the product or service you’ll be designing for. 

Often this means reviewing a series of hefty documents provided by the company or client, sometimes with past iterations, rationale and if you’re in good company, some insight user journeys and testing to help you understand the goals of the people that are using the product or service.

Rarely, though more regularly seen now, are well-documented, up-to-date design systems or customized frameworks. Either live coded in HTML/CSS or using a generative tool. But for many Open Source Software (OSS) products and tools, creating and maintaining a design system is time and labor-intensive not to mention design skill reliant and, often not carried out as we know the volume of designers contributing to OSS is still small in comparison to those that contribute code.

As such, designers looking to contribute to OSS can find one of their many hurdles to be how they access the building blocks, the UI, graphics, and flows of a product in order to create or modify the design in response to a feature request or issue in the OSS repo.

Without easy access to a test system, framework or design system, designers can only rely on simple wireframes or piecing together screenshots (if they have access to the product). They can also undertake the task of creating the product in design software.

There are some designers proficient in front-end coding that can ‘design in code’. This offers these individuals easier access to the building blocks to contribute design, but it doesn’t work for the large population of designers who’s primary tools are design software.

As part of the Open Design project goals, we’re focusing on one of [Ushahidi’s](https://www.ushahidi.com/) OSS tools, [TenFour](https://tenfour.org/) to see if a framework of support, documentation, collaboration and example files can increase design contributions to this OSS and more to come in the future. TenFour is a PWA app that uses [Ionic](https://ionicframework.com/) as a framework to build functionality and visuals. Ionic has a series of standard and customizable components that are now detailed and described in the TenFour design kit, which is available in XD.

## Our design kit for TenFour

The TenFour design kit was created in our design software of choice, Adobe XD. The file includes global elements used across the TenFour product as well as sample screens of many of the core functions of TenFour.

The global elements include those actively used in the product and also those that have previously been created and remain unused, but potentially useful assets for future features and layouts of the TenFour product.

We opted to include not only global example elements but as comprehensive a sample of screens from the live application so that designers can, in one file, get a sense of how TenFour operates and functions as a tool for communication in crisis scenarios.

This design kit can be iterated on, added to and improved in order to make design contributions to TenFour even easier in the future, just like the OSS tool it supports.

## How to find the TenFour design kit

You can find the TenFour design kit file in the Open Design issue [here](https://github.com/ushahidi/opendesign/issues/135) and in the TenFour repository on Github [here](https://github.com/ushahidi/tenfour/blob/develop/design-contributions.md).

[You can download the TenFour design kit here] (https://github.com/ushahidi/tenfour/blob/develop/design-contributions.md)

Currently, you can download the XD file to use for working on TenFour design issues. There are also links to view the content of the XD file [here](https://xd.adobe.com/view/d6acbb4d-0dce-44da-7093-bac08af8152d-a09d/) and [here](https://xd.adobe.com/spec/4ab4337a-d4a2-4f40-4881-f2349b12d769-3c85/grid).

This is the first version of the TenFour design kit for OSS contributions and versioning of the file will be kept track of in the [design contributions](https://github.com/ushahidi/tenfour/blob/develop/design-contributions.md) file in the TenFour repo. 

## Using the TenFour design kit XD file

When using the TenFour design kit we recommend that you pull the components and page layouts from the design kit and use them in a new file that has 

* The name of the TenFour issue. 
* The issue number.
* Your GitHub username .

in the XD file name in order to distinguish different files from contributors.

We ask all potential future contributors to not erase previous components unless they have been deprecated in Ionic and that we keep meticulous records of the file versions.

## How to start contributing to TenFour

First, take a look at the TenFour repo’s [Read me file](https://github.com/ushahidi/tenfour/blob/develop/README.md) in Github, this will give you some background information on TenFour’s purpose as a product. There’s also an informational [slide deck about TenFour](https://drive.google.com/file/d/1B80_hcdWD-7SQFdssUzzRegfChtbwjdH/view) that will give you some in-depth information about the problem space of communication in a crisis scenario that TenFour is aiming to help solve.

Next, we recommend you [download the TenFour design kit](https://github.com/ushahidi/tenfour/blob/develop/design-contributions.md) and take a look at the product screen examples and the design system to work with. 

You’re now ready to take a look at the TenFour repo that ‘need design’. We’ve separated this by suggested design function, [UX](https://github.com/ushahidi/tenfour/labels/Design%3A%20UX), [UI](https://github.com/ushahidi/tenfour/labels/Design%3A%20UI), [Visual/Graphic](https://github.com/ushahidi/tenfour/labels/Design%3A%20Visual%2FGraphic), [Usability/Inclusive design](https://github.com/ushahidi/tenfour/labels/Design%3A%20Inclusion), [Interaction design](https://github.com/ushahidi/tenfour/labels/Design%3A%20Interaction), [User Research](https://github.com/ushahidi/tenfour/labels/Design%3A%20User%20Research). You can also suggest that we add new labels for design-related work not expressed in these labels. 

Ask questions in the comments section of any issue if you need further clarification on how to approach the issue.

When you’ve completed your design response to an issue in the TenFour repo, we recommend adding your contributions via the comments section of the issue and be sure to add the XD design file you created from the TenFour design kit. Explain in as much detail how you responded to the needs of the issue, user case and any requirements detailed in the issue.

Add a new issue to the [Open Design repo](https://github.com/ushahidi/opendesign/issues) with a link back to the issue in the TenFour/OSS repo. This will ensure that if you need support form the Open Design community, it can be discovered and responded to.

We’ll be developing how we agree on design critique and feedback as an Open Design community going forward but we’ll be advocating for a supportive, collaborative environment that prioritizes users, design mentoring, skill development and inclusion first.

[If you can attend an Open Design event or workshop](https://github.com/ushahidi/opendesign/blob/master/events.md) we highly encourage this. These events are where we’ll be testing our [workshop framework](https://github.com/ushahidi/opendesign/blob/master/workshop-framework.md) and seeing how the global design community works best collaboratively on OSS.

If you can’t attend, we encourage you to use and remix the workshop framework and organize a local event yourself.

### Can I offer other design contributions like user testing or UX work?
You can use [Ushahidi’s documentation guides](https://app.gitbook.com/@ushahidi/s/platform-developer-documentation/design/design-process) on how to contribute design work like user test scripts, UX studies and performing and analyzing user testing results. This work greatly informs the rest of the design work that the TenFour design kit will be used for so we encourage these contributions too.

### What next?
If you can, join us at one of our live workshops where we’ll form teams to go in-depth on large features and issues for TenFour and explore the situations through empathy exercises and contextual inquiry and actively use the TenFour design kit as a team.


