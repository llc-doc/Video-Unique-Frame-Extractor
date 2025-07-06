# Video-Unique-Frame-Extractor

Running mode (executed on the command line):

Python main. py [Video file path] [Output directory path] [Optional: -- threshold threshold]

Parameter description:

Video file path: The complete or relative path of the video file

Example: "C:/videos/my-video. mp4" or "./input/video. mp4"

Output directory path: Save the directory path of the extracted frame

Example: "C:/Output_frames" or "./extracted_frames"

--Threshold (optional): Frame difference threshold (default 30.0)

The smaller the value, the more sensitive it is, and the more frames are extracted

Example: -- threshold 25.0

