It contains jupyter notebooks to create xifusim simulations to test X-IFU Event Processor

There are two type of simulations:

*Pulses Database:*

Single_pulse_DB:   
   * Includes noise and pulse streams
   * Single pulse data base (updated with new configurations)
   * Including very small (20/50 eV pulses) as well as very large pulses (50/100 keV)
   
Multi_pulse_DB:   
   * Includes noise and pulse streams
   * Multiple pulse data base (updated with new configurations)
   * Single_pulse_CR_DB 
   * Includes noise and pulse streams
   * Single pulse data base with bath temperature streams

*Streams Database:*

Crab_DB: Crab spectrum defocused with a duration of 1.1s over one quadrant
   * 384 brightest pixels of Crab like spectrum for 1.1 s

Point_Source_DB: One source at 10mCrab in focus with a duration of 30.1s over the 50 brightest pixels
   * 50 brightest pixels of in focus 10 mCrab source for 30.1 s

CasA:
   * 384 brightest pixels of Cas1 like spectrum for 30.1 s

