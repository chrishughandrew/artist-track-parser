![GitHub](https://img.shields.io/github/license/chrishughandrew/artist-track-parser)
![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/chrishughandrew/artist-track-parser?include_prereleases)

---

## Original Problem/Solution Formulation
### The Problem

Every working day, I consume copious volumes of music through online radio, often hearing tracks that that _need_ to be remembered for future reference. 

Currently, I copy the track info from the online radio platform tracklist, paste it into a `.txt` file (titled: Tunes {CurrentMonthYear}) and parse it into a single-line, readable format for future consumption - awful. 

### A Solution
The manual process of parsing this track info into a readable/usable format should be automated, from control of the the clipboard's latest contents, and stored in a more desriable format, to be output at the user's choosing - all in minimum of a single click. 

1. Get clipboard contents
2. Identify the properties of that copy:
    - content formats are radio station dependant
    - default: BBC
    - others: NTS, WorldwideFM, Bandcamp, Soundcloud,  custom(?)
3. Parse the contents into standard format
4. Store track in a retrievable format

#### Standard info
- Artist name
- Track name
- Record label (sometimes available)

#### Custom info
- Personal notes about the track
- relation to previous track (optional)
- Rating (5*) (could be other)(optional)


### Learning Outcomes
- Design/code in the SOLID paradigm
- Decide: app style (Console, Winforms, Web, all?) 
- Decide: storage format(s) outputs (NoSQL, SQL, ?)
- Decide: does this need to utlise asynchronous?
- Include: Unit testing project?
- Learn to store all application secrets (eg. DB connections) securely, (Github secrets?) 

