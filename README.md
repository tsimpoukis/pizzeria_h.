#include <studio.h>
#include <pthread.h>
#include <unistd.h>
#include <stdlib.h>
#include <time.h>

#define Torderiow 1 //Tis paraggelies sto diastima kai ti elaxistos
#define Torderhigh 3 //o megistos
#define Norderlow 1 //o akeraios arithos apo pitses
#define Norderhigh 5 //o megistos
#define Tpaymentlow 1 //o xronos einai to elaxisto kai h xrewsh
#define Tpaymenthigh 3 //o megistos
#define Cplain 12 //kostos plain 
#define Pfail 0,010 //h pithanotita einai apotuxe tisane xrewseis
#define Tprep 1 //o xronos Kathe pista einai tis paraggelies 
#define Tbake 10 //o xronos einai na psithoun mia mono pista #define Tpack 1 //o upallilos paketarismatos
#define Tdellow 5 //o xronos einai to elaxistos paradwsei enan tuxaio sto diastima 
#define Tdelhigh 15 //o megistos

void *order(void*x);
