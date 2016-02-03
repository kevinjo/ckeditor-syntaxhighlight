# Introduction #
This is a brief install guide for the ckeditor syntaxhighlight plugin. Beyond copying the plugin directory into your ckeditor installation, help on the rest can be located in the ckeditor documentation.

# Steps #

  1. Checkout or download the ckeditor-syntaxhighlight source
  1. Copy the plugins/syntaxhighlight directory into your ckeditor install directory under plugins
  1. Update your ckeditor configuration to use this plugin
```
config.extraPlugins = 'syntaxhighlight';
config.toolbar_Full.push(['Code']);
```
  1. Celebrate