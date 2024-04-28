# Create env
> python -m venv env

# Activate env
> source env/bin/activate

# Install packages
> python -m pip install ffmpeg faster-whisper

# Freeze packages
> pip freeze > requirements.txt

# TO RUN THE SUBTITLE GENERATOR PROGRAM
> python video_subs.py --input resources/TAHM_SSSS.avi --output output

# TO CONVERT THE SUBTITLE TO SRT PROGRAM
> python subs_convert.py --input output/output.csv --output output

# Deactivate env
> deactivate

# Setup a new copy of the project
> pip install -r requirements.txt
