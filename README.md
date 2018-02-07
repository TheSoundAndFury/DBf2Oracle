# dbf2Oracle

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b8064cbaa6754ce4b945c7b83c551369)](https://www.codacy.com/app/TheSoundAndFury/DBf2Oracle?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=TheSoundAndFury/DBf2Oracle&amp;utm_campaign=Badge_Grade)
[![Dependency Status](https://www.versioneye.com/user/projects/58b74d1a9fd69a003e8d2c5a/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/58b74d1a9fd69a003e8d2c5a)

DBF 2 Oracle is small command line tool for converting DBF files top MySQL dump format. Based on dbf2SQL by xmovrave2 https://github.com/xmorave2/dbf2sql.git

# Installation

1. Clone repository: <code>git clone https://github.com/TheSoundAndFury/DBf2Oracle.git</code>

2. Install php and composer (https://getcomposer.org/doc/00-intro.md#installation-linux-unix-osx)

3. Install libraries: <code>composer install</code>

# Use

<code>php dbf2sql.php [-e encoding] [-b batchsize] [-d destinationdir] list_of_dbf_files</code>

Example: 

<code>php dbf2sql.php -e CP1250 books.dbf authors.dbf</code>

