# [Benchmarking](https://en.wikipedia.org/wiki/Benchmarking) ([Profile](https://en.wikipedia.org/wiki/Profiling_(computer_programming)))

## RAW Goal/Question/Metric

* GOAL - To have a clear understanding on the performance impact/difference between coresponding implementations of the same feature in Native and Hybrid implementations.
  * Question 1 - What is the technology impact on RAM allocation?
  * Question 2 - What is the technology impact on CPU usage?
  * Question 3 - What is the technology impact on energy consumption of the device?
  * Question 4 - What is the technology impact on network usage?
  * Question 5 - What is the technology impact on the duration of a specific task?

### Android Profiling

* [Main Article](https://developer.android.com/studio/profile/index.html)
* [General Performance](https://developer.android.com/studio/profile/android-profiler.html)
* [RAM](https://developer.android.com/studio/profile/memory-profiler.html)
* [Network](https://developer.android.com/studio/profile/network-profiler.html)
* [Battery](https://developer.android.com/studio/profile/battery-historian.html)

### iOS Source

* [Main Article](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/index.html#//apple_ref/doc/uid/TP40004652-CH3-SW1)
* [General Performance](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/MeasuringCPUUse.html#//apple_ref/doc/uid/TP40004652-CH84-SW1)
* [RAM](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/MonitoringMemoryUsage.html#//apple_ref/doc/uid/TP40004652-CH33-SW1)
* [Network](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/MeasuringIO.html#//apple_ref/doc/uid/TP40004652-CH83-SW1)
* [Energy Impact](https://developer.apple.com/library/content/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/MeasuringEnergyImpact.html#//apple_ref/doc/uid/TP40004652-CH34-SW1)

### Pre built binary profiling

* [Android APK](https://developer.android.com/studio/debug/apk-debugger.html)

### Measure Template (focus on iteration)

* Tool used: Specify what tool was used to perform the measurement e.g Android studio memory profiler
* Simulator/Device: e.g iOS SIMULATOR iphone6s, DEVICE iPhone 7PLUS, SIMULATOR Nexus 5, DEVICE Galaxy S8.
* Native or Hybrid? e.g iOS Swift, Android ionic javascript ,e.g React Native, e.g React nonnative.
* Operating system: Must describe the exact version of the operating system installed, it should be easily installed/found by other developer , e.g. iOS11.2.12, Android 27 v4.5.
* Step-by-step: Describe all the steps necessary to **EXACTLY** reproduce the measurement including all the steps necessary since the start of the application to get to the point of starting the profile. The profile step-by-step must include also BEGIN(point where you start the profiling), MEASURE1(point where you get a value), MEASURE2 ( another point where you get a value if necessary), MEASURE-N, END(point where you stop profiling).
* Values obtained: Repeat the benchmark as many times needed (Can be in table form)

## Real Sample Measurements

In progress
