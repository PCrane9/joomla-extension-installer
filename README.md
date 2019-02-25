# joomla-extension-installer

cd /path/to/site/cli php ./install-joomla-extension.php --package=/where/is/your/extension.zip

The script returns one of the following exit statuses:

    The extension was installed successfully.
    The package file was not found.
    The package file could not be extracted.
    The extension could not be installed. You can copy this file to your site's cli directory and install extensions and extension updates any time you want.
