<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [notion-types](./notion-types.md) &gt; [BoardCollectionView](./notion-types.boardcollectionview.md)

## BoardCollectionView interface

<b>Signature:</b>

```typescript
export interface BoardCollectionView extends BaseCollectionView 
```
<b>Extends:</b> [BaseCollectionView](./notion-types.basecollectionview.md)

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [format](./notion-types.boardcollectionview.format.md) | { board\_cover: [CollectionCardCover](./notion-types.collectioncardcover.md)<!-- -->; board\_cover\_size: [CollectionCardCoverSize](./notion-types.collectioncardcoversize.md)<!-- -->; board\_cover\_aspect: [CollectionCardCoverAspect](./notion-types.collectioncardcoveraspect.md)<!-- -->; board\_properties: Array&lt;{ property: [PropertyID](./notion-types.propertyid.md)<!-- -->; visible: boolean; }&gt;; board\_groups2: Array&lt;{ property: [PropertyID](./notion-types.propertyid.md)<!-- -->; hidden: boolean; value: { type: [PropertyType](./notion-types.propertytype.md)<!-- -->; value: string; }; }&gt;; board\_columns: Array&lt;{ property: [PropertyID](./notion-types.propertyid.md)<!-- -->; hidden: boolean; value: { type: [PropertyType](./notion-types.propertytype.md)<!-- -->; value: string; }; }&gt;; } |  |
|  [type](./notion-types.boardcollectionview.type.md) | 'board' |  |

