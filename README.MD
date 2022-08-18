#There are unwanted packages but they are used for future projects.
#So its's good to keep as there might be version incompatabilities

Installing requirments
	pip install -r requirements.txt

To make standalone file	
	pyinstaller video2mp3v3.py // WILL NOT WORK
#Issues arise when running exe using this method, so use spec file
	pyinstaller video2mp3v3.spec

To change file discription edit file_version_info.txt
