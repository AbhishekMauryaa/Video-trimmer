# Video-trimmer
This Python script is designed to trim a video file into smaller segments of 90 seconds each. It utilizes the moviepy library, a powerful tool for video editing and manipulation in Python.


# Prerequisites
Python installed on your system.
The moviepy library installed. You can install it using pip:
pip install moviepy

# Instructions
Import Modules: Import the necessary modules moviepy.editor and os.
##
Specify Paths: Set the input_video_path variable to the path of the video you want to trim, and output_folder_path to the folder where you want to save the trimmed clips.
##
Load Video: Load the input video file using VideoFileClip().
##
Get Duration: Get the duration of the video in seconds.
##
Trim Video: Loop through the video in segments of 90 seconds, trimming each segment and storing it in the clips list.
##
Reverse Order: Reverse the order of the clips to maintain chronological order.
##
Write Clips: Write each trimmed clip to a separate video file in the output folder.
# Usage
Update the input_video_path and output_folder_path variables with your desired paths.
Run the script. It will trim the video into 90-second segments and save them as separate video files in the specified output folder.

# Example
For example, if your input video is charlie.mp4 located at C:\Users\Abhishek Maurya\Desktop\strt\main\ and you want to save the trimmed clips in C:\Users\Abhishek Maurya\Desktop\strt\trim, you would set:


input_video_path = r"C:\Users\Abhishek Maurya\Desktop\strt\main\charlie.mp4"
output_folder_path = r"C:\Users\Abhishek Maurya\Desktop\strt\trim"
# Note
Make sure the input video file exists at the specified path.
Ensure that the output folder exists; otherwise, the script will throw an error.
Depending on the length of the input video, the number of generated clips may vary.
