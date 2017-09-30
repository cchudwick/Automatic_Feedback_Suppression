# Automatic_Feedback_Suppression

Automatic Suppression of Acoustic Feedback:

A Real-Time Analysis and Learning Tool for Multichannel Systems in Pure Data


Acoustic feedback is a potential problem in every live public address (PA) situation. This work creates a patch in Pure Data to suppress instances of acoustic feedback using a standard procedure of Notch-filter-based Howling Suppression (NHS), where audio signals are analyzed for feedback and notch filters are applied to the signals at the frequencies that are determined to be feeding back. Beyond testing the success of various frequency detection criteria, this work expands NHS by incorporating a microphone detection process to work with multichannel systems. In specifying which microphone is the most problematic at the feedback frequency, the process applies notch filters only to microphones that need it. This way, the frequency response of the general system is less affected by notch filters. Because this work is also intended as a learning tool for live sound engineers, its visual analysis of various frequency responses is made to be easily accessible. 
