The code "generate_tts.cpp" produces and saves the truth tables of the Boolean functions which are obtained from the 
representative truth tables (RTTs) mentioned in [1]. The code is compiled with Microsoft Visual C++ 2010.

The following files are needed to run the code:

"ADK9.txt":           Contains the integer values corresponding to the vector space representations of the nonzero elements in GF(2^9).

"ADK11.txt":          Contains the integer values corresponding to the vector space representations of the nonzero elements in GF(2^{11}).

"ADK15.txt":          Contains the integer values corresponding to the vector space representations of the nonzero elements in GF(2^{15}).

"EC15_1.txt":         Contains the 21 equivalency classes for k=1.

"EC15_3.txt":         Contains the 49 equivalency classes for k=3.

"EC15_5.txt":         Contains the 93 equivalency classes for k=5.

The code generates the following files:

"TTs9.txt":   The truth tables of the 7  Boolean functions for the 9-variable case (mentioned in Remark).

"TTs11.txt":  The truth tables of the 13  Boolean functions for the 11-variable case (given in Table 5 in [1]).

"TTs15_1.txt":The truth tables of the 2   Boolean functions for the case k=1 (given in Table 1 in [1]).

"TTs15_3.txt":The truth tables of the 35  Boolean functions for the case k=3 (given in Table 2 in [1]).

"TTs15_5.txt":The truth tables of the 133 Boolean functions for the case k=5 (two of them are given in Table 4 in [1]).

Written by Selçuk Kavut, Balıkesir University, Turkey.

[1] S. Kavut. Modified Patterson-Wiedemann Construction.
