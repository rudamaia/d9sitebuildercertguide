[<< Previous](readme.md)
# Terminology

## Ajax

A web technology used to exchange data with a server to dynamically update parts of a web page (for example, forms) without needing entire page reloads.

## Alias

A user-friendly name to replace the internal [path](#path) that the system assigns to a URL on the site. For example, you might assign an alias of _/about_ to the About page on your site, to replace the internal path _/node/5_. This would give the page a URL of _http://example.com/about_ instead of _http://example.com/node/5_. See [Section 5.1, “Concept: Paths, Aliases, and URLs”](path-aliases-url.md) for more information.

## Anonymous

A person ([user](#user)) interacting with the site who is not logged in. See [Section 7.1, “Concept: Users, Roles, and Permissions”](user-roles-permissions.md) for more information.

## Block

A chunk of [content](#content) (text, images, links, etc.) that can be displayed on a page of a site. Blocks are displayed in [regions](#region). See [Section 8.1, “Concept: Blocks”](https://www.drupal.org/docs/user_guide/en/block-concept.html " Blocks") for more information.

## Block Type

Like the [content type](#content-type) the block type is used to define its fields and the way it is displayed. It is possible to create custom block types.

## Block Layout
[Blocks](#block) are boxes of content rendered into a [region](#region) of a web page (such as "User Login" or "Who's online") that can be displayed in [regions](#region) (such as footer or sidebar) on your page.

## Breakpoint

Breakpoints are used to separate the height or width of browser screens, printers, and other media output types into steps. A [responsive](#responsive) site adjusts its presentation at these breakpoints. See [Section 6.14, “Concept: Responsive Image Styles”](https://www.drupal.org/docs/user_guide/en/structure-image-responsive.html " Responsive Image Styles") for more information.

## Bundle

Synonym for [Entity subtype](#entity-subtype).

## Cache

The site’s internal cache stores the output of time-consuming calculations, such as computing output for an HTML page request, and then retrieves them instead of recalculating the next time they are needed. External caching systems can also be used on the web server to speed up a site’s response. See [Section 12.1, “Concept: Cache”](https://www.drupal.org/docs/user_guide/en/prevent-cache.html " Cache") for more information on the internal cache.

## CMS

Acronym for [Content Management System](#content-management-system).

## Configuration

Information about your site that is not [content](#content), and is meant to be more permanent than [state](#state) information, such as the name of your site, the [content types](#content-type) and [views](#view) you have defined, etc. See [Section 1.5, “Concept: Types of Data”](https://www.drupal.org/docs/user_guide/en/understanding-data.html " Types of Data") for more information.

## Contact

The Contact module allows site visitors to send emails to other authenticated users and to the site administrator. Contact Forms can be attached to [user] (#user) entities and [content](#content) entities.
([Contact module overview](https://www.drupal.org/docs/8/core/modules/contact/overview)).

## Content

Information meant to be displayed on your site, such as text, images, downloads, etc. See also [Configuration](#configuration) and [State](#state). See [Section 1.5, “Concept: Types of Data”](https://www.drupal.org/docs/user_guide/en/understanding-data.html " Types of Data") for more information.

## Content item

An item of [content](#content) that is typically meant to be displayed as the main content of a page on your site. This is an [entity type](#entity-type). See [Section 2.3, “Concept: Content Entities and Fields”](https://www.drupal.org/docs/user_guide/en/planning-data-types.html " Content Entities and Fields") for more information.

## Content Management System (CMS)

A collection of tools designed to allow the creation, modification, organization, search, retrieval and removal of information on a website. See [Section 1.1, “Concept: Drupal as a Content Management System”](https://www.drupal.org/docs/user_guide/en/understanding-drupal.html " Drupal as a Content Management System") for more information.

## Content type

An [entity subtype](#entity-subtype) for the [content item](#content-item) [entity type](#entity-type). Each content type is used for some particular purpose on the site, and each has its own fields. For example, a site for a farmers market might have a content type for simple pages, and another for a vendor listing page. See [Section 2.3, “Concept: Content Entities and Fields”](https://www.drupal.org/docs/user_guide/en/planning-data-types.html " Content Entities and Fields") for more information.

## Contextual link

A link to an administrative page for editing or configuring a feature of the site, shown in the context where that feature is displayed. Example: a link to configure a [menu](#menu) that is shown when you hover your mouse over the menu. See [Section 4.1, “Concept: Administrative Overview”](https://www.drupal.org/docs/user_guide/en/config-overview.html " Administrative Overview") for more information.

## Contributed

[Modules](#module), [themes](#theme), and [distributions](#distribution) that are not part of the [Drupal core](#drupal-core) download, and that can be downloaded separately from the [_Drupal.org_](https://www.drupal.org) website.

## Comment type

An [entity subtype](#entity-subtype) for the comment [entity type](#entity-type). Comment types are like content types in that they are fieldable and can have additional fields added to them to capture info outside of the normal subject, author, and comment. Comments can be displayed in pages, view listing and so on, like any entity, but also, different from content entity, the comment entity by default have a input form for the [anonymous](#anonymous) user to create new comments, or, the [Role](#role) with given [permission](#permission).

## Cron

On some operating systems, _cron_ is a command scheduler application that executes commands or scripts periodically. Your site defines periodic tasks, also known as cron tasks, that need to be triggered either by an operating system cron scheduler, or internally. See [Section 13.1, “Concept: Cron”](https://www.drupal.org/docs/user_guide/en/security-cron-concept.html " Cron") for more information.

## Custom module

By definition a custom module is a module that are currently not [contributed](#contributed) in Drupal.org but writen by yourself in the current project.

## Distribution

A single download that provides a shortcut for setting up a specific type of site, such as a website for a club or for e-commerce. A distribution contains [Drupal core](#drupal-core), along with [contributed](#contributed) [modules](#module) and/or [themes](#theme); many distributions also pre-configure the site or even create sample content upon installation. See [Section 1.4, “Concept: Distributions”](https://www.drupal.org/docs/user_guide/en/understanding-distributions.html " Distributions") for more information.

## Drupal core

The files, themes, profiles, and modules included with the standard project software download. See [Section 1.1, “Concept: Drupal as a Content Management System”](https://www.drupal.org/docs/user_guide/en/understanding-drupal.html " Drupal as a Content Management System") for more information.

## Entity

An item of either [content](#content) or [configuration](#configuration) data, although in common usage, the term often refers to content entities. Examples include [content items](#content-item), custom [blocks](#block), [taxonomy terms](#taxonomy-term), and definitions of [content types](#content-type); the first three are content entities, and the last is a configuration entity. See also [Entity type](#entity-type), [Entity subtype](#entity-subtype), and [Field](#field). See [Section 2.3, “Concept: Content Entities and Fields”](https://www.drupal.org/docs/user_guide/en/planning-data-types.html " Content Entities and Fields") for more information.

## Entity subtype

Within a [content](#content) [entity type](#entity-type), a grouping of entities that share the same [fields](#field). For example, within the [content item](#content-item) entity type, a farmers market site might have subtypes (known as [content types](#content-type)) for static pages and vendor pages, each with its own group of fields. You may also see the term _bundle_ used (especially in programmer documentation) as a synonym of entity subtype. See [Section 2.3, “Concept: Content Entities and Fields”](https://www.drupal.org/docs/user_guide/en/planning-data-types.html " Content Entities and Fields") for more information.

## Entity type

The overall type of an [entity](#entity); in common usage, it is only applied to a [content](#content) entity. Examples include [content types](#content-type), [taxonomy terms](#taxonomy-term), and custom [blocks](#block). See [Section 2.3, “Concept: Content Entities and Fields”](https://www.drupal.org/docs/user_guide/en/planning-data-types.html " Content Entities and Fields") for more information.

## Field

Data of a certain type that is attached to a [content](#content) [entity](#entity). For instance, on a farmers market site’s vendor content type, you might have fields for an image, the vendor description, and a [taxonomy term](#taxonomy-term). See [Section 2.3, “Concept: Content Entities and Fields”](https://www.drupal.org/docs/user_guide/en/planning-data-types.html " Content Entities and Fields") for more information.

## Field bundle

Synonym for [Entity subtype](#entity-subtype).

## Field formatter

[Configuration](#configuration) that defines how the data in a [field](#field) is displayed. For example, a text field could be displayed with a prefix and/or suffix, and it could have its HTML tags stripped out or limited. See also [View mode](#view-mode) and [Field widget](#field-widget). See [Section 6.10, “Concept: View Modes and Formatters”](https://www.drupal.org/docs/user_guide/en/structure-view-modes.html " View Modes and Formatters") for more information.

## Field widget

[Configuration](#configuration) that defines how someone can enter or edit data for a [field](#field) on a data entry form. For example, a text field could use a single-line or multi-line entry box, and there could be a setting for the size of the box. See also [Field formatter](#field-formatter). See [Section 6.8, “Concept: Forms and Widgets”](https://www.drupal.org/docs/user_guide/en/structure-widgets.html " Forms and Widgets") for more information.

## Form Mode
Like [view modes](#view-mode), form modes are a way to create different field configurations with the same content entity bundle, but, for the 'edit' and 'add' operations, not the entity viewing which belongs to [view mode](#view-mode)

https://www.drupal.org/docs/8/api/entity-api/display-modes-view-modes-and-form-modes#s-form-modes-and-form-operations
## Formatter

See [Field formatter](#field-formatter).

## FOSS

Acronym for _Free and Open Source Software_, meaning software that is developed by a community of people and released under a non-commercial license. See also [GPL](#gpl). See [Section 1.6, “Concept: The Drupal Project”](https://www.drupal.org/docs/user_guide/en/understanding-project.html " The Drupal Project") for more information.

## GPL

Acronym for the _GNU General Public License_, a non-commercial software license. All software downloaded from the [_Drupal.org_](https://www.drupal.org) website is licensed under the ["GNU General Public License, version 2"](http://www.gnu.org/licenses/old-licenses/gpl-2.0.html). See also [FOSS](#foss). See [Section 1.7, “Concept: Drupal Licensing”](https://www.drupal.org/docs/user_guide/en/understanding-gpl.html " Drupal Licensing") for more information.

## Image style

A set of processing steps that transform a base image into a new image; typical processing includes scaling and cropping. See [Section 6.12, “Concept: Image Styles”](https://www.drupal.org/docs/user_guide/en/structure-image-styles.html " Image Styles") for more information.

## Issue
Issues are problems or feature requests detected in the drupal core or in a [contrib module](#module). Those [issues](https://www.drupal.org/project/issues) can be shared in the drupal community in the form of an issue. Every drupal project(module) has it's issue page that will be used to report any problem or feature request.
[Issues how to](https://www.drupal.org/docs/develop/issues/issue-procedures-and-etiquette/issue-etiquette)
## Language
Languages are used to translate content and the site interface in Drupal. [Multi-lingual guide](https://www.drupal.org/docs/multilingual-guide)

## LAMP

Acronym for _Linux, Apache, MySQL, and PHP_: the software on the web server that the scripts commonly run on (although it can use other operating systems, web servers, and databases). See [Section 3.1, “Concept: Server Requirements”](https://www.drupal.org/docs/user_guide/en/install-requirements.html " Server Requirements") for more information.

## Layout
Drupal 8's Layout Builder allows content editors and site builders to easily and quickly create visual layouts for displaying content. Users can customize how content is arranged on a single page, or across types of content, or even create custom landing pages with an easy to use drag-and-drop interface.
[Layout overview](https://www.drupal.org/docs/8/core/modules/layout-builder)

## Log

A list of recorded events on the site, such as usage data, performance data, errors, warnings, and operational information. See [Section 12.4, “Concept: Log”](https://www.drupal.org/docs/user_guide/en/prevent-log.html " Log") for more information.

## Mainteinnance mode
Drupal core has a [Mainteinnance mode](https://www.drupal.org/docs/user_guide/en/extend-maintenance.html) feature that enables the site administrator to put the site in a state that [anonymous](#anonymous) users won't be able to view the site content but a temporary 'maintenance message'. There is dedicated permission for this feature in order to give access to thedesired [roles](#role)..



## Media

The core Media module manages the creation, editing, deletion, settings, and display of media entities. Media items are typically images, documents, slideshows, YouTube videos, tweets, Instagram photos, etc. [Media documentation](https://www.drupal.org/docs/8/core/modules/media)

## Menu

A set of links used for navigation on a site, which may be arranged in a hierarchy. See [Section 5.6, “Concept: Menu”](https://www.drupal.org/docs/user_guide/en/menu-concept.html " Menu") for more information.

## Module

Software (usually PHP, JavaScript, and/or CSS) that extends site features and adds functionality. The Drupal project distinguishes between _[core](#drupal-core)_ and _[contributed](#contributed)_ modules. See [Section 1.2, “Concept: Modules”](https://www.drupal.org/docs/user_guide/en/understanding-modules.html " Modules") for more information.

## Path

The unique, last part of the internal URL that the system assigns to a page on the site, which can be a visitor-facing page or an administrative page. For example, the internal URL for the About page on your site might be _http://example.com/node/5_, and in this case, the path is _node/5_. See also [Alias](#alias). See [Section 5.1, “Concept: Paths, Aliases, and URLs”](path-aliases-url.md) for more information.

## Patch
A Patch is a text file, whose contents are similar to Git diff, but along with code. Patches are quick fixes that can be applied to Drupal Projects in order to correct [issues](#issue).

## Permission

The ability to perform some action on the site, such as editing a particular type of [content](#content), or viewing user profiles. See also [Role](#role). See [Section 7.1, “Concept: Users, Roles, and Permissions”](user-roles-permissions.md) for more information.

## Reference field

A [field](#field) that represents a relationship between an [entity](#entity) and one or more other entities, which may be the same [entity type](#entity-type) or a different type. For example, on a farmers market site, a recipe content item might have a reference field to the vendor (also a content item) that posted the recipe. [Taxonomy term](#taxonomy-term) fields are also reference fields. See [Section 6.4, “Concept: Reference Fields”](https://www.drupal.org/docs/user_guide/en/structure-reference-fields.html " Reference Fields") for more information.

## Region

A defined area of a page where [content](#content) can be placed, such as the header, footer, main content area, left sidebar, etc. Regions are defined by [themes](#theme), and the content displayed in each region is contained in [blocks](#block). See [Section 2.1, “Concept: Regions in a Theme”](https://www.drupal.org/docs/user_guide/en/block-regions.html " Regions in a Theme") for more information.

## Responsive

A site or [theme](#theme) is said to be responsive if it adjusts its presentation in response to the size of the browser screen, printer, or other media output type. See also [Breakpoint](#breakpoint). See [Section 6.14, “Concept: Responsive Image Styles”](https://www.drupal.org/docs/user_guide/en/structure-image-responsive.html " Responsive Image Styles") for more information.

## Revision

A record of the past or present state of a [content](#content) [entity](#entity), as it is edited over time. See [Section 2.6, “Concept: Editorial Workflow”](https://www.drupal.org/docs/user_guide/en/planning-workflow.html " Editorial Workflow") for more information.

## Role

A named set of [permissions](#permission) that can be applied to a [user account](#user). See [Section 7.1, “Concept: Users, Roles, and Permissions”](user-roles-permissions.md) for more information.

## Security update

An [update](#update) that fixes a security-related bug, such as a hacking vulnerability. See [Section 13.3, “Concept: Security and Regular Updates”](https://www.drupal.org/docs/user_guide/en/security-concept.html " Security and Regular Updates") for more information.

## State

Information of a temporary nature about the current state of your site, such as the time when [cron](#cron) was last run, etc. See also [Content](#content) and [Configuration](#configuration). See [Section 1.5, “Concept: Types of Data”](https://www.drupal.org/docs/user_guide/en/understanding-data.html " Types of Data") for more information.

## Taxonomy

The process of classifying [content](#content). See [Section 6.5, “Concept: Taxonomy”](https://www.drupal.org/docs/user_guide/en/structure-taxonomy.html " Taxonomy") for more information.

## Taxonomy term

A term used to classify [content](#content), such as a tag or a category. See also [Vocabulary](#vocabulary). See [Section 6.5, “Concept: Taxonomy”](https://www.drupal.org/docs/user_guide/en/structure-taxonomy.html " Taxonomy") for more information.

## Text format

[Configuration](#configuration) that defines the processing that happens to user-entered text before it is shown in the browser. This might include stripping or limiting HTML tags, or turning URLs into links. See [Section 6.15, “Concept: Text Formats and Editors”](https://www.drupal.org/docs/user_guide/en/structure-text-formats.html " Text Formats and Editors") for more information.

## Theme

Software and asset files (images, CSS, PHP code, and/or templates) that determine the style and layout of the site. The Drupal project distinguishes between _[core](#drupal-core)_ and _[contributed](#contributed)_ themes. See [Section 1.3, “Concept: Themes”](https://www.drupal.org/docs/user_guide/en/understanding-themes.html " Themes") for more information.

## UI

Acronym for [_User Interface_](#user-interface).

## Update

A newer version of your site’s software, either [Drupal core](#drupal-core) or a [module](#module) or [theme](#theme). See also [Security update](#security-update). See [Section 13.3, “Concept: Security and Regular Updates”](https://www.drupal.org/docs/user_guide/en/security-concept.html " Security and Regular Updates") for more information.

## User

A person interacting with the site, either logged-in or [anonymous](#anonymous). See [Section 7.1, “Concept: Users, Roles, and Permissions”](user-roles-permissions.md) for more information.

## User interface

The text, styles, and images that are visible on a site, separated logically into the user interface for site visitors and the administrative user interface.

## User one (User 1)

The initial [user](#user) account that is created when you install the site (whose ID number is 1). It automatically has all [permissions](#permission), even if it is not assigned an administrative [role](#role). See [Section 7.2, “Concept: The User 1 Account”](https://www.drupal.org/docs/user_guide/en/user-admin-account.html " The User 1 Account") for more information.

## View

A formatted listing of data; typically, the data comes from [content](#content) [entities](#entity). For example, on a farmers market site, you might create a [content item](#content-item) for each vendor. You could then make view that generates a listing page that shows a thumbnail image and short description of each vendor, linking to the full-page content item. Using the same data, you could also make a view that generates a new vendors block, which would show information from the most recently added vendors. See [Section 2.4, “Concept: Modular Content”](https://www.drupal.org/docs/user_guide/en/planning-modular.html " Modular Content") for more information.

## View mode

A set of [field formatter](#field-formatter) [configuration](#configuration) for all of the [fields](#field) of a [content](#content) [entity](#entity), some of which may be hidden. Each [entity subtype](#entity-subtype) can have one or more view modes defined; for example, [content types](#content-type) typically have _Full_ and _Teaser_ view modes, where the _Teaser_ view mode displays fewer or trimmed-down fields. It is possible to create custom view modes but only use them on the desired [content types](#content-type). See [Section 6.10, “Concept: View Modes and Formatters”](https://www.drupal.org/docs/user_guide/en/structure-view-modes.html " View Modes and Formatters") for more information.

## Vocabulary

A group of [taxonomy terms](#taxonomy-term) to choose from when classifying [content](#content) in a particular way, such as the list of all of the vendor categories on a farmers market site. Technically, vocabularies are the [entity subtype](#entity-subtype) for the taxonomy term [entity type](#entity-type). See [Section 6.5, “Concept: Taxonomy”](https://www.drupal.org/docs/user_guide/en/structure-taxonomy.html " Taxonomy") for more information.

## Widget

See [Field widget](#field-widget).

## Wizard

A web form that allows you to fill in a few values, and creates something with sensible defaults based on the values you chose. For example, there are wizards for creating [views](#view) of different types. See [Section 9.3, “Creating a Content List View”](https://www.drupal.org/docs/user_guide/en/views-create.html "9.3. Creating a Content List View") for more information.

## WYSIWYG

Acronym for _What You See is What You Get_, meaning a method for editing [content](#content) where what you see on the editing screen closely resembles the final product. See [Section 6.16, “Configuring Text Formats and Editors”](https://www.drupal.org/docs/user_guide/en/structure-text-format-config.html "6.16. Configuring Text Formats and Editors") for more information.