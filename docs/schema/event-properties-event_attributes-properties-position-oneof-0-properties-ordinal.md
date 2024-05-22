# Untitled object in Event Schema

```txt
https://o19s.github.io/ubi/schema/event.schema.json#/properties/event_attributes/properties/position/oneOf/0/properties/ordinal
```

The nth position of the document on the search results page.

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [event.schema.json\*](../../out/event.schema.json "open original schema") |

## ordinal Type

`object` ([Details](event-properties-event_attributes-properties-position-oneof-0-properties-ordinal.md))

# ordinal Properties

| Property        | Type      | Required | Nullable       | Defined by                                                                                                                                                                                                                                                       |
| :-------------- | :-------- | :------- | :------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [index](#index) | `integer` | Required | cannot be null | [Event](event-properties-event_attributes-properties-position-oneof-0-properties-ordinal-properties-index.md "https://o19s.github.io/ubi/schema/event.schema.json#/properties/event_attributes/properties/position/oneOf/0/properties/ordinal/properties/index") |

## index

The position of the document.  For grid layout this would be left to right, ignoring wrapping.

`index`

* is required

* Type: `integer`

* cannot be null

* defined in: [Event](event-properties-event_attributes-properties-position-oneof-0-properties-ordinal-properties-index.md "https://o19s.github.io/ubi/schema/event.schema.json#/properties/event_attributes/properties/position/oneOf/0/properties/ordinal/properties/index")

### index Type

`integer`

### index Examples

```json
1
```

```json
3
```

```json
24
```