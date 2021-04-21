## PowerTransformer

Adapted from CIM and https://github.com/smart-data-models/dataModel.EnergyCIM/ data models: An electrical device consisting of two or more coupled windings, with or without a magnetic core, for introducing mutual coupling between electric circuits. Transformers can be used to control voltage and phase shift (active power flow). 

A power transformer may be composed of separate transformer tanks that need not be identical. 

A power transformer can be modeled with or without tanks and is intended for use in both balanced and unbalanced representations. A power transformer typically has two terminals, but may have one (grounding), three or more terminals. 

The inherited association ConductingEquipment.BaseVoltage should not be used.  The association from TransformerEnd to BaseVoltage should be used instead.
