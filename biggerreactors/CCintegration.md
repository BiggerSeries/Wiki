

**Computer ports**
<img style="float: left;" src="/biggerreactors/reactor/reactor_computer_port.png"></img>
<img style="float: middle;" src="/biggerreactors/turbine/turbine_computer_port.png"></img>
<img style="float: right;" src="/biggerreactors/heat_exchanger/heat_exchanger_computer_port.png"></img>

The Computer ports for the reactor, turbine, and heat exchanger allow for users to monitor and control their entire Bigger Reactors based power generation system. For those who are familliar with big reactors, the peripheral names have changed only slightly, to `"BiggerReactors_Reactor"`, `"BiggerReactors_Turbine"`, and  `"BiggerReactors_Heat-Exchanger"`.

The below is simple going to be a commands list dump, not a tutorial *currently*

## Commands list

**Reactor commands**

| main command | sub commands | return |
| --- | --- | --- |
| .active() | --- | true/false |
| .ambientTemperature() | --- | *value* |
| .apiVersion() | --- | *value* |
| .battery() | 3 | *nil* if using active cooling |
| --- | .capacity() | *value* |
| --- | .producedLastTick() | *value* |
| --- | .stored() | *value* |
| .casingTemperature() | --- | *value* |
| .connected() | --- | true/false |
| .controlRodCount() | --- | *value* |
| .coolantTank() | 6 | *nil* if using passive cooling |
| --- | .capacity() | *value* |
| --- | .coldFluidAmount() | *value* |
| --- | .dump() | none, dumps coolant |
| --- | .hotFluidAmount() | *value* |
| --- | .maxTransitionedLastTick() | *value* |
| --- | .transitionedLastTick() | *value* |
| .fuelTank() | 7 | --- |
| --- | .burnedLastTick() | *value* |
| --- | .capacity() | *value* |
| --- | .ejectWaste() | none, ejects waste |
| --- | .fuel() | *value* |
| --- | .fuelReactivity() | *value* |
| --- | .totalReactant() | *value* |
| --- | .waste() | *value* |
| .fuelTemperature() | --- | *value* |
| .getControlRod(*value*) | 6 | --- |
| --- | .index() | *value* |
| --- | .level() | *value* |
| --- | .name() | *string* |
| --- | .setLevel(*value*) | --- |
| --- | .setName(*string*) | --- |
| --- | .valid() | true/false |
| .setActive(true/false) | --- | --- |
| .setAllControlRodLevels(*value*) | --- | --- |
| .stackTemperature() | --- | *value* |

**notes**
- the dump command was added in Bir version 1.18.2-0.6.0-beta.1.3

**Turbine commands**

| main command | sub commands | return |
| --- | --- | --- |
| .active() | --- | true/false |
| .apiVersion() | --- | *value* |
| .battery() | 3 | --- |
| --- | .capacity() |
| --- | .producedLastTick() |
| --- | .stored() |
| .coilEngaged() | --- | true/false |
| .connected() | --- | true/false |
| .fluidTank() | 6 | --- |
| --- | .flowLastTick() | *value* |
| --- | .flowRateLimit() | *value* |
| --- | .nominalFlowRate() | *value* |
| --- | .setNominalFlowRate(*value*) | --- |
| .fluidTank().input() | 3 | --- |
| --- | .amount() | *value* |
| --- | .maxAmount() | *value* |
| --- | .name() | *string* |
| .fluidTank().output() | 3 | --- |
| --- | .amount() | *value* |
| --- | .maxAmount() | *value* |
| --- | .name() | *string* |
| .rotor() | 2 | --- |
| --- | .RPM() | *value* |
| --- | .efficiencyLastTick() | *value* |
| .setActive(true/false) | --- | --- |
| .setCoilEngaged(true/false) | --- | --- |

**notes**
- none

**Heat Exchanger commands**

| main command | sub commands | return |
| --- | --- | --- |
| .ambientInternalRFKT() | --- | *value* |
| .ambientTemperature() | --- | *value* |
| .apiVersion() | --- | *value* |
| .condenser() | 8 | --- |
| --- | .dump() | --- |
| --- | .maxTransitionedLastTick() | *value* |
| --- | .rfPerKelvin() | *value* |
| --- | .temperature() | *value* |
| --- | .transitionedEnergy() | *value* |
| --- | .transitionedLastTick() | *value* |
| .condenser().input() | 3 | --- |
| --- | .amount() | *value* |
| --- | .maxAmount() | *value* |
| --- | .name() | *string* |
| .condenser().output() | 3 | --- |
| --- | .amount() | *value* |
| --- | .maxAmount() | *value* |
| --- | .name() | *string* |
| .condensorEvaporatorRFKT() | --- | *value* |
| .condensorInternalRFKT() | --- | *value* |
| .connected() | --- | true/false |
| .evaporator() | 8 | --- |
| --- | .dump() | --- |
| --- | .maxTransitionedLastTick() | *value* |
| --- | .rfPerKelvin() | *value* |
| --- | .temperature() | *value* |
| --- | .transitionedEnergy() | *value* |
| --- | .transitionedLastTick() | *value* |
| .evaporator().input() | 3 | --- |
| --- | .amount() | *value* |
| --- | .maxAmount() | *value* |
| --- | .name() | *string* |
| .evaporator().output() | 3 | --- |
| --- | .amount() | *value* |
| --- | .maxAmount() | *value* |
| --- | .name() | *string* |
| .evaporatorInternalRFKT() | --- | *value* |
| .internalEnvironment() | 2 | --- |
| --- | .rfPerKelvin() | *value* |
| --- | .temperature() | *value* |

**notes**
- the dump command was added in Bir version 1.18.2-0.6.0-beta.1.3



self notes
[](https://github.com/BiggerSeries/BiggerReactors/blob/1.18/src/main/java/net/roguelogix/biggerreactors/multiblocks/reactor/deps/ReactorPeripheral.java)
[](https://github.com/BiggerSeries/BiggerReactors/blob/1.18/src/main/java/net/roguelogix/biggerreactors/multiblocks/heatexchanger/deps/HeatExchangerPeripheral.java)
[](https://github.com/BiggerSeries/BiggerReactors/blob/1.18/src/main/java/net/roguelogix/biggerreactors/multiblocks/turbine/deps/TurbinePeripheral.java)

