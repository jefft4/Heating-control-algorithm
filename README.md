# Heating control algorithm
Smart heating control algo for Domoticz

I created this algorithm to control my own heating and hot water system.  The way I've designed it is such that it should be able to handle most heating systems.

It's designed to work with a wide range of system types, valves, etc and its behaviour is quite configurable.  It doesn't try to learn, but it does make smart use of sensors to provide advanced features like pre-heating, time/temperature modulation and weather compensation.

The user guide is the most comprehensive source of information.

The code is in Lua, intended to operate under the dzVents event framework in the Domoticz home automation system (www.domoticz.com).  No doubt someone will convert the code for other systems and languages - Lua isn't the greatest language for this sort of thing so the code is quite simple, no especially fancy tricks.

Let me know how you get on; I will create a thread on the domoticz user forum for people usingthe algo in Domoticz.  If you convert the algo for another automation system, please share it and post me a link.  I'm happy for you to host spin-offs in your own Git repo or to ask me to include them in this repo.

Have fun!

Jeff
