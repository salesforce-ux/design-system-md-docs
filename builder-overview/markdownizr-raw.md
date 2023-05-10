<a id="jump-to-nav">Jump to Navigation</a>[Skip to Content](#site-main-content)[SalesforceLightning Design System](/)

<form class="slds-grid site-search slds-grid_vertical-align-center" novalidate=""><label for="search-landing-nav" class="slds-assistive-text">Search</label><input id="search-landing-nav" class="site-searchbox__input slds-input site-search-input ds-input" type="text" name="search" placeholder="Search" autocomplete="off" required="" spellcheck="false" role="combobox" aria-autocomplete="list" aria-expanded="false" aria-owns="algolia-autocomplete-listbox-6" dir="auto" style="position: relative; vertical-align: top;">Submit your search query</form>

<main class="site-main slds-order_1" role="main" id="site-main-content" tabindex="-1">Overview

# Overview

## Guidelines

*   [Introduction](#Overview-Introduction)
*   [Usage](#Overview-Usage)
*   [Workflow](#Overview-Workflow)
    *   [Where to Launch a Builder](#Overview-Workflow-Where-to-Launch-a-Builder)
    *   [Record Information: Names, Versions, and Statuses](#Overview-Workflow-Record-Information:-Names,-Versions,-and-Statuses)
    *   [Settings and Help](#Overview-Workflow-Settings-and-Help)
    *   [Saving Builder Records](#Overview-Workflow-Saving-Builder-Records)
    *   [Autosave](#Overview-Workflow-Autosave)
    *   [Activating or Publishing](#Overview-Workflow-Activating-or-Publishing)
    *   [Exiting a Builder](#Overview-Workflow-Exiting-a-Builder)

Declaratively build and visualize applications and business processes.

<figure>![Overview header](/assets/images/guidelines/builder/overview/Overview_Hero.png)</figure>

## Introduction

A builder is a tool that lets everyone from developers and admins to business users create and customize applications and business processes. Developers and admins use builders such as Lightning App Builder, Experience Builder, Bot Builder, and Flow Builder to create interfaces for business users. Users can also create experiences for teams or customers with tools such as Journey Builder and Engagement Studio.

There are four main types of builder:

*   **Logic builders** visualize business processes, flows, or sequences.
*   **Content builders** are used to design and configure web pages and other visual elements.
*   **Data builders** help users develop reports and presentations featuring tables, charts, and graphs.
*   **Code builders** are used to develop code views and database schemas.

## Design Resources

[Download Sketch Kit](https://github.com/salesforce-ux/design-system-ui-kit)

## Usage

When should you think about using a builder? Start, as always, with the user. If users will be doing one or more of these things, there could be a builder in your future:

*   Working with WYSIWYG (“what you see is what you get”) declarative elements that can be added with clicks and customized with forms
*   Designing a business process on a blank canvas
*   Creating and defining a series of logical actions that result in different outputs
*   Defining the relationship of one element to another—for example, in a workflow or visual layout
*   Saving and tracking multiple drafts or versions

If a builder isn’t a good fit, consider using another framework, such as a [directional modal](/components/modals/#Directional), [Channel Studios on Marketing Cloud](https://www.salesforce.com/products/marketing-cloud/overview/), or use an [expression](/components/expression/), [form](/components/form-element/), or [filter](/guidelines/rules-filters-logic/).

## Workflow

### Where to Launch a Builder

Depending on your target user, a builder can be opened from Setup, an app, or a record page.

#### For Admins and Developers Customizing Salesforce

*   In Setup, launch the builder in full-screen mode.
*   Make sure that the builder, its list-view, and any detail pages can be accessed from the builder home page in Setup.

<figure class="site-figure site-figure_no-border">![A builder home page in Setup; blue brand button opens the builder](/assets/images/guidelines/builder/overview/Builder-Home.png)

<figcaption class="site-figure__caption">A builder home page in Setup; blue brand button opens the builder</figcaption>

</figure>

<figure class="site-figure site-figure_no-border">![A builder record page in Setup; blue brand button opens the builder](/assets/images/guidelines/builder/overview/Builder-Record.png)

<figcaption class="site-figure__caption">A builder record page in Setup; blue brand button opens the builder</figcaption>

</figure>

#### For Salesforce App and Console Users

*   Launch a builder from a relevant record detail page or app page. For example, Journey Builder can be launched from any Journey record page.

<figure class="site-figure site-figure_no-border">![Wireframe showing a standard file list.](/assets/images/guidelines/builder/overview/App-Listview.png)

<figcaption class="site-figure__caption">Launch a builder from a standard file list; use title text (blue links) or create a row-level action</figcaption>

</figure>

<figure class="site-figure site-figure_no-border">![Launching a builder from a standard object record detail page](/assets/images/guidelines/builder/overview/App-Record.png)

<figcaption class="site-figure__caption">Launch a builder from a standard record detail page; use an action button (blue button) in the top right of the header</figcaption>

</figure>

<figure class="site-figure">![Record view in a Salesforce Console app; blue brand button opens the builder](/assets/images/guidelines/builder/overview/App-Console-Record.png)

<figcaption class="site-figure__caption">Record view in a Salesforce Console app; blue brand button opens the builder</figcaption>

</figure>

<figure class="site-figure site-figure_no-border">![Do open a builder in a new browser tab with a utility bar](/assets/images/guidelines/builder/overview/Console-Launch-Do.png)

<figcaption class="site-figure__caption">Do open a builder in a new browser tab with a utility bar</figcaption>

</figure>

<figure class="site-figure site-figure_no-border">![Don’t open the builder in a Salesforce Console tab](/assets/images/guidelines/builder/overview/Console-Launch-DoNot.png)

<figcaption class="site-figure__caption">Don’t open the builder in a Salesforce Console tab</figcaption>

</figure>

*   In Salesforce Console, a builder should open in a new window or browser tab—**not** in a console tab or subtab.
*   A utility bar that overlays the interface can persist over a builder. If the user navigates away from the builder by clicking the utility bar, an alert should warn that unsaved changes may be lost. See [Modal usage](/guidelines/builder/modals) for warning messages.
*   Builder record metadata can be represented in a console tab or sub-tab.

### Record Information: Names, Versions, and Statuses

Before opening a builder, start on the **record list** page, which includes a clear summary of **file names**, **versions**, and **statuses**. Display this information in the builder, in the record list, record detail, and builder header.

#### Record List

Display file name, version, and status in the builder list.

<figure class="site-figure">![Builder home layout](/assets/images/guidelines/builder/overview/Builder-Home.png)

<figcaption class="site-figure__caption">Builder home layout</figcaption>

</figure>

#### Record Detail

To orient users without making them return to the builder, provide a dedicated view of file name and version(s) for each record. 

<figure class="site-figure">![File overview layout](/assets/images/guidelines/builder/overview/Builder-Record.png)

<figcaption class="site-figure__caption">File overview layout</figcaption>

</figure>

#### Builder Header

The builder header should include the builder name, file name, and save status. 

<figure class="site-figure">![Builder header layout](/assets/images/guidelines/builder/overview/Builder-Header-Layout.png)

<figcaption class="site-figure__caption">Builder header layout</figcaption>

</figure>

_For more information about the Builder header, see_ [_Header Guidelines_](/guidelines/builder/header) _and_ [_Header Component Blueprint_](/components/builder-header/)_._

### Settings and Help

The top right of the builder’s header bar is reserved for links to builder-level settings and help documentation.

<figure class="site-figure">![Builder help menu at the top right of the header bar](/assets/images/guidelines/builder/overview/OV-Builder-rhs-helpv4.png)

<figcaption class="site-figure__caption">Builder options at the top right of the header bar</figcaption>

</figure>

### Saving Builder Records

When working in a builder, users tend to save changes often. Some builders also let users activate, run, or publish.

Saving is a server-side snapshot of an object and its state. Note that saving does not equal approval to push an object for activation or publication; these are two separate actions. If saving does activate/publish a file or execute a process, explicitly call this out.

#### When and how can I save my builder objects?

*   Use a Save button to initiate a server-side save of the entire object.
*   When a builder allows manual saving, users should be allowed to save even when their work contains errors. (See [Validation](/guidelines/builder/validation) for more information on messaging.)
*   When a save also triggers activation/publication, allow the file to be saved without push. Alert the user to any errors blocking activation/publication.

#### What about versioning?

*   Builders may allow object versioning. If your builder does so, let users clone or copy objects with a Save As command.
*   If a builder autosaves (and creates auto-versions for each save), batch any changes into a new version. Make it easy for users to view and revert to previous versions.

<figure class="site-figure">![Use a Save button for server-side saving. Use Save As to create a copy. ](/assets/images/guidelines/builder/overview/OV-Builder-save.png)

<figcaption class="site-figure__caption">Use a Save button for server-side saving. Use Save As to create a copy.</figcaption>

</figure>

#### What happens when I save with multiple records open?

*   Multiple records can be viewed simultaneously in new browser windows or tabs.
*   An explicit save affects only the record currently in focus—_not_ other open records.
*   When a user attempts to closes a browser window with unsaved records, display a warning that they will lose all unsaved changes.

#### Indicating Status

Clearly communicate the status of save, activate, and other actions, without overwhelming users or drawing focus from the task at hand.

_For more information, see_ [_Status Text_](/guidelines/builder/header#Header-Toolbar-Status-Text) _in the Header Toolbar section._

### Autosave

Consider these principles when using autosave:

*   **Confidence.** Make clear what is and isn’t saved at all times. Can an autosave offer the trust of an explicit save button?
*   **Simplicity.** How are previous versions presented? Reinstated? What’s a simple, easy, and on-pattern way for users to perform these actions?
*   **Data.** Where do autosave versions live? Do they affect a user’s data limits? Are both users and Salesforce prepared to deal with the data implications?
*   **Performance.** What effect will constant saving have on performance? Are the benefits of autosaving and versioning enough to outweigh any lag?

### Activating or Publishing

Most builders separate save functionality from publication/activation, allowing users to edit without affecting runtime or live business processes.

Place the Activate or Publish action at the right side of the builder toolbar, with other action buttons. If technical or other factors make that difficult, place it on the Builder Home or Record Overview page.

<figure class="site-figure">![Activate action button](/assets/images/guidelines/builder/overview/OV-header-activating-1.png)

<figcaption class="site-figure__caption">Activate action button</figcaption>

</figure>

_For more information, see_ [_Activate/Deactivate_](../header#Header-Toolbar-Activate/Deactivate) _in the Header Toolbar section._

### Exiting a Builder

To exit a builder, users close the browser window or click the Back button in the header bar. The user will return to the page from which the builder was launched.

<figure class="site-figure">![The Back button is located in the top left corner of the Builder header bar](/assets/images/guidelines/builder/overview/OV-Builder-rhs-options.png)

<figcaption class="site-figure__caption">The Back button is located in the top left corner of the Builder header bar</figcaption>

</figure>

Next: [_Configuration_](/guidelines/builder/configuration)

</main>

© Copyright 2015-present Salesforce, Inc. [All rights reserved](https://www.salesforce.com/company/legal/intellectual/). Various trademarks held by their respective owners.

Salesforce, Inc. Salesforce Tower, 415 Mission Street, 3rd Floor, San Francisco, CA 94105, United States

Site: Version 1.2.44 | Framework: Version 2.21.0\. Last Updated on May 5th 2023, 2:27 pm.

*   [Twitter](https://twitter.com/salesforceux "Follow @salesforceux on Twitter")
*   [Dribbble](https://dribbble.com/salesforce "Find us on Dribbble")
*   [GitHub Repository](https://github.com/salesforce-ux/design-system "Get the code on GitHub")

## Cookie Consent Manager

*   ### General Information

*   ### Required Cookies

*   ### Functional Cookies

*   ### Advertising Cookies

### General Information

We use three kinds of cookies on our websites: required, functional, and advertising. You can choose whether functional and advertising cookies apply. Click on the different cookie categories to find out more about each category and to change the default settings.  
[Privacy Statement](https://www.salesforce.com/company/privacy/full_privacy/)

### Required Cookies

Always Active

Required cookies are necessary for basic website functionality. Some examples include: session cookies needed to transmit the website, authentication cookies, and security cookies.

Cookies Details‎

### Functional Cookies

<input type="checkbox" name="ot-group-id-3" id="ot-group-id-3" aria-checked="true" role="switch" class="category-switch-handler" data-optanongroupid="3" checked="" aria-labelledby="ot-header-id-3"> <label class="ot-switch" for="ot-group-id-3"> Functional Cookies</label>

Functional cookies enhance functions, performance, and services on the website. Some examples include: cookies used to analyze site traffic, cookies used for market research, and cookies used to display advertising that is not directed to a particular individual.

Cookies Details‎

### Advertising Cookies

<input type="checkbox" name="ot-group-id-4" id="ot-group-id-4" aria-checked="true" role="switch" class="category-switch-handler" data-optanongroupid="4" checked="" aria-labelledby="ot-header-id-4"> <label class="ot-switch" for="ot-group-id-4"> Advertising Cookies</label>

Advertising cookies track activity across websites in order to understand a viewer’s interests, and direct them specific marketing. Some examples include: cookies used for remarketing, or interest-based advertising.

Cookies Details‎

### Back

<label for="vendor-search-handler" class="ot-scrn-rdr">Vendor Search</label> <input id="vendor-search-handler" aria-label="Vendor Search" type="text" placeholder="Search..." name="vendor-search-handler">Consent Leg.Interest<input id="select-all-hosts-groups-handler" type="checkbox" aria-checked="false"> <label for="select-all-hosts-groups-handler">checkbox label</label> label<input id="select-all-vendor-groups-handler" type="checkbox" aria-checked="false"> <label for="select-all-vendor-groups-handler">checkbox label</label> label<input id="select-all-vendor-leg-handler" type="checkbox" aria-checked="false"> <label for="select-all-vendor-leg-handler">checkbox label</label> label

*   View Third Party Cookies

    *   Namecookie name

Clear<input id="chkbox-id" type="checkbox" aria-checked="false" class="category-filter-handler"> <label for="chkbox-id">checkbox label</label> labelApply CancelSave SettingsAccept All Cookies[](https://www.onetrust.com/products/cookie-consent/)
