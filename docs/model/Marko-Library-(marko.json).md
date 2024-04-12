---
stoplight-id: f9fk0h96vtwb3
---

# Marko Library Definition (marko.json)


```yaml json_schema
$ref: ../../src/models/tag.yaml
```
---
```json json_schema
{
  "type": "object",
  "allOf": [
          {
            "title": "object :: Tag (camelCased)",
            "type": "object"
          },
          {
            "type": "object",
            "$ref": "../../schemas/models/tag.base.json#/$defs/camelCased"
          },
          {
            "type": "object",
            "$ref": "tag.base.json#/$defs/topLevel-tag-properties"
          }
        ]
}
```
