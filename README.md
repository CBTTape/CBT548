# CBT548
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 548 is from Alfred Nikolyn and contains some REXX         *   FILE 548
//*           functions, which are especially useful in disk        *   FILE 548
//*           shadowing environments, but which are useful in       *   FILE 548
//*           general.                                              *   FILE 548
//*                                                                 *   FILE 548
//*      These REXX functions were written as supplements for       *   FILE 548
//*      managing PPRC volume pairs.  They will be useful for HDS   *   FILE 548
//*      ShadowImage environments.                                  *   FILE 548
//*                                                                 *   FILE 548
//*      Contact Alfred Nykolyn   apn@istar.ca for any problems     *   FILE 548
//*                                                                 *   FILE 548
//*      RXSIQRY  Returns the state of a PPRC pair                  *   FILE 548
//*               status = RXSIQRY(devN)                            *   FILE 548
//*               States are SIMPLEX, PENDING, DUPLEX, SUSPEND      *   FILE 548
//*                                                                 *   FILE 548
//*      RXV2DEV  Returns the device number of a specified volume   *   FILE 548
//*               devN   = RXV2DEV(VolSer)                          *   FILE 548
//*                                                                 *   FILE 548
//*      RXSLEEP  Sleeps for a specified time                       *   FILE 548
//*                  y   = RXSLEEP(wait)                            *   FILE 548
//*               Another sleep routine using STIMERM.              *   FILE 548
//*               Contrary to popular belief, it is impossible to   *   FILE 548
//*               escape from the wait by trapping the attention    *   FILE 548
//*               with a STAX. The attention exit gains control     *   FILE 548
//*               after the wait time has expired.  This could be   *   FILE 548
//*               done by using multiple TCB's and some tricky      *   FILE 548
//*               logic.  But this is just too complicated.         *   FILE 548
//*                                                                 *   FILE 548
//*      RXWTO    Issue a message to the operator                   *   FILE 548
//*                  y   = RXWTO('Your message')                    *   FILE 548
//*                                                                 *   FILE 548
//*      $ASMCL   JCL to build these functions                      *   FILE 548
//*                                                                 *   FILE 548
```
