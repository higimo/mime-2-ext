# higimo/mime-2-ext
Converter mime type to extension

```php
<?php
	$file = file_get_contents('./file.otf');
	\Higimo\Mime2Ext::getMime($file); // 'application/vnd.ms-opentype'
	\Higimo\Mime2Ext::getExt($file); // otf
	\Higimo\Mime2Ext::getExtByFile($file); // otf
	\Higimo\Mime2Ext::getExtByMime('application/vnd.ms-opentype'); // otf
	\Higimo\Mime2Ext::get('application/vnd.ms-opentype'); // otf
```

## Install
```
composer.bat require higimo/mime-2-ext
```

## License
MIT