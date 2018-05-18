---
title: Configuring Text Streams
description: Configuring Text Streams
ms.assetid: 'd99baac5-69e5-4e0a-9cd6-35b288d8181a'
keywords: ["streams,configuring text streams", "codecs,configuring text streams", "text streams,configuring"]
---

# Configuring Text Streams

Text streams are essentially the same as custom arbitrary streams. There is no configuration information associated with a text stream to identify the type of text encoding, so the writer object cannot verify samples.

To configure a text stream, you must ensure that the [**WM\_MEDIA\_TYPE**](wm-media-type.md) structure contains a major media type of WMMEDIATYPE\_TEXT. You must also set a bit rate and buffer window for the stream.

## Related topics

<dl> <dt>

[**Calculating Bit Rate and Buffer Window Values for Arbitrary Streams**](calculating-bit-rate-and-buffer-window-values-for-arbitrary-streams.md)
</dt> <dt>

[**Configuration Common to All Streams**](configuration-common-to-all-streams.md)
</dt> <dt>

[**Configuring Arbitrary Stream Types**](configuring-arbitrary-stream-types.md)
</dt> <dt>

[**Text Streams**](text-streams.md)
</dt> </dl>

 

 



