# Silverstripe Elemental Base Site

Content blocks commonly used with [dynamic/silverstripe-base-site](https://github.com/dynamic/silverstripe-base-site)

[![Latest Stable Version](https://poser.pugx.org/dynamic/recipe-silverstripe-elemental-base-site/v/stable)](https://packagist.org/packages/dynamic/recipe-silverstripe-elemental-base-site)
[![Total Downloads](https://poser.pugx.org/dynamic/recipe-silverstripe-elemental-base-site/downloads)](https://packagist.org/packages/dynamic/recipe-silverstripe-elemental-base-site)
[![Latest Unstable Version](https://poser.pugx.org/dynamic/recipe-silverstripe-elemental-base-site/v/unstable)](https://packagist.org/packages/dynamic/recipe-silverstripe-elemental-base-site)
[![License](https://poser.pugx.org/dynamic/recipe-silverstripe-elemental-base-site/license)](https://packagist.org/packages/dynamic/recipe-silverstripe-elemental-base-site)


## Requirements

* [dynamic/silverstripe-elemental-blog](https://github.com/dynamic/silverstripe-elemental-blog) ^2.0
* [dynamic/silverstripe-elemental-embedded-code](https://github.com/dynamic/silverstripe-elemental-embedded-code) ^2.0
* [dynamic/silverstripe-elemental-features](https://github.com/dynamic/silverstripe-elemental-features) ^3.0
* [dynamic/silverstripe-elemental-filelist](https://github.com/dynamic/silverstripe-elemental-filelist) ^2.0
* [dynamic/silverstripe-elemental-flexslider](https://github.com/dynamic/silverstripe-elemental-flexslider) ^2.0
* [dynamic/silverstripe-elemental-image](https://github.com/dynamic/silverstripe-elemental-image) ^2.0
* [dynamic/silverstripe-elemental-oembed](https://github.com/dynamic/silverstripe-elemental-oembed) ^2.0
* [dynamic/silverstripe-elemental-promos](https://github.com/dynamic/silverstripe-elemental-promos) ^3.0

## Installation

```
composer require dynamic/recipe-silverstripe-elemental-base-site
```

## License
See [License](license.md)

## Upgrading from version 1

Recipe Silverstripe Elemental Base Site drops `sheadawson/silverstripe-linkable` usage in favor of `gorriecoe/silverstripe-linkfield`. To avoid data loss, install the `dynamic/silverstripe-link-migrator` module as follows:

```markdown
composer require dynamic/silverstripe-link-migrator
```

Then, run the task "Linkable to SilverStripe Link Migration" via `/dev/tasks`, or cli via:
```markdown
vendor/bin/sake dev/tasks/LinkableMigrationTask
```

This will populate all of the new Link fields with data from the old class.

## Getting more elements

See [Elemental modules by Dynamic](https://github.com/orgs/dynamic/repositories?q=elemental&type=all&language=&sort=)

## Configuration

See [SilverStripe Elemental Configuration](https://github.com/dnadesign/silverstripe-elemental#configuration)


## Maintainers
 *  [Dynamic](https://www.dynamicagency.com) (<dev@dynamicagency.com>)

## Bugtracker
Bugs are tracked in the issues section of this repository. Before submitting an issue please read over
existing issues to ensure yours is unique.

If the issue does look like a new bug:

 - Create a new issue
 - Describe the steps required to reproduce your issue, and the expected outcome. Unit tests, screenshots
 and screencasts can help here.
 - Describe your environment as detailed as possible: SilverStripe version, Browser, PHP version,
 Operating System, any installed SilverStripe modules.

Please report security issues to the module maintainers directly. Please don't file security issues in the bugtracker.

## Development and contribution
If you would like to make contributions to the module please ensure you raise a pull request and discuss with the module maintainers.
