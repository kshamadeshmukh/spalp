# Single Page App Landing Page module for Drupal

This module provides a way for site managers to configure and serve single-page applications as pages in a Drupal site.

This approach has been described as “Progressively Decoupled” - see https://dri.es/how-to-decouple-drupal-in-2018

The module defines an App Landing Page content type.

The standard view mode for these nodes would be the landing page for each app.

A separate view mode would provide a JSON endpoint for configuration and text, to be consumed by the app.

All relevant configuration would be stored on this node.


TODO: define app element ID to be replaced by JS

## Extending the module
Create a module that implements `hook_spalp_app_ids`.

Default configuration and application text should be stored in mymodule.config.json

The spalp_example module shows how this can be done. 
