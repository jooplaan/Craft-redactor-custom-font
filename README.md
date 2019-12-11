# Craft - Redactor custom font plugin - Craft 3


This plugin adds the ability to use your own font file with icons in Redactor in your CP panel. To use this plugin you also need the free [Redactor](https://github.com/craftcms/redactor) plugin. To generate a font file, you could a service like [Fontello](http://fontello.com/).

## Download & Installation

Use Composer to download and install the plugin.

1. Open your terminal and go to your Craft project:

```
cd /path/to/project
```

2. Then tell Composer to load the plugin:

```
composer require jooplaan/craft-redactor-custom-font
```

3. Include the Custom font plugin in your Redactor config file located in `craft/config/redactor/-your-config-file-.json`. To do so, add `customFont` in the plugins array.

4. In the Control Panel, go to Settings → Plugins and click the “Install” button for Redactor Custom font.

**NOTE:** Don't forget to include your font on your front-end.


## Changelog

See [CHANGELOG.md](https://github.com/jooplaan/Craft-redactor-custom-font/blob/master/CHANGELOG.md).