# Bilder hochladen

wgGallery unterstützt den Multifile-Upload. Das Uploadtool führt neben dem normalen Uploadvorgang auch noch zusätzliche Aufgaben aus.

### Schritte für das Hochladen

* Wählen Sie das gewünschte Album aus. Danach erscheint der Uploadbereich

![](../../.gitbook/assets/upload1.png)

* Wählen Sie Ihre Bilddateien über den Explorer aus \(Klick auf "Dateien auswählen"\) oder ziehen Sie diese mit Drag&Drop in die Drop-Zonee. 
![](../../.gitbook/assets/important.png) Achtung: seitens wgGallery besteht kein Limit, wieviele Dateien Sie auf einmal hochladen können, aber wahrscheinlich sind Sie durch Ihr Webseitensystem \(PHP-Einstellungen\) limitiert. Sie können Ihre Einstellungen unter Wartung [Systemcheck](../administration-menu/maintenance/system-check.md) überprüfen.

* Nach dem Hinzufügen der Dateien in die Uploadliste überprüft wgGallery, ob die Dateien die Voraussetzungen erfüllen:

  * Ist die maximale Dateigröße überschritten?
  * Werden die maximal erlaubten Bilddimensionen \(Breite oder Höhe\) überschritten?

  ![](../../.gitbook/assets/important.png) Sie können die Einstellungen betreffend der erlaubten Gößen unter [Optionen für bildupload](../preferences/options-for-image-upload.md) ändern.

* If all files fullfill the conditions this will be confirmed ![](../../.gitbook/assets/upload2.png)
* wgGallery takes the file name as default for image title. if you want to change you can click on the suggested title or on the pen and change as you want  ![](../../.gitbook/assets/upload3.png) 
* Start upload
* Processes during upload
  * Storing original image \(if selected in preferences [Options for image upload](../preferences/options-for-image-upload.md)\)
  * Resizing image corresponding settings in preferences [Options for image upload](../preferences/options-for-image-upload.md)
  * Adding watermark, if a watermark is linked with current album \(see [Albums](../administration-menu/albums.md) and [Watermarks](../administration-menu/watermarks.md)\)
  * saving different types \(large, medium, thumb\) of images in upload directory
  * reading information of image
    * size
    * dimension
    * mime type
    * EXIF \(only if option in preferences [Options for image processing](../preferences/options-for-image-processing.md)
* After successful upload each line gets a green backgound and the upload tools confirm success  ![](../../.gitbook/assets/upload4.png) 

## Next steps

After uploading the images you can goto

* [Image index](image-upload.md) in order to check all images
* [Image management](image-management.md) in order to check/change sorting of images
* [Album image](album-image.md) in order to select an image as album image

