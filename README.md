# fontsdb

The **fontsdb** package is meant to be used with the **fonts** package. The
fonts package contains the code to install and use fonts, while the fontsdb
package contains the directory structure to hold the fonts database.

These are separated into two packages because the each time that the package
containing the database is re-installed, the database gets deleted. By putting
the database in a separate package, it is possible to update the code package
without deleting the database and having to re-import the fonts.

See [https://github.com/wch/fonts](https://github.com/wch/fonts) for more
information.