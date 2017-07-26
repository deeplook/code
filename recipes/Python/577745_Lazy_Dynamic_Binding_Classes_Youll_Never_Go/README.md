## Lazy Dynamic Binding on Classes (You'll Never Go Back) 
Originally published: 2011-06-11 00:02:36 
Last updated: 2011-08-12 23:42:27 
Author: Eric Snow 
 
This recipe provides a descriptor class and a decorator to make the deferred binding.  Before the first access to that name, the __dict__ of the class will have the descriptor object.  After that first access it will have whatever was returned by the first access.