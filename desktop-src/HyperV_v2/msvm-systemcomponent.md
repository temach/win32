---
Description: 'Establishes a &\#0034;part of&\#0034; relationship between a system and any managed system element of which it is composed.'
ms.assetid: '6BF72E36-9B6C-4853-A553-DDAF65991C86'
title: 'Msvm\_SystemComponent class'
---

# Msvm\_SystemComponent class

Establishes a "part of" relationship between a system and any managed system element of which it is composed.

The following syntax is simplified Managed Object Format (MOF) code, and it includes all of the inherited properties.

## Syntax

``` syntax
[Dynamic, Provider("VmmsWmiInstanceAndMethodProvider"), Association, Aggregation]
class Msvm_SystemComponent : CIM_SystemComponent
{
  CIM_System�������������� REF GroupComponent;
  CIM_ManagedSystemElement REF PartComponent;
};
```

## Members

The **Msvm\_SystemComponent** class has these types of members:

-   [Properties](#properties)

### Properties

The **Msvm\_SystemComponent** class has these properties.

<dl> <dt>

**GroupComponent**
</dt> <dd> <dl> <dt>

Data type: **[**CIM\_System**](https://msdn.microsoft.com/library/aa388503)**
</dt> <dt>

Access type: Read-only
</dt> </dl>

The parent element in the association. This property is inherited from [**CIM\_SystemComponent**](https://msdn.microsoft.com/library/aa388506).

</dd> <dt>

**PartComponent**
</dt> <dd> <dl> <dt>

Data type: **[**CIM\_ManagedSystemElement**](https://msdn.microsoft.com/library/aa387898)**
</dt> <dt>

Access type: Read-only
</dt> </dl>

The child element in the association. This property is inherited from [**CIM\_SystemComponent**](https://msdn.microsoft.com/library/aa388506).

</dd> </dl>

## Requirements



|                                     |                                                                                                         |
|-------------------------------------|---------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�8.1 \[desktop apps only\]<br/>                                                            |
| Minimum supported server<br/> | Windows Server�2012�R2 \[desktop apps only\]<br/>                                                 |
| Namespace<br/>                | Root\\Virtualization\\V2<br/>                                                                     |
| MOF<br/>                      | <dl> <dt>WindowsVirtualization.V2.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>Vmms.exe</dt> </dl>                     |



�

�



