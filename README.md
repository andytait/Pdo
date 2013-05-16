# PDO Wrapper

A PDO wrapper to provide developer related information. Currently only has enough support for my current uses. Advisable only to use when in development mode, and to swap out with native PDO later.

# Features

- Provides a query count
- Provides a query log (full query strings, bound parameters replaced)

# Installation

Add to your composer.json file

	{
		"require": {
			"centralapps/pdo": "dev-master"
		}
	}

Install via composer

	php composer.phar install

# Usage

Use in place of the PDO class

	$pdo = new \CentralApps\Pdo\Pdo(....