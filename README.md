# PHPVersion

The PHPVersion is a tool to change the PHP version that is currently in use.

Currently this project can run only on **Windows** environments (with [MinGW](http://www.mingw.org/)), because to perform this task in other operating systems such as Linux and OSX there is already a solution.

Well, to use this tool you must clone this repository:

```bash
git clone https://github.com/jpcercal/php-version.git
```

Now, put the following (where the project was cloned) directories on the environment variable `PATH` of your system.

- yourdrive:/root/directory/of/this/project/bin/
- yourdrive:/root/directory/of/this/project/current-release/

When you complete this steps, then run on your terminal the command `php-version` to see the help about how to use this application.

## Download PHP releases

To this application works, you must create a directory named `releases` and put in it the releases downloaded from [http://windows.php.net/downloads/releases/archives/](http://windows.php.net/downloads/releases/archives/).

For example, you may download a PHP 7.0.0 from php.net [http://windows.php.net/downloads/releases/archives/php-7.0.0-nts-Win32-VC14-x64.zip](http://windows.php.net/downloads/releases/archives/php-7.0.0-nts-Win32-VC14-x64.zip) and unzip on `releases` directory as `7.0.0`.

Notes:

1. To install any version you need following this steps.
2. You must install the [7z](http://www.7-zip.org/) and put it on your environment variable `PATH`.

## Documentation

To list all releases that are available to use you can type this command on terminal:

```bash
php-version releases
```

And to use a different release type the following command on terminal:

```bash
php-version use 7.0.0
```

Contributing
------------

1. Give me a star **=)**
2. Fork it
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Make your changes
5. Commit your changes (`git commit -am 'Added some feature'`)
6. Push to the branch (`git push origin my-new-feature`)
7. Create new Pull Request
