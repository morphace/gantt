# Gantt Chart Add-on for Vaadin 7

Gantt is an UI component add-on for Vaadin 7.

You can read more about Gantt charts in general from here: http://en.wikipedia.org/wiki/Gantt_chart. 

Download latest release jar from http://vaadin.com/directory#addon/gantt

List of features that are supported:
* Server side API allows to modify timeline options and step options like start/end date, caption, color and adding/removing steps
* adjustable timeline range
* timeline supports Hour, Day and Week resolutions 
* modify step's start date and end date by dragging and moving the step (move and resize events)
* scrolling enabled horizontally and vertically for a large chart content
* scales the small timeline and content width up to fit in the space available
* touch support (experimental)

Techincal details:
* server side class name is Gantt, it extends AbstractComponent
* client side connector class name is GanttConnector
* client side widgets (pure GWT) are 
	* GanttWidget, which is the main widget that connector uses 
	* TimelineWidget, which is a standalone widget.

Tested to work with following browsers: 
* IE 8, 9, 10, 11
* Firefox
* Chrome
* Safari


## Demo

Online demo available @ http://tomivirtanen.app.fi/gantt-demo/

Code can be found under /gantt-demo folder.

## Building and running demo

* git clone <url of the Gantt repository>
* mvn clean install
* cd gantt-demo
* mvn jetty:run

To see the demo, navigate to http://localhost:8080/gantt-demo


## License & Author

Add-on is distributed under Apache License 2.0. For license terms, see LICENSE.txt.

Gantt is written by Tomi Virtanen

