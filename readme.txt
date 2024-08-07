1. download and install "all in one migration 6.7 " plugin.
2. click "plugin file editor"
3. select "All in one migration " plugin
4. click "constants.php"
5. click "ctrl + F" and type "Max File Size"
6. replace "define( 'AI1WM_MAX_FILE_SIZE', 2 << 28 );" to "define( 'AI1WM_MAX_FILE_SIZE', 10737418240 );"  type this number according byte this number is 10GB
7.click "Update file"
8. check "Maximum upload file size"