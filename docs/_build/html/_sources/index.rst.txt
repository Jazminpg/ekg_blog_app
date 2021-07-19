.. ECG Visual App documentation master file, created by
   sphinx-quickstart on Mon Jul 19 16:58:40 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to ECG Visual App's documentation!
==========================================
This app had the intention to save and show ecg graphics in order to simplify the cardiologists life. 
Although, the ecg graphics are still apart from the visual app. 


The visual app runs in Django framework, of course with its own virtualenv.
The ecg app (heart rate signal file) runs in python with the help of spyder editor (because this shows graphics inmediately)

In the visual app the user can log in, sign up and log out. 
Also the user can create new entries to save patient data. It's supposed to save the ecg graphic but for so far you can write the title
as the patient name, the author that is creating the entry, because more than one cardiologist could save data (as in hospitals).
And finally, add a description for the heart rate signal, the details.

The entries can create not just main patient entrance but also little posts, not just for patient data but also if any doctor
would like to create a post to inform his/her mates important information about heart diseases.

The user can create, edit and delete a post and a main article. 

.. toctree::
   :maxdepth: 2
   :caption: Contents:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
