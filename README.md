# NuguCall Android

Android client for NuguCall, a call connection application based on multimodal interaction. The application was demonstrated at the ITRC Forum.

## Related repository

- [NuguCall Server](https://github.com/SamoSpri/NUGUCALLSERVER)

## Source layout

- [AndroidManifest.xml](AndroidManifest.xml) declares application components.
- [CallReceiver.java](CallReceiver.java) and [BackgroundService.java](BackgroundService.java) cover call handling and background operation.
- [ContentsActivity.java](ContentsActivity.java) and [PreviewActivity.java](PreviewActivity.java) contain the content and preview screens.
- [ContentsFileUpload.java](ContentsFileUpload.java) and [ContentsFileDownload.java](ContentsFileDownload.java) contain file transfer logic.

The repository contains Java sources and Android resources. Building an APK requires an Android project configuration and a compatible server setup.
