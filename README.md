# LWDF-for-the-CD-to-DAT-Sample-Rate-Conversion-application
List of required files for the implementation and tests of the CD2DAT application.

fir.c (Implementation file for the multirate FIR)
fir.h (Header file for the multirate FIR)
util.c (Implementation file for the utility functions)
util.h (Header file for the utility functions)
wav_file_source.c (Implementation file for the wave file reader)
wav_file_source.h (Header file for the wave file reader)
wav_file_sink.c (Implementation file for the wave file writer)
wav_file_sink.h (Header file for the wave file writer)
disps_fifo.c (Implementation file for the FIFO ADT)
disps_fifo.h (Header file for the FIFO ADT)
actor.h (Header file for the actor ADT)
actor_context_type_common.h (Header file for the actor ADT)
coefs1.txt (Tap coefficients for the 1st FIR (i.e. FIR1) in the CD2DAT application)
coefs2.txt (Tap coefficients for the 2nd and the 4th FIRs (FIR2 and FIR4) in the CD2DAT application) 
coefs3.txt (Tap coefficients for the 3rd FIR (i.e. FIR3) in the CD2DAT application)
cd.wav (Input file for your tests of CD2DAT application)
correct-dat.wav (Correct output file for your tests of CD2DAT application)
