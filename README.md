# AutoStartDocument

# Request 1. Start Engine
```js

{
    cmd: 1,
    imei: "123456789"
}
```

// Response
const RES1 = {
    imei: "123456789",
    cmd: 1,
    success: true, // or false
    message: "If unsuccessful, the reason is returned"
}

/* --------------------------------------------------------------------- */

// Request 2. Stop Engine
const REQ2 = {
    cmd: 2,
    imei: "123456789"
}

// Response
const RES2 = {
    imei: "123456789",
    cmd: 2,
    success: true, // or false
    message: "If unsuccessful, the reason is returned"
}

/* --------------------------------------------------------------------- */

// Request 3. Car Lock
const REQ3 = {
    cmd: 3,
    imei: "123456789"
}

// Response
const RES3 = {
    imei: "123456789",
    cmd: 3,
    success: true, // or false
    message: "If unsuccessful, the reason is returned"
}

/* --------------------------------------------------------------------- */

// Request 4. Car Unlock
const REQ4 = {
    cmd: 4,
    imei: "123456789"
}

// Response
const RES4 = {
    imei: "123456789",
    cmd: 4,
    success: true, // or false
    message: "If unsuccessful, the reason is returned"
}

/* --------------------------------------------------------------------- */

// Request 5. Get car information
const REQ5 = {
    cmd: 5,
    imei: "123456789"
}

// Response
const RES5 = {
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
