<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Runtime](./puppeteer.protocol.runtime.md) &gt; [CustomPreview](./puppeteer.protocol.runtime.custompreview.md)

## Protocol.Runtime.CustomPreview interface

<b>Signature:</b>

```typescript
export interface CustomPreview 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [bodyGetterId](./puppeteer.protocol.runtime.custompreview.bodygetterid.md) | [RemoteObjectId](./puppeteer.protocol.runtime.remoteobjectid.md) | If formatter returns true as a result of formatter.hasBody call then bodyGetterId will contain RemoteObjectId for the function that returns result of formatter.body(object, config) call. The result value is json ML array. |
|  [header](./puppeteer.protocol.runtime.custompreview.header.md) | string | The JSON-stringified result of formatter.header(object, config) call. It contains json ML array that represents RemoteObject. |

