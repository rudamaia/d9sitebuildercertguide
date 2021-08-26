# ACQUIA CERTIFIED SITE BUILDER (D9) - Study Guide

### Introduction
- [introduction](introduction.md)

### Basic concepts (non certification)
- [composer](composer.md)
- [git](git.md)

# Certification Track
### 1 - Content
- 1.1 [Understanding Drupal and working with a Drupal Site](#understanding-drupal--working-with-a-drupal-site).

Demonstrate the ability to explain the distinct and differentiating features of Drupal and understanding [Drupal terminology](terminology.md)
- 1.2 Given an example of a page layout, determine what is [content](terminology.md#content-item) versus a [block](terminology.md#block)
- 1.3 Demonstrate an ability to troubleshoot problems related to [content](terminology.md#content-item), [configuration](terminology.md#configuration) and maintenance
  
### 2 - [Content Modeling](#content-modeling)

- 2.1 Demonstrate the ability to model [content](terminology.md#content-item) using [content types](terminology.md#content-type) and [vocabularies](terminology.md#taxonomy)
- 2.2 Demonstrate the ability to configure and manage [comment types](terminology.md#comment-type) and [comments](https://www.drupal.org/docs/8/core/modules/comment)
- 2.3 Demonstrate the ability to configure and manage [block types](terminology.md#block-type) and [blocks](terminology.md#block)
- 2.4 Demonstrate the ability to configure and manage [contact forms](terminology.md#contact)
-  2.5 Demonstrate the ability to configure and use [multilingual content](terminology.md#language) and [interface](terminology.md#language)
- 2.6 Demonstrate ability to configure and manage [menus](terminology.md#menu), [menu items](terminology.md#menu) and [menu blocks](terminology.md#block)
- 2.7 Demonstrate the ability to configure and use [Rich media](terminology.md#media) in content using [Media module](terminology.md#block)

### 3 - [Site Display](#site-display)

  - 3.1 Demonstrate the ability to control the display of content across various [regions](terminology.md#region) of the site using the [block system](terminology.md#block)

  - 3.2 Demonstrate the ability to provide different presentations of Content - Entities (like [Nodes](terminology.md#content-item), [Comments](https://www.drupal.org/docs/8/core/modules/comment), [User Profiles](https://www.drupal.org/docs/8/core/modules/user/overview), [Terms](terminology.md#taxonomy) etc) for [editing](terminology.md#form-mode) or [viewing](terminology.md#view-mode)

  - 3.3 Demonstrate the ability to create, manage and display lists of content using Drupal [Views](terminology.md#view)

- 3.4 Demonstrate the ability to build [layouts](terminology.md#layout) of content using [Layout Builder](terminology.md#layout)

### 4 - [Site Configuration](#site-configuration)

- 4.1 Demonstrate the ability to use the various options related to site configuration like account settings, content authoring, development, [search](https://www.drupal.org/docs/8/core/modules/search/overview), site and system settings, media 

- 4.2 Demonstrate the ability to use the [Configuration](terminology.md#configuration) and [Synchronization options to import, export, compare configuration across environments](https://www.drupal.org/docs/configuration-management/managing-your-sites-configuration)

- 4.3 Given a scenario, demonstrate the ability to configure [user accounts](terminology.md#user)

### 5 - [Contributed Modules and Themes management](#contributed-modules-and-themes-management)

- 5.1 Demonstrate the ability to add, update, and remove [_contributed_](terminology.md#contributed) [**modules**](terminology.md#module)

- 5.2 Demonstrate the ability to add, update, and remove [_contributed_](terminology.md#contributed) [**themes**](terminology.md#theme)

- 5.3 Identify ways of [_community_](https://www.drupal.org/community) [**participation**](https://www.drupal.org/community/contributor-guide) and [reporting issues](https://www.drupal.org/community/contributor-guide)

### 6 - [Security & Performance](#security--performance)

- 6.1 Identify [security issues](security-issues.md) resulting from site configuration

- 6.2 Identify [performance issues](performance-issues.md) resulting from site configuration

# Study
### Hypothetical questions
- What are the [Content Types](terminology.md#content-type) for the site?
- What are the [fields](terminology.md#field) and field settings for each [Content Type](terminology.md#content-type)?
- What are the [Displays](terminology.md#view-mode) configured for each [Content Type](terminology.md#content-type)? Are there any [Custom displays](terminology.md#view-mode)? If so, how and where are they used?
- What [Vocabularies](terminology.md#taxonomy) are defined? Are they controlled or uncontrolled? How is the [Taxonomy](terminology.md#taxonomy)  system used?
- How many [Custom blocks](terminology.md#block-type) are used on the site? Are there any Custom Block Types defined? Are there any [custom fields](terminology.md#block-type) in the blocks? [How are they used on the site](terminology.md#block-layout)?
- How many [Menus](terminology.md#menu) are defined? Are there any Custom Menus? How are the Menu items managed? Where are the Menus used on the site?
- List all the [Views](terminology.md#view) used on the site. For each View, check the Displays, Format, [Fields](terminology.md#field), Sort Criteria, - Filter Criteria, Contextual Filters and Relationships. Check how views are used on the site.
- List all the [Custom Modules](terminology.md#custom-module) enabled on the site. Check the functionality added by each module.
- Go to the Configuration Settings page of the site. Check the settings made under all the available options. Check the settings made under People, Content Authoring, Development, Search and Metadata, RSS - Publishing, System, Media, Regional and Language Settings.
- Go to Extend. Enable modules under Multilingual section. Check the different configuration options newly available under Language settings and Content type configurations. Play around with the settings to build a bi-lingual or a multilingual website.

### Understanding Drupal & Working with a Drupal Site
- [Understanding Drupal](https://www.drupal.org/docs/understanding-drupal)
- [Drupal Version Numbers](https://www.drupal.org/docs/understanding-drupal/understanding-drupal-version-numbers)
- [Drupal System Requirements](https://www.drupal.org/docs/system-requirements)
- [Drupal General Concepts](https://www.drupal.org/node/19828)
- [Administering a Drupal Site](https://www.drupal.org/docs/administering-a-drupal-site/getting-started-with-drupal-administration)
- [Managing Content on a Drupal Site](https://www.drupal.org/docs/administering-a-drupal-site/managing-content)

### Content modeling
- [Planning Data Types](https://www.drupal.org/docs/user_guide/en/planning-data-types.html)
- [Planning Content Structure](https://www.drupal.org/docs/user_guide/en/planning-structure.html)
- [Content Types](https://www.drupal.org/docs/user_guide/en/content-structure-chapter.html)
- [Blocks](https://www.drupal.org/docs/user_guide/en/block-concept.html)
- [Contact module documentation](https://www.drupal.org/documentation/modules/contact)
- [Drupal Multilingual Guide](https://www.drupal.org/docs/multilingual-guide)
- [Working with Menus](https://www.drupal.org/docs/user_guide/en/menu-concept.html)
- [Setting up Content Structure](https://www.drupal.org/docs/user_guide/en/content-structure-chapter.html)
- [Media Module](https://www.drupal.org/docs/8/core/modules/media)

### Site display
- [Views User Guide](https://www.drupal.org/docs/user_guide/en/views-chapter.html)
- [Working with Views](https://www.drupal.org/documentation/modules/views)
- [Working with blocks](https://www.drupal.org/docs/user_guide/en/blocks-chapter.html)
- [Layout Builder](https://www.drupal.org/docs/8/core/modules/layout-builder)

### Site configuration
- [Managing your site configuration](https://www.drupal.org/docs/configuration-management/managing-your-sites-configuration)
- [Managing User Accounts](https://www.drupal.org/docs/user_guide/en/user-chapter.html)

### Contributed Modules and Themes management
- [Finding and installing a contributed module](https://www.drupal.org/docs/extending-drupal/installing-modules)
- [Extending Drupal](https://www.drupal.org/docs/extending-drupal)
- [Installing themes](https://www.drupal.org/docs/extending-drupal/installing-themes)
- [Evaluating a contrib module](https://dev.acquia.com/blog/how-select-drupal-modules-part-3-evaluation-tips)
- [Ways of community contribution](https://www.drupal.org/contribute)
- [Reporting a problem](https://www.drupal.org/node/314185)

### Security & Performance
- [Secure configurations for Site Builders](https://www.drupal.org/docs/security-in-drupal/secure-configuration-for-site-builders)
- [Drupal Performance improvements](https://docs.acquia.com/acquia-cloud/performance/)

	https://docs.acquia.com/acquia-cloud/performance/#cloud-perf-drupal-core
___
The documentation content is mostly gathered from [Drupal.org](https://drupal.org) and ordered to make sense with the certification track.
___
The author: [Rudá Maia](https://www.drupal.org/u/rudam)
