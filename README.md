# PsycCalibrationSite
Simple website to perform an image inversion test, go no go test, audio oddball test, and conversation simulation for EEG experiments.
The tests log timestamps and user info to an EEG connected trigger, as specified by the IP address. The conversation logs to a sql database. To initialize the database, go to the root of the directory and enter python. From a terminal, do the following:

>python

>from main import db

>db.create_all()

>exit()

Now, you can run the site with:
>python main.py

This was created with flask, sqlite, and ajax.
