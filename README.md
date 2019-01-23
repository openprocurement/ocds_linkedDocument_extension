## Linked Document
The extension shows entity to which the document belongs
# Overview
The fields introduced by this extension are:
- `documents/relatedItem` - The identifier of the item that the document belongs to. 
It should be string value.
- `documents/documentScope` - The entity to which the document belongs. 
It should be string value which can be `tender` or `item`.
# Example
The following extract illustrates this property in use within the documents block.
```
{
    "documents": [
          {
            "hash": "md5:00000000000000000000000000000000",
            "language": "uk",
            "title": "Notice.pdf",
            "url": "http://public.docs-sandbox.openprocurement.org/get/f8910e202a3f451a904ae67142358a74?KeyID=d8e133db&Signature=gWwLvym6za8Ii%252BfpoueQoftCtQSE4M%2FyyNKu%2FtLjuy96l%2FYJoH%252BUFQ4Up8YpoFnppZo1mHxGOuZ2XMOK49ZLDg%253D%253D",
            "format": "application/pdf",
            "relatedItem": "edd0032574bf4402877ad5f362df225a",
            "documentScope": "tender",
            "datePublished": "2017-06-21T17:05:22.481301+03:00",
            "id": "95a16064160d49fe820a8bee63fff415",
            "dateModified": "2017-06-21T17:05:22.481335+03:00"
          }
    ]
}
```