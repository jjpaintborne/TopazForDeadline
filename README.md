# TopazForDeadline

This has only been tested with Topaz Video AI 3.0.12
Other versions may or may not work

A Deadline plugin for enhancing Deadline jobs through Topaz Video AI

Unzip Topaz.zip to \DeadlineRepository10\custom\plugins

Copy "Topaz-Combined.py to \DeadlineRepository10\custom\scripts\Jobs

Configure Topaz to point to ffmpeg.exe inside the Topaz Video AI folder (C:\Program Files\Topaz Labs LLC\Topaz Video AI\ffmpeg.exe)

Add or modify this System ENV Variable to any node running Topaz Video AI
  Variable name: VEAI_MODEL_DIR
  Variable value: C:\ProgramData\Topaz Labs LLC\Topaz Video AI\models\
  
References
Command Line Interface (CLI) Instructions for Topaz Video AI v3.0
https://support.topazlabs.com/article/118-command-line-interface-instructions-for-video-enhance-ai-v3-0

I modified an existing ffmpeg.py script I found on GitHub but forgot who it belongs to. If I can find it I will add it here
