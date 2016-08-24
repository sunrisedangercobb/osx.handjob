# HandJob
A basic wrapper for handbrake binary that allow you to do multiple jobs.

This is a shout out to the amazing team at handbrake, you guys are amazing; thanks for all your hardwork to create such a robust tool!

This wrapper is a very simple way either running a single or batch job using any of the handbrake builtins.  It allows you to choose target/destination and was created to simply save time.

I often found myself doing batch re-encodes of files and adding them one by one was tedious.  This supports conversion to either .mkv or .mp4 from .avi .mp4 .mkv .mpg with any of handbrakes builtin options.

# note
Kill is at the initial prompt, this will stop all jobs running (even multiple instances). Due to being able to spawn multiple jobs be aware that you can easily choke your resources.
This app would like to use a ruby gem called terminal-notifier.  If it is not installed it will use the basic notifications.  

If you would like to install the gem you can issue this command:
[sudo] gem install terminal-notifier

