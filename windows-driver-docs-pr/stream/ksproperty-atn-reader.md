---
title: KSPROPERTY\_ATN\_READER
description: The KSPROPERTY\_ATN\_READER property retrieves the absolute track number (ATN) of the current tape position.
ms.assetid: ac127aa0-5a47-41b2-9a2d-96090231d43e
keywords: ["KSPROPERTY_ATN_READER Streaming Media Devices"]
topic_type:
- apiref
api_name:
- KSPROPERTY_ATN_READER
api_location:
- ksmedia.h
api_type:
- HeaderDef
ms.date: 11/28/2017
ms.localizationpriority: medium
---

# KSPROPERTY\_ATN\_READER


The KSPROPERTY\_ATN\_READER property retrieves the absolute track number (ATN) of the current tape position.

## <span id="ddk_ksproperty_atn_reader_ks"></span><span id="DDK_KSPROPERTY_ATN_READER_KS"></span>


### Usage Summary Table

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>Get</th>
<th>Set</th>
<th>Target</th>
<th>Property descriptor type</th>
<th>Property value type</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>Device</p></td>
<td><p>[<strong>KSPROPERTY_TIMECODE_S</strong>](https://msdn.microsoft.com/library/windows/hardware/ff565781)</p></td>
<td><p>[<strong>TIMECODE_SAMPLE</strong>](https://msdn.microsoft.com/library/windows/hardware/ff568528)</p></td>
</tr>
</tbody>
</table>

 

The property value (operation data) is a TIMECODE\_SAMPLE structure that specifies the absolute track number of the current tape position.

Remarks
-------

The **TimecodeSamp** member of the KSPROPERTY\_TIMECODE\_S structure describes the absolute track number of the current tape position.

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Header</p></td>
<td>Ksmedia.h (include Ksmedia.h)</td>
</tr>
</tbody>
</table>

## See also


[**KSPROPERTY**](https://docs.microsoft.com/windows-hardware/drivers/ddi/content/ks/ns-ks-ksidentifier)

[**KSPROPERTY\_TIMECODE\_S**](https://msdn.microsoft.com/library/windows/hardware/ff565781)

[**TIMECODE\_SAMPLE**](https://msdn.microsoft.com/library/windows/hardware/ff568528)

 

 






