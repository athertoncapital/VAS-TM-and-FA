# VAS-TM-and-FA

Dec. 8, 2015

I changed the upper limit of steps to MAX_VALUE = 2147483647 in Preferences.java so that the program will not stop after running 100000 steps when students design TM to run their own Enumeration Machines.

Before the modification: public static final int DEFAULT_INFINITE_TM_STEPS = 100000;

After: public static final  int DEFAULT_INFINITE_TM_STEPS = Integer.MAX_VALUE; //2147483647
