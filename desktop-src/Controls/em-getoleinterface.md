---
title: EM\_GETOLEINTERFACE message
description: Retrieves an IRichEditOle object that a client can use to access a rich edit control's Component Object Model (COM) functionality.
ms.assetid: 'fa462c7b-29b9-4694-b7ad-6068c69ffb76'
keywords: ["EM_GETOLEINTERFACE message Windows Controls"]
topic_type:
- apiref
api_name:
- EM_GETOLEINTERFACE
api_location:
- Richedit.h
api_type:
- HeaderDef
---

# EM\_GETOLEINTERFACE message

Retrieves an [**IRichEditOle**](iricheditole.md) object that a client can use to access a rich edit control's Component Object Model (COM) functionality.

## Parameters

<dl> <dt>

*wParam* 
</dt> <dd>

This parameter is not used; it must be zero.

</dd> <dt>

*lParam* 
</dt> <dd>

Pointer to a pointer that receives the [**IRichEditOle**](iricheditole.md) object. The control calls the [**AddRef**](https://msdn.microsoft.com/library/windows/desktop/ms691379) method for the object before returning, so the calling application must call the [**Release**](https://msdn.microsoft.com/library/windows/desktop/ms682317) method when it is done with the object.

</dd> </dl>

## Return value

If the operation succeeds, the return value is a nonzero value.

If the operation fails, the return value is zero.

## Requirements



|                                     |                                                                                       |
|-------------------------------------|---------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�Vista \[desktop apps only\]<br/>                                        |
| Minimum supported server<br/> | Windows Server�2003 \[desktop apps only\]<br/>                                  |
| Header<br/>                   | <dl> <dt>Richedit.h</dt> </dl> |



## See also

<dl> <dt>

[**IRichEditOle**](iricheditole.md)
</dt> </dl>

�

�




