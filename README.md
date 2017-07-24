Plotting Accelerometer Values in ShinobiCharts for Android
=====================
This is a demo project that demonstrates how to plot the accelerometer readings from the motion sensor onto a ShinobiChart. There's an accompanying blog post [here](http://www.shinobicontrols.com/blog/posts/2014/02/03/building-a-streaming-chart-in-android).

![Screenshot](screenshot.png?raw=true)

There's also an [iOS version of this project](https://github.com/ShinobiControls/charts-accelerometer-visualisation).

Building the project
------------------

In order to build this project you'll need a copy of ShinobiCharts for Android. If you don't have it yet, you can download a free trial from the [ShinobiCharts for Android website](http://www.shinobicontrols.com/android/).

* **Using Eclipse**

	If you haven't already set up ShinobiCharts as an Android library in your Eclipse workspace, there are instructions in our [quick start guide](http://www.shinobicontrols.com/android/shinobicharts/quickstartguide/import-the-library/). Once the library is in place, and you've cloned or downloaded this repo, click File > New > Other… > "Android Project from Existing Code", then point it at the root directory of your download. 

	Once you've opened up the project, open up its Properties dialog, and in the Android section, add a library reference to your own Shinobi library.

* **Using Android Studio**
	
	We don't officially support Android Studio yet, but if you really want to give it a go, have a look at [this blog post](http://www.shinobicontrols.com/blog/posts/2013/12/10/using-shinobicharts-with-android-studio/).

If you're using the trial version you'll need to add your trial key. To do so, open up AccelerometerActivity.java and add the following line after the chart has been created (replacing the placeholder with your trial key):

    shinobiChart.setTrialKey("your trial key");
    
You should now be able to build the project and run it. Try it on a real device rather than an emulator, twist and turn it, and watch the graph appear!
    
Contributing
------------

We'd love to see your contributions to this project - please go ahead and fork it and send us a pull request when you're done! Or if you have a new project you think we should include here, email info@shinobicontrols.com to tell us about it.

License
-------

The [Apache License, Version 2.0](license.txt) applies to everything in this repository, and will apply to any user contributions.

