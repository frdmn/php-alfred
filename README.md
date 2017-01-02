# php-alfred

Forked from @[jdfwarrior/Workflows](https://github.com/jdfwarrior/Workflows) to create a [Packagist/Composer package](https://packagist.org/packages/frdmn/php-alfred).

See [dferg.us](http://dferg.us/workflows-class) for full class documentation.

## Usage

```php
<?php
require __DIR__ . '/vendor/autoload.php';

// Create new workflow instance
$alfred = new \frdmn\PhpAlfred\Workflows();

// Construct array with workflow data
$array = [
    [
      'uid'   => 0,
      'arg'   => 'test',
      'title' => 'Title'
    ]
];

// Print XML
print $alfred->toXML($array);
```

## Installation

1. Install using Composer:  
  `composer require frdmn/php-alfred`

## Contributing

1. Fork it
2. Create your feature branch: `git checkout -b feature/my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/my-new-feature`
5. Submit a pull request

## Requirements / Dependencies

* PHP >= 5.3
* Composer

## Version

0.3.6
