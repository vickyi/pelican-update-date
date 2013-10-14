# Update Date plugin

## Introduction

This is a simple pelican plugin which can

1. use the value of `update' metadata as update date
2. use filesystem's mtime value as update date if the `update' metadata is not defined
 
New variables:

* article.updatedate
* page.updatedate

Settings:

* UPDATEDATE_MODE
    * metadata: do not use filesystem's mtime even if the `update' metadata is not defined

## License
BSD license, see LICENSE.txt for more details.

