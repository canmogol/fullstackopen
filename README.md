# Full Stack Open 2021 Course

Deep Dive Into Modern Web Development Full Stack Open 2021 course exercises.

## Part0

This chapter contains the general information about course content and fundamentals of Web applications.

### 0.4: new note

> Create a similar diagram depicting the situation where the user creates a new note on page 'https://studies.cs.helsinki.fi/exampleapp/notes' by writing something into the text field and clicking the submit button.

![Sequence Diagram for Posting on notes endpoint](https://www.websequencediagrams.com/cgi-bin/cdraw?lz=bm90ZSBvdmVyIGJyb3dzZXI6CndoZW4gY2xpY2tpbmcgb24gdGhlIHN1Ym1pdCBidXR0b24sCgAmByBzZW5kcwAcBWZvcm0gZGF0YSBjb250YWluaW5nIAp0aGUgJ25vdGUnIGlucHV0IGZpZWxkJ3MgdmFsdWUuCmVuZCBub3RlCgBKCC0-c2VydmVyOiBIVFRQIFBPU1QgaHR0cHM6Ly9zdHVkaWVzLmNzLmhlbHNpbmtpLmZpL2V4YW1wbGVhcHAvbmV3XwBJBgCBTgoASQcKAFIGIGNyZWF0ZXMgYQBzBSBvYmplY3Qgd2l0aACBYwUAgSYHAIEaBSAKYW5kIGN1cnJlbnQgZGF0ZSwgYW5kIGFkZHMgaXQgdG8AKwhkZXMnIGFycmF5LApyZXR1cm5zIGEgMzAyIHJlZGlyZWN0IHJlc3BvbnNlIHRvIACBJg1vdGVzAIF9DACBegYtLT4AgwkIAIIEBjMwMiBSAEUIADAUAIFoDACDQwkAgyAIZ2V0AIMhBgCAfxEAgV8FAINBBmEgR0VUAEYWAIMIIEdFAIJ6LQCBKwUAgVUUTUwtY29kAIMzDQCBOxFzdGFydHMgcmVuZGVyaW5nAIUbBUhUTUwsIGZpAIUHCCdsaW5rJwCDKgUnc2NyaXB0JyB0YWdzLgotAIFlCXJlcXVlcwCDPgoALQZVUkwgdG8gZ2V0AIV0BUNTUwAYHABUCAAnD0pTAIU6IgCCBi5tYWluLmNzAIIjFAASCQAfSmoATxlqAIRLHgCDFgdleGVjdXRpbmcganMAg0wGdGhhdACCaghzIEpTT04AiCgGZnJvbQCHHQcgAIQYT2RhdGEuanNvbgCGQRNbewCJIwVlbnQ6ICJIVE1MIGlzIGVhc3kiLACHZQU6ICIyMDE5LTA1LTIzIiB9LCAuLi5dAIZHHQCBbgZlAIoJBmV2ZW50IGhhbmRsZXIAgXUIbmRlcnMAiWsFcyB0byBkaXNwbGF5AIl7Cg&s=default "Sequence Diagram")

### 0.5: Single page app

> Create a diagram depicting the situation where the user goes to the single page app version of the notes app at 'https://studies.cs.helsinki.fi/exampleapp/spa'.

![Sequence Diagram for Single page app](https://www.websequencediagrams.com/cgi-bin/cdraw?lz=CmJyb3dzZXItPnNlcnZlcjogSFRUUCBHRVQgaHR0cHM6Ly9zdHVkaWVzLmNzLmhlbHNpbmtpLmZpL2V4YW1wbGVhcHAvc3BhCgA5Bi0tPgBKBzogSFRNTC1jb2RlCgpub3RlIG92ZXIgABYIAHAIIHN0YXJ0cyByZW5kZXJpbmcgdGhlADYFLCBmaW5kcwALBSdsaW5rJyBhbmQgJ3NjcmlwdCcgdGFncy4KLSBzZW5kcyBhIHJlcXVlc3QgdG8AJwxVUkwgdG8gZ2V0AFQFQ1NTABgcAFQIACcPSlMuCmVuZCBub3RlCgCBbUVtYWluLmNzcwCCJBMAEgkAgwQXAIJqLS5qAE8UABIHAIJ0I2V4ZWN1dGluZyBqcwCDRwUgdGhhdACCYBYAglwIbm90ZXMgZnJvbSAAhE4GAIMzBXJlZ2lzdGVycyBhbiAKZXZlbnQgaGFuZGxlciB0bwAEBwCDeAVyZXNwb25zZS4KLQAoDgAkEXRoZSBmb3JtADIPAA4Fc3VibWl0AIJoUGRhdGEuanNvbgCFXRNbeyBjb250ZW50OiAiSFRNTCBpcyBlYXN5IiwgZGF0ZTogIjIwMTktMDUtMjMiIH0sIC4uLl0AhggVSmF2YVMAhWMFAIFmDwCCLAYAhg8GAIIgCCwKLSBhc3NpZ24ACg4AgwIHdG8gbG9jYWwAgxEHbGlzdACGRAUKLSBkcmF3AIZbBgARBW9mAIM1B29uAIcBBXBhZ2UAhW4L&s=default "Sequence Diagram")

### 0.6: New note

> Create a diagram depicting the situation where the user creates a new note using the single page version of the app.

![Sequence Diagram for Single page app POST](https://www.websequencediagrams.com/cgi-bin/cdraw?lz=bm90ZSBvdmVyIGJyb3dzZXI6CndoZW4gY2xpY2tpbmcgb24gdGhlIHN1Ym1pdCBidXR0b24sIEphdmFTY3JpcHQgZm9ybQAXCGV2ZW50IGhhbmRsZXIgCi0gcHIADgVzAD8FACUFZnJvbSBwb3N0aW5nAFUFZGF0YSwgCi0gY3JlYXRlcyBhIG5ldyAAgRMGYmplY3QAfAhmcm9udGVuZCwgYWRkcyB0bwCBFQVjbGllbnQtc2lkZQAwBXMgbGlzdCwKLSBjbGVhcgB1Bidub3RlJyBpbnB1dCdzIHRleHQKLSByZWRyYXcAgRcGAIIEBWxpcwBlCXBhZ2UsCi0gc2VuZHMgYSBQT1NUIHJlcXVlc3QgdXNpbmcgYW4gWE1MSHR0cFIAEQdhbmQgcmVnaXN0ZXJzIGFuAIIDD2ZvciByZXNwb25zZS4KZW5kAIFiBQoKAIJ1By0-c2VydmVyOiBIVFRQAGwGaHR0cHM6Ly9zdHVkaWVzLmNzLmhlbHNpbmtpLmZpL2V4YW1wbGVhcHAvbmV3X25vdGVfc3BhCgBDBi0tPgCDTwgATQYyMDEgeyJtZXNzYWdlIjoiAIN6BQCCcwZkIn0KCgCDfBNUaGUAhBQIIGxvZwCDRQYAgT0IIABEByBpZgAKDmNvZGUgaXMAbAVpAIQ9BgCEEA0AgXQK&s=default "Sequence Diagram")
