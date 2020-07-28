# Auto convert audio files to a specified format 
A WordPress plugin which automatically converts any audio upload to a specified format. Requires FFMPEG and the ability to run shell commands through PHP.

## How to specify the final audio format:
In audio-optimizer.php change:
$desired_ext                  = 'ogg';
