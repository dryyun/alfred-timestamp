# Alfred-timestamp

Alfred Timestamp Workflow

**_自用_**  
- `ts `
- `ts 1645449120001`  
- `ts 1645449120`  
- `ts 2022-02-21 21:27:00`  
- `ts 2022-02-21`  
- `ts +1h`
- `ts -1d`


## Workflow

**Alfred Keyword: `ts`**

Usage: ts \<duration\>

​ *duration:*

- +1w: add 1 weeks
- +2d: add 2 days
- -1h: sub 1 hours
- -2m: sub 2 minutes
- -3s: sub 3 seconds
- +4ms: add 4 milliseconds
- +5us: add 5 microseconds
- +6ns: add 6 nanoseconds
- +1d12h30m: add 1 days, 12 hours and 30 minutes

**Output Format:**

- int64 (timestamp)
- 2006-01-02
- 2006-01-02 15:04:05
- 2006-01-02T15:04:05Z07:00
- Mon, 02 Jan 2006 15:04:05

![screen](screen.png)

## Install

Download [alfred-workflow_kaba-ts.alfredworkflow](https://github.com/kabacloud/alfred-timestamp/raw/main/alfred-workflow_kaba-ts.alfredworkflow)

Double-click the alfred-workflow_kaba-ts.alfredworkflow to install.

