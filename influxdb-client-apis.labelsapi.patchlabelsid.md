<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@influxdata/influxdb-client-apis](./influxdb-client-apis.md) &gt; [LabelsAPI](./influxdb-client-apis.labelsapi.md) &gt; [patchLabelsID](./influxdb-client-apis.labelsapi.patchlabelsid.md)

## LabelsAPI.patchLabelsID() method

Update a label. See [https://v2.docs.influxdata.com/v2.0/api/\#operation/PatchLabelsID](https://v2.docs.influxdata.com/v2.0/api/#operation/PatchLabelsID)

<b>Signature:</b>

```typescript
patchLabelsID(request: PatchLabelsIDRequest, requestOptions?: RequestOptions): Promise<LabelResponse>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  request | [PatchLabelsIDRequest](./influxdb-client-apis.patchlabelsidrequest.md) | request parameters and body (if supported) |
|  requestOptions | [RequestOptions](./influxdb-client-apis.requestoptions.md) | optional transport options |

<b>Returns:</b>

Promise&lt;[LabelResponse](./influxdb-client-apis.labelresponse.md)<!-- -->&gt;

promise of response
