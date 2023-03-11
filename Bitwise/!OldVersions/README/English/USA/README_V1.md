
***

# Bitwise operations

Originally, QMEFS was planned to be a 256 bit file system with 128 bit compatibility. This has remained the same, but new modes have been added to futureproof the design:

- ~~4 bit mode (`2^4`)~~ **Not supported**
- ~~8 bit mode (`2^8`)~~ **Not supported**
- ~~12 bit mode (`2^12`)~~ **Not supported**
- ~~16 bit mode (`2^16`)~~ **Not supported**
- ~~24 bit mode (`2^24`)~~ **Not supported**
- ~~32 bit mode (`2^32`)~~ **Not supported**
- ~~48 bit mode (`2^48`)~~ **Not supported**
- ~~64 bit mode (`2^64`)~~ **Not supported**
- 128 bit mode (`2^128`) **Backwards compatibility mode**
- 256 bit mode (`2^256`) **Starter default mode**
- **512** bit mode (`2^512`)
- **1024** bit mode (`2^1024`)
- **2048** bit mode (`2^2048`)
- **4096** bit mode (`2^4096`)
- **8192** bit mode (`2^8192`)
- **16384** bit mode (`2^16384`)
- **32768** bit mode (`2^32768`)
- **65536** bit mode (`2^65536`)

This should cover any bitwise computational limitation issues that arise for at least 500 years. 256 bit will be the default for now, with support for each bitwise counter being added when needed. The [:octocat: DeciCube project](https://github.com/seanpm2001/DeciCube/) is looking more complicated than originally thought, so this improvement was needed.

***

**File version:** `1 (2023, Friday, March 10th at 5:36 pm PST)`

***
