# Optimizing-Swift-Code
An Xcode 10 project, written in Swift 4.2, companion to [my tutorial](http://iosbrain.com/blog/2018/11/24/using-xcode-instruments-time-profiler-template-to-optimize-swift-code/) on optimizing code using the Instruments Time Profile.

In my tutorial, we're going to use Xcode Instruments' _Time Profiler_ to analyze the performance of this sample app's code. In simplest of terms, _Time Profiler_ collects information about your app while it's running, determines you how long each of your functions takes to run, and also figures out the percentage of CPU cycles each of your functions is using. It gathers the same data about iOS SDK functions. The percentage of CPU cycles from 0% to 100% at each sample point is shown over time on a graph called the "timeline" or "track." There are multiple tracks. The top track aggregates all the data from all individual thread and CPU core tracks. The _Time Profiler_ is a very powerful tool as it shows your app's performance in real time, thus reflecting surges or lulls in CPU usage. We'll walk through an example. Please [join me](http://iosbrain.com/blog/2018/11/24/using-xcode-instruments-time-profiler-template-to-optimize-swift-code/)...

-------
Copyright (c) 2018 Andrew L. Jaffee, microIT Infrastructure, LLC, and iosbrain.com.

