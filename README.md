# CakePHP 3 Wizard Plugin

The Wizard plugin for CakePHP automates several aspects of multi-page forms including data persistence, form preparation and unique data processing, wizard resetting (manual and automatic), user navigation, and plot-branching navigation while maintaining flexibility with custom validation and completion callbacks.  
  
This fork makes this plugin available for CakepPHP 3. There might still be some bugs here and there related to migration, but this works for us.

## Installation

### Clone and copy
* Clone/Copy the files in this directory into `app/plugins/wizard`
* Include the wizard component in your controller:
   * `public $components = array('Wizard.Wizard');`
   
### Add to composer
You can run this through composer using the following snippet.

```
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com/bordplate/cakephp-wizard"
    }
  ],
  "require": {
    "bordplate/cakephp-wizard": "dev-master"
  }
```

## Documentation

Detailed documentation, including usage examples, can be found in the [GitHub wiki](http://github.com/jaredhoyt/cakephp-wizard/wiki).
