# AutoStartDocument

## Request 1. Start Engine
```js
{
    cmd: 1,
    imei: "123456789"
}
```

## Response
```js
{
    imei: "123456789",
    cmd: 1,
    success: true, // or false
    message: "If unsuccessful, the reason is returned"
}
```

## Request 2. Stop Engine
```js
{
    cmd: 2,
    imei: "123456789"
}
```

## Response
```js
{
    imei: "123456789",
    cmd: 2,
    success: true, // or false
    message: "If unsuccessful, the reason is returned"
}
```

## Request 3. Car Lock

```js
{
    cmd: 3,
    imei: "123456789"
}
```

## Response
```js
{
    imei: "123456789",
    cmd: 3,
    success: true, // or false
    message: "If unsuccessful, the reason is returned"
}
```


## Request 4. Car Unlock

```js
{
    cmd: 4,
    imei: "123456789"
}
```

## Response

```js
{
    imei: "123456789",
    cmd: 4,
    success: true, // or false
    message: "If unsuccessful, the reason is returned"
}
```

## Request 5. Get car information

```js
{
    cmd: 5,
    imei: "123456789"
}
```

## Response

```js
{
    imei: "123456789",
    cmd: 5,
    success: true, // or false
    message: "If unsuccessful, the reason is returned",
    data: {
        temprature: "10 C",
        volt: "10",
        latitude: 10,
        longitude: 10,
        // etc other information
    }
}
```
