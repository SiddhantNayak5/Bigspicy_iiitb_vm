# Bigspicy_iiitb_vm
`bigspicy` is a tool for merging circuit descriptions (netlists), generating Spice decks modeling those circuits, generating Spice tests to measure those models, and analyzing the results of running Spice on those tests.

`bigspicy` allows you to combine structural Verilog from a PDK, Spice models of standard cells, a structural Verilog model of some circuit implemented in that PDK, and parasitics extracted into SPEF format. You can then reason about the electrical structure of the design however you want.

`bigspicy` generates Spice decks in `Xyce` format, though this can be extended to other Spice dialects.

Official github repo of BigSpicy: https://github.com/google/bigspicy.git

## Vending Machine
This repository shows the steps for merging the SPEF, verilog and spice netlist into a circuit protobuf and generating the spice file of the design which can further be used to perform various tests and analysis. In this repo, the design of a vending machine is implemented using SKY130 PDKS. The RTL to GDS2 flow of the given design can be referred from the following github repo.

https://github.com/SiddhantNayak5/iiitb_vm
