# VBA Project: cJobject
This cross reference list for repo (cJobject) was automatically created on 4/18/2017 10:29:07 AM by VBAGit.For more information see the [desktop liberation site](http://ramblings.mcpher.com/Home/excelquirks/drivesdk/gettinggithubready "desktop liberation")
You can see [library and dependency information here](dependencies.md)

###Below is a cross reference showing which modules and procedures reference which others
*module*|*proc*|*referenced by module*|*proc*
---|---|---|---
cregXLib||regXLib|rxMakeRxLib
cStringChunker||cJobject|serialize
cStringChunker||cJobject|recurseSerialize
cStringChunker||cJobject|unSplitToString
regXLib|rxReplace|usefulcJobject|hackJSObjectToJSON
regXLib|rxReplace|usefulcJobject|hackJSONPObjectToJSON
regXLib|rxReplace|usefulcJobject|cleanGoogleWire
usefulcJobject|toISODateTime|cJobject|recurseSerialize
usefulSheetStuff|min|usefulcJobject|cleanGoogleWire
usefulStuff|escapeify|cJobject|recurseSerialize
usefulStuff|isSomething|cJobject|findInArray
usefulStuff|makeKey|cJobject|find
usefulStuff|SortColl|cJobject|sortByValue
