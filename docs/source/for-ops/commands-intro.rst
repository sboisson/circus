.. _commands:

Commands
########

At the epicenter of circus lives the command systems.  *circusctl* is just a
zeromq client, and if needed you can drive programmaticaly the Circus system by
writing your own zmq client.

All messages are JSON mappings.

For each command below, we provide a usage example with circusctl but also the
input / output zmq messages.

.. The actual list of commands is generated by the docs/circus_ext.py file.  
   It will append the list of commands to the content above.  Documentation 
   contributors can safely edit the text above this comment when making
   improvements.
