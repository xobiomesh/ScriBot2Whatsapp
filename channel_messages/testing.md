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
2024-03-10T02:07:48.986Z - onsimius:  [Attachment: https://cdn.discordapp.com/attachments/1215760008088780800/1216205842601345074/message.txt?ex=66568df4&is=66553c74&hm=0f52ad307c03de928f1a165420e172c2877b261cb6c4c778810d77be4fe27a35&]
2024-03-10T02:46:12.997Z - onsimius:  [Attachment: https://cdn.discordapp.com/attachments/1215760008088780800/1216215506390876220/message.txt?ex=665696f4&is=66554574&hm=965d59ba64c06d5023f70904a2b2e67cf1987dae3bfd17ed9bfaaba3eaa2c480&]
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
2024-05-28T01:48:36.559Z - onsimius: d
2024-05-28T01:48:57.361Z - ScriBot: Fetched and saved all messages from testing to channel_messages/testing.md
2024-05-28T01:49:14.348Z - onsimius: a
2024-05-28T01:49:22.485Z - onsimius: aaae
2024-05-28T01:49:25.257Z - onsimius: zez
2024-05-28T01:50:18.098Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T01:51:08.019Z - onsimius: aze
2024-05-28T01:52:15.956Z - onsimius: azeaze
2024-05-28T01:52:27.054Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T01:59:12.507Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:01:03.444Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:01:23.948Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:15:10.868Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:15:24.554Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:16:25.370Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:16:35.008Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:18:39.767Z - onsimius: zer
2024-05-28T02:18:44.493Z - onsimius: ezr
2024-05-28T02:19:27.034Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:19:38.647Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:20:02.959Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:20:16.133Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:23:14.392Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:23:25.427Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:23:43.273Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:23:51.917Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:26:43.071Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:26:54.171Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:30:15.596Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:30:25.402Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:30:58.403Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:31:25.518Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:33:38.671Z - onsimius: ze
2024-05-28T02:33:46.884Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:34:22.028Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:39:42.217Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:47:22.751Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:50:13.279Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T02:50:42.567Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T02:57:55.317Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T03:08:47.590Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T03:23:01.830Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T03:25:07.242Z - ScriBot: Started recording in the voice channel Télétubies!
2024-05-28T03:25:26.820Z - ScriBot: Stopped recording and left the voice channel Télétubies.
2024-05-28T03:27:23.764Z - onsimius: azeaze
2024-05-28T03:27:38.787Z - ScriBot: Fetched and saved all messages from testing to channel_messages/testing.md
2024-05-28T03:28:02.197Z - onsimius: sdf
2024-05-28T03:28:08.456Z - onsimius: sdf
2024-05-28T03:28:09.586Z - onsimius: sdf
2024-05-28T03:31:10.891Z - onsimius: azer
2024-05-28T03:31:16.415Z - ScriBot: Fetched and saved all messages from testing to channel_messages/testing.md
2024-05-28T03:31:23.327Z - onsimius: zeraa2024-05-28T03:31:50.400Z - onsimius: azee
