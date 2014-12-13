scala-highcharts
================

Highcharts wrapper in Scala

Now with repl support!

![Line Chart](https://github.com/quantifind/scala-highcharts/blob/master/images/line.png)

generated by

```
austin-2:scala-highcharts austin$ sbt 'project poppy' console
[info] Loading project definition from /Users/austin/IdeaProjects/scala-highcharts/project
[info] Set current project to scala-highcharts (in build file:/Users/austin/IdeaProjects/scala-highcharts/)
[info] Set current project to Poppy (in build file:/Users/austin/IdeaProjects/scala-highcharts/)
[info] Starting scala interpreter...
[info]
Welcome to Scala version 2.10.3 (Java HotSpot(TM) 64-Bit Server VM, Java 1.7.0_25).
Type in expressions to have them evaluated.
Type :help for more information.

scala> import com.qf.charts.repl.Highcharts._
import com.qf.charts.repl.Highcharts._

scala> line((1 to 10), (1 to 10))
serving resources from: file:/Users/austin/IdeaProjects/scala-highcharts/index-1418179288496.html
2014-12-09 18:41:29.188:INFO:oejs.Server:jetty-7.6.0.v20120127
2014-12-09 18:41:29.216:INFO:oejsh.ContextHandler:started o.e.j.s.ServletContextHandler{/,file:/Users/austin/IdeaProjects/scala-highcharts/index-1418179288496.html}
2014-12-09 18:41:29.225:INFO:oejs.AbstractConnector:Started SocketConnector@0.0.0.0:53495
Server started: http://172.20.10.2:53495/index-1418179288496.html
Output written to http://172.20.10.2:53495 (CMD + Click link in Mac OSX).
res0: com.qf.charts.highcharts.Highchart = Highchart(List(Series(Vector(Data(1,1,None,None), Data(2,2,None,None), Data(3,3,None,None), Data(4,4,None,None), Data(5,5,None,None), Data(6,6,None,None), Data(7,7,None,None), Data(8,8,None,None), Data(9,9,None,None), Data(10,10,None,None)),None,None,None,Some(line),None,None,None,None,series)),Some(Title(,None,None,None,None,None,None,None,title)),None,None,Some(Credits(None,,None,None,)),Some(Exporting(chart,None,None,None,None,None,None)),Some(Legend(None,None,None,Some(false),None,None,None,None,None,None,None,None,None,None,None,None,None,None,None,None,None)),None,true,None,None,Some([Lcom.qf.charts.highcharts.Axis;@40dc66ae))

scala>
```

Future Tasks
============

* ~~Undo / Redo~~
* Vega, D3, JFreeChart support
* Open-Source!
* Maven Managed Dependency
* Local mode refresh code
* Zoom
* ~~Iterable[Tuple2]~~
* Common-use-cases: ie ~~least-squares-regression support~~
* Common plots - bubble charts, geomap (highcharts? vega?)
* Documentation + Testing
* Highcharts coverage percentage?
* Consistent naming: Highchart vs Highcharts?


Highcharts
==========

[Highcharts](http://www.highcharts.com/) is available freely for non-commercial use. Contact highcharts directly for commercial licensing.

