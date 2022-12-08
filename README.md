# CS305_Module5

## Introduction

The Administration Menu module displays the entire administrative menu tree
(and most local tasks) in a drop-down menu, providing administrators one- or
two-click access to most pages.  Other modules may also add menu links to the
menu using `hook_admin_menu_output_alter()`.

- For a full description of the module, visit the
  [project page](https://www.drupal.org/project/admin_menu).
- Submit bug reports and feature suggestions, or track changes in the
  [issue queue](https://www.drupal.org/project/issues/admin_menu).
  
## Requirements

This module requires the following modules:

- [Views](https://www.drupal.org/project/views)
- [Panels](https://www.drupal.org/project/panels)

## Recommended modules

[Markdown filter](https://www.drupal.org/project/markdown): When enabled,
display of the project's README.md help will be rendered with markdown.

## Installation

Install as you would normally install a contributed Drupal module. For further
information, see
[Installing Drupal Modules](https://www.drupal.org/docs/extending-drupal/installing-drupal-modules).

## Configuration

The module has no menu or modifiable settings. There is no configuration. When
enabled, the module will prevent the links from appearing. To get the links
back, disable the module and clear caches.
