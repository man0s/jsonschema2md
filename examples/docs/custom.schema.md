---
template: reference
foo: bar
---

# Custom Schema

```
https://example.com/schemas/custom
```

This is an extensible schema. It has `definitions`, that can be used in other schemas. Additionally, it allows custom properties.

| Abstract | Extensible | Custom Properties | Defined In |
|----------|------------|-------------------|------------|
| Can be instantiated | Yes | Allowed | [custom.schema.json](custom.schema.json) |

# Custom Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [foo](#foo) | `string` | Optional | Custom (this schema) |
| [bar](#bar) | `string` | Optional | Custom (this schema) |

## foo

A unique identifier given to every addressable thing.

`foo`
* is optional
* type: `string`
* defined in this schema

### foo Type


`string`






## bar

A unique identifier given to every addressable thing.

`bar`
* is optional
* type: `string`
* defined in this schema

### bar Type


`string`





