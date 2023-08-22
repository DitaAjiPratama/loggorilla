# LogGorilla
Python Script for logging format.

There is 4 type for this logging availability:
- `prcss` for logging a process
- `fyinf` for logging a value
- `accss` for logging an access
- `error` for logging the error

## Usage

    APIADDR = "/your/api/page/directory"
    
    loggorilla.prcss(APIADDR, f"Checking authority"                     )
    loggorilla.fyinf(APIADDR, f"Username: {username}"                   )
    loggorilla.prcss(APIADDR, f"{username} try to logged in and failed" )
    loggorilla.error(APIADDR, f"Username and Password is Incorrect"     )
