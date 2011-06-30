PHP Shell Detector
==================
PHP Shell Detector - is php script that help to detect or find any php shells.

PHP Shell Detector is released under the MIT License <http://www.opensource.org/licenses/mit-license.php>

Requirements
------------
PHP v5.x

Usage
-----
To activate PHP Shell Detector:

1) Upload to your root directory

2) Open this file in your browser

  http://www.website.com/shelldetect.php

3) Inspect all strange files, if some of files look suspicious, send them to us. If this file is a shell we will insert this file to our fingerprint database

4) If shells found and identified remove it (please be carefull because some of shells may be integrated into system files!).

Options
-------
extension - extensions that should be scanned

showlinenumbers - show line number where suspicious function used

dateformat - used with access time & modified time

langauge - if I want to use other language

directory - scan specific directory

task - perform different task

report_format - used with is_cron(true) file format for report file

is_cron - if true run like a cron(no output)

filelimit - maximum files to scan (more then 30000 you should scan specific directory)


Changelog
---------

 - 1.1 fingerprint function change
       show line regex changed

 - 1.0 first version