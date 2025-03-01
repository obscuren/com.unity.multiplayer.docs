---  
id: MLAPI.NetworkVariable.NetworkVariableULong  
title: MLAPI.NetworkVariable.NetworkVariableULong
---

<div class="markdown level0 summary">

A NetworkVariable that holds ulongs and support serialization

</div>

<div class="markdown level0 conceptual">

</div>

<div class="inheritance">

##### Inheritance

<div class="level0">

System.Dynamic.ExpandoObject

</div>

<div class="level1">

System.Dynamic.ExpandoObject

</div>

<div class="level2">

System.Dynamic.ExpandoObject

</div>

</div>

<div classs="implements">

##### Implements

<div>

INetworkVariable

</div>

</div>

<div class="inheritedMembers">

##### Inherited Members

<div>

NetworkVariable&lt;UInt64&gt;.Settings"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.LocalTick"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.RemoteTick"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.OnValueChanged"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.Value"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.SetDirty(Boolean)"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.IsDirty()"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.ResetDirty()"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.CanClientRead(UInt64)"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.WriteDelta(Stream)"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.CanClientWrite(UInt64)"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.ReadDelta(Stream, Boolean, UInt16,
UInt16)"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.SetNetworkBehaviour(NetworkBehaviour)"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.ReadField(Stream, UInt16, UInt16)"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.WriteField(Stream)"

</div>

<div>

NetworkVariable&lt;UInt64&gt;.GetChannel()"

</div>

<div>

Object.Equals(Object)

</div>

<div>

Object.Equals(Object, Object)

</div>

<div>

Object.GetHashCode()

</div>

<div>

Object.GetType()

</div>

<div>

Object.MemberwiseClone()

</div>

<div>

Object.ReferenceEquals(Object, Object)

</div>

<div>

Object.ToString()

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: MLAPI.dll

##### Syntax

    [Serializable]
    public class NetworkVariableULong : NetworkVariable<ulong>, INetworkVariable

## Constructors 

### NetworkVariableULong()

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public NetworkVariableULong()

### NetworkVariableULong(NetworkVariableSettings)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public NetworkVariableULong(NetworkVariableSettings settings)

#### Parameters

| Type                    | Name     | Description |
|-------------------------|----------|-------------|
| NetworkVariableSettings | settings |             |

### NetworkVariableULong(NetworkVariableSettings, UInt64)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public NetworkVariableULong(NetworkVariableSettings settings, ulong value)

#### Parameters

| Type                    | Name     | Description |
|-------------------------|----------|-------------|
| NetworkVariableSettings | settings |             |
| System.UInt64           | value    |             |

### NetworkVariableULong(UInt64)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public NetworkVariableULong(ulong value)

#### Parameters

| Type          | Name  | Description |
|---------------|-------|-------------|
| System.UInt64 | value |             |

### Implements

<div>

INetworkVariable

</div>
