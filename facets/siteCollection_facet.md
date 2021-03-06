# SiteCollection resource

The **siteCollection** resource provides more information about a site collection.

If a [**site**](../resources/site.md) resource has a non-null **siteCollection** property, then the site is a root site for a site collection.

## JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [
  ],
  "@odata.type": "oneDrive.siteCollection"
}-->

```json
{
  "hostname": "contoso.sharepoint.com"
}
```

## Properties

| Property name | Type    | Description                                                                                                                  |
|:--------------|:--------|:---------------------------------------------------
| **hostname**  | string  | The hostname for the site collection. Read-only.


<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "",
  "keywords": "",
  "section": "documentation",
  "tocPath": "Facets/SiteCollection"
}-->
