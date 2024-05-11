# Typescript helpers

Small footprint library that helps with repetitive tasks.

## Installation

```bash
npm i --save @hoangcung1804npm/quidem-asperiores-nulla
```

## Usage

```ts
import {DeepObjectScan} from '@hoangcung1804npm/quidem-asperiores-nulla/deep-object-scan';
import {OfNumberType} from '@24vlh/ts-assert/number';

console.log(
    DeepObjectScan('a.b.c', {a: {b: {c: 1}}}, OfNumberType)
);
// shall output 1
```

## List of helpers

### Helpers

- DeepCopyPrimitive
- DeepCopy
- DeepObjectScan
- MoveArrayEntryIndex
- ReadObjectProperty
- SaveAs
- SaveAsPrimitive
- SaveAsBlob
- SaveAsText
- SaveAsJson
- SaveAsCsv
- SaveAsXml
- SaveAsHtml
- SaveAsImage
- SaveAsCanvas
- SaveAsPdf
- SaveAsAudio
- SaveAsVideo
- SaveAsFile
- SaveAsArrayBuffer
- SaveAsBlobParts

@vlah.io
