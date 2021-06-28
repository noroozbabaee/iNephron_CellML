Components
----------
The main CellML components are:

- To generate the required variables, which will be considered an input for the NHE3 exchanger, the following component is used: <Generator.cellml>.
- NHE3 exchanger formulated, based on Weinstein's work in 1995: "Kinetically Defined Na +/H + Antiporter
  within a Mathematical Model of the Rat Proximal Tubule". The CellML code is available  in <NHE3.cellml>. 
  The constant parameters are updated according to  Weinstein's work in 2007: 
  "Flow-dependent transport in a mathematical model of rat proximal tubule".
- Parameters specified for NHE3 antiporter from Weinstein 2007 in components <Weinstein_NHE3_2007.cellml>.
- To run the experiment, go to <experiment_NHE3.cellml>.