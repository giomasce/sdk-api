---
UID: NE:strmif.tagDVD_SUBPICTURE_CODING
title: DVD_SUBPICTURE_CODING (strmif.h)
description: Indicates what kind of content the subpicture stream contains.
helpviewer_keywords: ["DVD_SPCoding_Extended","DVD_SPCoding_Other","DVD_SPCoding_RunLength","DVD_SUBPICTURE_CODING","DVD_SUBPICTURE_CODING","DVD_SUBPICTURE_CODING enumeration [DirectShow]","DVD_SUBPICTURE_CODINGEnumeration","dshow.dvd_subpicture_coding","strmif/DVD_SPCoding_Extended","strmif/DVD_SPCoding_Other","strmif/DVD_SPCoding_RunLength","strmif/DVD_SUBPICTURE_CODING"]
old-location: dshow\dvd_subpicture_coding.htm
tech.root: dshow
ms.assetid: 46f45dfb-9be7-4222-b6fb-ea95b60323cd
ms.date: 4/26/2023
ms.keywords: DVD_SPCoding_Extended, DVD_SPCoding_Other, DVD_SPCoding_RunLength, DVD_SUBPICTURE_CODING, DVD_SUBPICTURE_CODING , DVD_SUBPICTURE_CODING enumeration [DirectShow], DVD_SUBPICTURE_CODINGEnumeration, dshow.dvd_subpicture_coding, strmif/DVD_SPCoding_Extended, strmif/DVD_SPCoding_Other, strmif/DVD_SPCoding_RunLength, strmif/DVD_SUBPICTURE_CODING
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: DVD_SUBPICTURE_CODING
req.redist: 
ms.custom: 19H1
f1_keywords:
 - tagDVD_SUBPICTURE_CODING
 - strmif/tagDVD_SUBPICTURE_CODING
 - DVD_SUBPICTURE_CODING
 - strmif/DVD_SUBPICTURE_CODING
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - strmif.h
api_name:
 - DVD_SUBPICTURE_CODING
---

# DVD_SUBPICTURE_CODING enumeration


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

Indicates what kind of content the subpicture stream contains.

## -enum-fields

### -field DVD_SPCoding_RunLength:0

Indicates that the subpicture uses run length encoding.

### -field DVD_SPCoding_Extended:1

Indicates that subpicture uses extended encoding.

### -field DVD_SPCoding_Other:2

Indicates that the subpicture uses some other encoding scheme.

## -remarks

Most subpicture streams contain language-related content such as movie subtitles, but subpictures can also be used for the bouncing ball in karaoke or other non-language-related purposes.

## -see-also

[DVD_SubpictureAttributes](/windows/desktop/api/strmif/ns-strmif-dvd_subpictureattributes)



<a href="/windows/desktop/DirectShow/directshow-enumerated-types">DirectShow Enumerated Types</a>
