# Basic summary
This simulator aims to replicate an ecosystem composed of animals, including carnivores (wolves) and herbivores (sheep). Each animal acts as an individual, determining its behavior based on its environment and state, which can range from normal to seeking a mate or fleeing from perceived threats. Reproduction occurs among paired animals, producing offspring with inherited traits. Animals have age and energy limits, defining their lifespan. Simulation progresses in time intervals to update aspects such as age and position of animals.

The environment includes regions providing food to animals, managed by a dedicated manager. Each region offers food based on specific criteria. Simulation runs in steps, removing dead animals, updating the state of the living, and allowing births. The initial world configuration is loaded from a JSON file.

In addition to the aforementioned features, the program also implements a GUI (Graphical User Interface) that allows for detailed analysis of the animals. Users can view several analysis tables, pause and resume the simulation, select a different input JSON file, and modify regions within the ecosystem.
