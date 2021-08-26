[<< Previous](readme.md)
# Composer 
For Drupal 8 and Drupal 9, use the composer template at drupal/recommended-project. This template ensures Drupal Core dependencies are the exact same version as the official drupal release.

Composer is not a package manager in the same sense as Yum or Apt are. Yes, it deals with "packages" or libraries, but it manages them on a per-project basis, installing them in a directory (e.g. vendor) inside your project. By default, it does not install anything globally. Thus, it is a dependency manager for Drupal ([core](terminology.md#drupal-core)/[module](terminology.md#module)/[themes](terminology.md#theme)/[patches](terminology.md#patch)).

Geting started with composer:
```
composer create-project drupal/recommended-project my_site_name_dir
```