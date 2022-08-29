# Positions
Paramaters:_name_:Defines of Name Variable (Support We:"x" and "y"). (and _value_: Defines a Value the Position.)
## X
Adjust a x position without graphic (or vercial line) html5.

Try Digiting:
```js
new Position("x", 2)
```

## Y
Adjust a y position without graphic html5.

Try Digiting:
```js
new Position("y", 1)
```

## Shipped Position Auto Updating
Uses a `() => ` in a value:
```js
new Position("y", () => Math.cos(1.5))
new Position("y", () => Math.tan(27))
```

## Update Positions
Must use the equaltion the value:
```js
a[0] = new Position("x", 2.25)
```