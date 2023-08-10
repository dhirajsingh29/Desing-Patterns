> *Identify the aspects of your application that vary and separate them from what stays the same.*
> - If we have got some aspect of our code that is changing, say with every new requirement, then we know we have got a behavior that needs to be pulled out and separated from all the stuff that doesn't change.
> - Take the part that vary and encapsulate them, so that later we can alter or extend the parts that vary without affecting those that don't.

> *Program to an interface, not an implementation*
> - It will help us change behavior at runtime.
> - We can add / remove any behavior without modifying existing one.

> *Favor composition over inheritance*
> - Instead of inheriting behavior (is-a relationship), we opt for composition (has-a relationship).
> - This helps in delagating the task to correct behavior, rather than implementing the behavior on its own.