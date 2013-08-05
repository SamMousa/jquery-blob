jquery-blob
===========

Blob support for jQuery ajax.

This file is a modified version from https://github.com/jquery/jquery/blob/master/src/ajax/xhr.js

When using the blob as dataType argument for the .ajax call (and probably the other AJAX functions) the complete callback will contain the Blob.

Can be used in combination with the FileSaver interface to download files via AJAX.
