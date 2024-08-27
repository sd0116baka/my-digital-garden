```dataview
>> task
>> from "Note/Period/Daily"
>> where file.cday = date(today)
>> where meta(link).subpath = "Breaking"
>> ```