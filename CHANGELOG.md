## 1.2.0+1

* Cache video duration for fast retrieval on iOS

## 1.2.0

iOS
* Return video `duration` with `getMediaFile`
* Duration can also be returned with `getAlbums` if the argument `loadIOSPath` is true

Android
* Return video `duration` and `mimeType` of files with `getMediaFile` and getAlbums

## 1.1.1

* On iOS, fix crash when retrieving albums

## 1.1.0+1

* Added a new api to get media file based on file id
* For iOS only, new flag [loadIOSPaths] added to optimize the speed of querying the files.

## 1.0.0+2

* Remove meta dependency

## 1.0.0+1

* Update docs

## 1.0.0

* Initial release
