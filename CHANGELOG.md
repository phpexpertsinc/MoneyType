## v2.0.0: 2019-04-13

* **[2019-04-13]** [Major] Implemented strict_types so that precision is guaranteed. (#11)
* **[2019-04-13]** Added NumberHelper::assertIsNumeric() to enforce number-like values. (#10)
* **[2019-04-13]** Added arbitrary precision for converting decimals to lossless integers. (#9)
* **[2019-04-13]** [Major] Internalized the calculation strategy classes. (#7)
* **[2019-04-13]** [minor] Made pratically every class `final` to protected against bad devs. (#6)
* **[2019-04-13]** [minor] Upgraded to PHPUnit 8.0. (#8)

## v1.6.1: 2019-04-12

* **[2019-04-12]** Added a NumberHelper::isFloatLike() check utility. (#4)

# v1.6.0: 2019-04-10

* [Major] Added ::getWithFullPrecision() for seeing the whole number. 

## v1.5.0: A whole lot of goodness.  2019-04-10 

* [Major] Definitely require PHP 7.2, and BCMath for dev.
* [Major] (#1) Completely reimplemented bcround() and fixed serious bugs.
* [Major] Fixed the precision problems in BCMathCalcStrategy.
* [Major] Fixed the precision problems in NativeCalcStrategy.
* [Major] Added a whole bunch of type saftey to modding native numbers.
* [Major] Added 100% Unit Test code coverage. Hurray!
* [Major] Added the I_AM_A_DUMMY functionality to NativeCalc->modulus().
* [minor] Fixed the copyright headers.
* [minor] Added a mechanism to dynamically test whether extension paths work.
* [minor] Added functionality to find out what strategy Money is using.
* Reimplemented NativeCalcStrat's compare().
* Added phpstan and fixed every type discrepancy.
* Added TravisCI support.
