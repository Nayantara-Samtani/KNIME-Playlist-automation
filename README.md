# KNIME-Playlist-automation
Built an automated KNIME workflow that cleans song data, categorizes tracks by danceability, generates balanced playlists, calculates cumulative runtime, and exports playlists under a specified duration limit.

Overview

I built this project in KNIME to explore how workflow automation can be used to solve a simple but practical problem: creating playlists from a large music dataset. Instead of manually sorting songs, I created a workflow that cleans the data, groups songs based on danceability, and automatically generates playlists that follow a specific pattern. The goal was to learn more about data preparation, automation, and how different KNIME nodes can work together to create a complete process from start to finish.

What I Did

I started by importing the dataset and cleaning it by handling missing values to make sure the workflow would run smoothly. From there, I used rule-based filtering to separate songs into high and medium danceability groups. After shuffling each group to create variety, I built a playlist pattern that places four high-danceability songs followed by one medium-danceability song. One challenge I ran into was calculating the playlist runtime using the Moving Aggregation node. It took some trial and error to figure out, but working through that problem helped me better understand how cumulative calculations work in KNIME. Once the playlist met the required duration, I exported the results as CSV files.

Skills Used

Through this project I gained hands-on experience with KNIME workflow design, data cleaning, rule-based filtering, workflow automation, and cumulative calculations. More importantly, it helped me develop problem-solving skills by troubleshooting workflow issues and finding ways to connect different nodes to achieve the final result. It was a good exercise in thinking through a process step-by-step and turning a manual task into an automated workflow. Looking back, it was one of the projects that helped me become more comfortable working with KNIME and understanding how data moves through a workflow from input to final output.
