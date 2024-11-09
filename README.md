
# PHP Sessions Extra

A PHP package to extend the functionality of native PHP sessions with additional features, making session management easier and more flexible.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Overview

The `php-sessions-extra` package provides additional functionality for PHP session management, helping developers manage session data more efficiently with enhanced customization options. This package is ideal for projects that need to handle sessions beyond the basic PHP capabilities.

## Features

- Enhanced session data handling
- Customizable session configurations
- Easy-to-use methods for common session operations

## Installation

To install `php-sessions-extra`, use the following steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Paola3stefania/php-sessions-extra.git
   ```

2. Include the package in your PHP project:

   ```php
   require_once 'path/to/php-sessions-extra/src/SessionManager.php';
   ```

## Usage

To start using the package, instantiate the `SessionManager` class and call the desired methods to interact with session data.

```php
use Paola3stefania\PhpSessionsExtra\SessionManager;

$session = new SessionManager();
$session->start();
$session->set('user_id', 123);
echo $session->get('user_id');
```

## Examples

Examples of session operations:

- **Start a session**: `$session->start();`
- **Set session data**: `$session->set('key', 'value');`
- **Retrieve session data**: `$value = $session->get('key');`
- **Destroy a session**: `$session->destroy();`

## Configuration

Configuration options allow you to customize session parameters. Refer to the documentation in `docs/configuration.md` for more details.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to get started.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

