# Subo
Subo is a Javascript client-side Web user interface framework that exploits a combination of the Presentation-abstraction-control (PAC), state machine and portlet patterns. A Subo application is a hierarchy of controller-state-machines that run in your browser window. Each controller has an HTML view, a data model, and zero or more child controllers. These are switched on state transitions: on entry, each state activates for its controller a different view, model, and set of child controllers. A view can embed views of child controllers. When a controller receives an event from it's current view, it can update its model, transition, or fire control events up or down the hierarchy. On receiving a control event, the recipient controller can perform a model update, transition or fire further control events, and so on. A Subo application doesn't necessarily need a server, but you can connect it to one if you wish via service objects.

## More Information
Get downloads and play with a couple of demos at: [Subo Home][subo-home]

## Author

Subo is written by [Lindsay Kay][neocoders-github]. Lindsay has a skunkworks at [http://www.xeolabs.com][xeolabs.com] where you can find more of this kind of stuff.

[subo-home]: http://www.xeolabs.com/portal/projects/subo
[xeolabs-github]: http://github.com/xeolabs
[xeolabs.com]: http://www.xeolabs.com

