This is the stadard Wire library for Aruino UNO R4 modified
to allow the "**Time Slicing**" (*parameter configUSE_TIME_SLICING (1) in FreeRTOSConfig.h*) in FreeRTOS™.

In wire functions, where a response is required within
a specific time frame, interrupts remain active, but the
scheduler is temporary suspended.

gpb01 (guglielmo@braguglia.ch) - May 2025