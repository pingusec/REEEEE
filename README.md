# TO DO

- **cyber1**

  1. Understand email
  2. Present data in right way
  3. Aim for below the byte count, and fill the rest with `0x00` (if `cat` doesn't show null bytes), if not fill with spaces (`0x20`)

  - File must be in CSV format
  - The rows are ordered in importance (most important first)
    - Fields are seperated by comma "," (`0x2C`)
    - Rows are seperated by a newline "\n" (`0x0A`)
    - There must be no commas at the
      - Start of a row
      - End of a row
      - Within a data field
  - Each row has six fields

    - Name (max 30 chars) `eg. Cyber Disc`
    - Type - see below:
      > must be one of "summer school", "course", "school/college project", "work/placement project", "own project", "other" (without the quotes).
    - Level - see below:
      > (introduction, advanced, elite, etc) - You must leave the field empty if the level is not objectively/externally well-defined.
    - Start Date: `YYYY-MM-DD`
    - Duration in "typical working days"
    - Description - Up to 200 characters
    - WHAT IS THIS???? LIKE WHAT? LIKE OK? LET ME SLAP 50 BILLION SPACES IN THIS FIELD TO MAKE IT 2.5Kb Long????? LIKE BRUH
      > Any data within fields in the last row will be ignored.

    | Name                | Type              | Level        | Start | Duration (in typical working days) | Description |
    | ------------------- | ----------------- | ------------ | ----- | ---------------------------------- | ----------- |
    | Cyber Disc          | Course            | Elite        | Find  | 2 Years                            | HELP ME     |
    | CyberFirst Advanced | Course            | Advanced     | Find  | 2 Weeks                            | HELP ME     |
    | Work Experienced    | Placement Project | Advanced     | Find  | 2 Weeks                            | HELP ME     |
    | LED Fixture Project | Own Project       | Advanced     | Find  | 3 Months                           | HELP ME     |
    | InvestIN            | Course            | Introduction | Find  | 1 Day                              | HELP ME     |

- **cyber2**

  - 1000 bytes in length
  - Should expand on the first two rows in `cyber1`
  - What this means:
    > We are particularly interested in you creatively communicating how each particular activity developed you.
  - No Malware :|

- **README**
  - Optional
  - 200 bytes
  - Every char must represent precisely one ASCII character
