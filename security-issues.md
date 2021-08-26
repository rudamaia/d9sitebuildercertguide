[<< Previous](readme.md)
# Security Issues
The scenario for a security issue can be really vast from a developers perspective. That said, the security issue that **ACQUIA CERTIFIED SITE BUILDER (D9)** certification is asking for, are probably the most simple kinds of security issues.

## Permissions
Permisions can be a security issue if miss managed. If a Site Administrator inadvertently gives the 'content administration' or 'user administration' permission to the [Anonymous](terminology.md#anonymous) role that means that any [_not logged in user_](terminology.md#anonymous) can create, edit, or delete, the site's [content](terminology.md#content) and [users](terminology.md#user)

_This is a miss use case and maybe it is not what the certification will be asking for, but, it's better to know that Site Administration can cause security issues if they don't know what they are doing._

## Core and Modules update
The Drupal core and Modules could pose as a security issue when outdated, so, it is importante for the security of a project to constantly update the core and contrib modules.

## Patches
Usually the community create patches to fix issues discovered by the community, because it is a lot faster to share a patch fix than it is to release new version of a module, or, a new drupal version.

It is possible to apply those patches in your project using [composer](composer.md).

## File/Folder permissions
Last but not least, it is importante to have the correct permissioning in the drupal file system structure.
[Drupal recommended file and directory permissions](https://drupal.guru/drupal-recommended-file-and-directory-permissions/)