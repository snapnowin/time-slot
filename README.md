
# Time Slot Package

This package provides the time slot functionality for a Laravel application.

## Installation

1. Add the package to your Laravel project using Composer.

2. Publish the package assets.

3. Run the migrations to create the necessary database tables.

### Step 1: Add the Package

Add the package to your Laravel project's `composer.json` file.

```json
{
    "require": {
        "snapnowin/time-slot-package": "dev-master"
    }
}
```

Run `composer update` to install the package.

### Step 2: Publish the Package Assets

Publish the package assets using the following command:

```bash
php artisan vendor:publish --provider="App\Providers\TimeSlotServiceProvider"
```

### Step 3: Run the Migrations

Run the migrations to create the necessary database tables:

```bash
php artisan migrate
```

### Running Seeders

If you need to run the seeders provided by the package, use the following command:

```bash
php artisan db:seed --class=DatabaseSeeder
```

## Usage

Include instructions on how to use the package in your application.
