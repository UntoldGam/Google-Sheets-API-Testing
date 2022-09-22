# Google Sheets Connector

These functions allow you to:

- make a connection to a google sheet
- use that connection to alter data within a google sheet
- use the data in a sheet to manage your program

The data that the module returns is in the following format:

```json
{
    values: [
        [
            100, 100, 100 // row 1
        ],
                [
            100, 100, 100 // row 2
        ]
    ]
}
```
