# AMPD
* Finds peaks in a periodic or quasi-periodic signal D. P contains the sample indices of the peak positions.
 * It implements a multiscale peak detection algorithm proposed in Scholkmann et al.. D MUST be a signal that 
 * is periodic or quasi-periodic such as pulsemeter readouts, respiration belt output or solar spot intensity 
 * changes. The periodicity of peaks are detected automatically, no parameter is needed to be given. The peri-
 * odicity that is detected consists of the periodicity where the highest amount oflocal maximas are found.
 * I have furthere extended this code to find minimas of the singal aswell.
 * <p>
 * Reference:
 * <pre> 
 * An Efficient Algorithm for Automatic Peak Detection in Noisy Periodic and Quasi-Periodic Signals.             
 * http://www.mdpi.com/1999-4893/5/4/588            