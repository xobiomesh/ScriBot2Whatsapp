2024-03-08T20:36:17.591Z - onsimius: Hi again! I've been trying to get the  notes from different days and under different headings to be retrieved and I think I'm almost there but I the data doesn't make it to the end and into the new note... 
`js
function appendSectionsToNote(tp, headingsWithOffsets) {
    
    let allSections = '';

    // Iterate through each headingWithOffset provided in the array
    headingsWithOffsets.forEach(({ heading, daysOffset = 0 }) => {
        
        const dateForHeading = tp.date.now("YYYY-MM-DD dddd", -daysOffset);
        // Construct the include identifier with the calculated date and the current heading
        let section = tp.file.include(`[[${dateForHeading}${heading}]]`);
        // Append the fetched section to the allSections string
        allSections += section + '\n\n'; // Adding a newline for separation between sections
    });

    return allSections;
}
module.exports = appendSectionsToNote;
`
2024-03-08T20:36:36.117Z - onsimius: Hi again! I've been trying to get the  notes from different days and under different headings to be retrieved and I think I'm almost there but I the data doesn't make it to the end and into the new note... 
```js
function appendSectionsToNote(tp, headingsWithOffsets) {
    
    let allSections = '';

    // Iterate through each headingWithOffset provided in the array
    headingsWithOffsets.forEach(({ heading, daysOffset = 0 }) => {
        
        const dateForHeading = tp.date.now("YYYY-MM-DD dddd", -daysOffset);
        // Construct the include identifier with the calculated date and the current heading
        let section = tp.file.include(`[[${dateForHeading}${heading}]]`);
        // Append the fetched section to the allSections string
        allSections += section + '\n\n'; // Adding a newline for separation between sections
    });

    return allSections;
}
module.exports = appendSectionsToNote;
```
2024-03-08T20:37:08.173Z - onsimius: Hi again! I've been trying to get the  notes from different days and under different headings to be retrieved and I think I'm almost there but I the data doesn't make it to the end and into the new note... 
function appendSectionsToNote(tp, headingsWithOffsets) {
    
    let allSections = '';

    // Iterate through each headingWithOffset provided in the array
    headingsWithOffsets.forEach(({ heading, daysOffset = 0 }) => {
        
        const dateForHeading = tp.date.now("YYYY-MM-DD dddd", -daysOffset);
        // Construct the include identifier with the calculated date and the current heading
        let section = tp.file.include(`[[${dateForHeading}${heading}]]`);
        // Append the fetched section to the allSections string
        allSections += section + '\n\n'; // Adding a newline for separation between sections
    });

    return allSections;
}
module.exports = appendSectionsToNote;
2024-03-08T20:37:14.700Z - onsimius: function appendSectionsToNote(tp, headingsWithOffsets) {
    
    let allSections = '';

    // Iterate through each headingWithOffset provided in the array
    headingsWithOffsets.forEach(({ heading, daysOffset = 0 }) => {
        
        const dateForHeading = tp.date.now("YYYY-MM-DD dddd", -daysOffset);
        // Construct the include identifier with the calculated date and the current heading
        let section = tp.file.include(`[[${dateForHeading}${heading}]]`);
        // Append the fetched section to the allSections string
        allSections += section + '\n\n'; // Adding a newline for separation between sections
    });

    return allSections;
}
module.exports = appendSectionsToNote;
2024-03-10T02:07:48.986Z - onsimius:  [Attachment: https://cdn.discordapp.com/attachments/1215760008088780800/1216205842601345074/message.txt?ex=6655e534&is=665493b4&hm=5e01119dcf3c4139568263139c058747019b66428a6b4bbce543d8050dad532a&]
2024-03-10T02:46:12.997Z - onsimius:  [Attachment: https://cdn.discordapp.com/attachments/1215760008088780800/1216215506390876220/message.txt?ex=6655ee34&is=66549cb4&hm=321a30a2767856ee130d85536e4832aef37e921af3b3484d8344618ea3400902&]
2024-05-27T23:42:29.697Z - onsimius: !fetch
2024-05-27T23:42:30.161Z - ScriBot: Fetched and saved all messages to channel_messages.txt
2024-05-28T00:28:31.981Z - onsimius: !fetch
2024-05-28T00:28:32.785Z - ScriBot: Fetched and saved all messages to channel_messages.txt
2024-05-28T01:29:31.260Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T01:32:35.418Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T01:35:10.117Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T01:37:52.117Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T01:39:42.614Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T01:41:45.383Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T01:43:36.360Z - ScriBot: The bot is not in a voice channel.
2024-05-28T01:43:46.337Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T01:47:29.134Z - onsimius: aa
2024-05-28T01:47:32.603Z - onsimius: aa
2024-05-28T01:47:42.235Z - onsimius: a
2024-05-28T01:48:36.559Z - onsimius: d2024-05-28T01:49:14.348Z - onsimius: a
2024-05-28T01:49:22.485Z - onsimius: aaae
2024-05-28T01:49:25.257Z - onsimius: zez
2024-05-28T01:52:15.956Z - onsimius: azeaze
2024-05-28T02:18:39.767Z - onsimius: zer
2024-05-28T02:18:44.493Z - onsimius: ezr
2024-05-28T02:33:38.671Z - onsimius: ze
