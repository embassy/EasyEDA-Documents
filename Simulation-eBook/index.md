# Simulation eBook

- [Introduction](./introduction.htm#Introduction)
    - [What this book is for](./introduction.htm#What-this-book-is-for)
    - [What this book is not for](./introduction.htm#What-this-book-is-not-for)
    - [Who this book is for](./introduction.htm#Who-this-book-is-for)
    - [How the book is structured](./introduction.htm#How-the-book-is-structured)
- [Introductory concepts of Spice simulation](./introductory-concepts-of-spice-simulation.htm#Introductory-concepts-of-Spice-simulation)
- [About naming conventions](./About-naming-conventions.htm#About-naming-conventions)
- [Introduction to using a simulator](./Introduction-to-using-a-simulator.htm#Introduction-to-using-a-simulator)
    - [Avoiding common mistakes](./Introduction-to-using-a-simulator.htm#Avoiding-common-mistakes)
        - [Prefix conflict error](./Introduction-to-using-a-simulator.htm#Prefix-conflict-error)
        - [All simulation circuits MUST have a ground node](./Introduction-to-using-a-simulator.htm#All-simulation-circuits-MUST-have-a-ground-node)
        - [All simulation circuits MUST have a power and/or signal source](./Introduction-to-using-a-simulator.htm#All-simulation-circuits-MUST-have-a-power-and-or-signal-source)
        - [Every point in a simulation schematic MUST have a DC path to ground](./Introduction-to-using-a-simulator.htm#Every-point-in-a-simulation-schematic-MUST-have-a-DC-path-to-ground)
            - [Values and DC paths of RLC components](./Introduction-to-using-a-simulator.htm#Values-and-DC-paths-of-RLC-components)
            - [The effects of adding DC paths](./Introduction-to-using-a-simulator.htm#The-effects-of-adding-DC-paths)
            - [Common problems with DC paths](./Introduction-to-using-a-simulator.htm#Common-problems-with-DC-paths)
        - [Components are connected by netnames](./Introduction-to-using-a-simulator.htm#Components-are-connected-by-netnames)
        - [Probing signals](./Introduction-to-using-a-simulator.htm#Probing-signals)
            - [Probing voltages](./Introduction-to-using-a-simulator.htm#Probing-voltages)
            - [Probing currents](./Introduction-to-using-a-simulator.htm#Probing-currents)
- [Configuring Voltage and Current Sources](./Configuring-Voltage-and-Current-Sources.htm#Configuring-Voltage-and-Current-Sources)
    - [Configuring the SIN or SINE option](./Configuring-Voltage-and-Current-Sources.htm#Configuring-the-SIN-or-SINE-option)
    - [More ways to use the SIN (or SINE) option](./Configuring-Voltage-and-Current-Sources.htm#More-ways-to-use-the-SIN-or-SINE-option)
    - [Configuring the PULSE option](./Configuring-Voltage-and-Current-Sources.htm#Configuring-the-PULSE-option)
    - [More ways to use the PULSE option](./Configuring-Voltage-and-Current-Sources.htm#More-ways-to-use-the-PULSE-option)
    - [Configuring the EXP option](./Configuring-Voltage-and-Current-Sources.htm#Configuring-the-EXP-option)
    - [Configuring the SFFM option](./Configuring-Voltage-and-Current-Sources.htm#Configuring-the-SFFM-option)
    - [Configuring the AM option](./Configuring-Voltage-and-Current-Sources.htm#Configuring-the-AM-option)
    - [Configuring the PWL option](./Configuring-Voltage-and-Current-Sources.htm#Configuring-the-PWL-option)
    - [Configuring the AC source option](./Configuring-Voltage-and-Current-Sources.htm#Configuring-the-AC-source-option)
- [Setting up Analyses](./Setting-up-Analyses.htm#Setting-up-Analyses)
    - [What are Analyses?](./Setting-up-Analyses.htm#What-are-Analyses)
        - [SPICE Analyses available from the Green Man / Simulate... button](./Setting-up-Analyses.htm#SPICE-Analyses-available-from-the-Green-Man-Simulate-button)
        - [SPICE Analyses and Control Statement Syntax](./Setting-up-Analyses.htm#SPICE-Analyses-and-Control-Statement-Syntax)
            - [1) OP: Perform an Operating Point Analysis](./Setting-up-Analyses.htm#1-OP-Perform-an-Operating-Point-Analysis)
            - [2) TF: Perform a DC Transfer Function Analysis](./Setting-up-Analyses.htm#2-TF-Perform-a-DC-Transfer-Function-Analysis)
            - [3) DC: Perform a DC-Sweep Analysis](./Setting-up-Analyses.htm#3-DC-Perform-a-DC-Sweep-Analysis)
            - [4) AC: Perform a Small-Signal AC (frequency domain) Analysis](./Setting-up-Analyses.htm#4-AC-Perform-a-Small-Signal-AC-frequency-domain-Analysis)
            - [5) TRAN: Perform a Transient (time domain) Analysis](./Setting-up-Analyses.htm#5-TRAN-Perform-a-Transient-time-domain-Analysis)
            - [IC: Set Initial Conditions](./Setting-up-Analyses.htm#IC-Set-Initial-Conditions)
- [Initial conditions and starting up circuits](./Initial-conditions-and-starting-up-circuits.htm#Initial-conditions-and-starting-up-circuits)
    - [Some background and basic start-up techniques](./Initial-conditions-and-starting-up-circuits.htm#Some-background-and-basic-start-up-techniques)
    - [Setting initial voltages on nets and currents through components](./Initial-conditions-and-starting-up-circuits.htm#Setting-initial-voltages-on-nets-and-currents-through-components)
        - [Using the ic spice directive](./Initial-conditions-and-starting-up-circuits.htm#Using-the-ic-spice-directive)
        - [Using a current source to set an initial current through an inductor](./Initial-conditions-and-starting-up-circuits.htm#Using-a-current-source-to-set-an-initial-current-through-an-inductor)
        - [Setting a capacitor voltage using an XSPICE capacitor model](./Initial-conditions-and-starting-up-circuits.htm#Setting-a-capacitor-voltage-using-an-XSPICE-capacitor-model)
        - [Setting an inductor current using an XSPICE inductor model](./Initial-conditions-and-starting-up-circuits.htm#Setting-an-inductor-current-using-an-XSPICE-inductor-model)
    - [Using a 1V source to help start-up](./Initial-conditions-and-starting-up-circuits.htm#Using-a-1V-source-to-help-start-up)
    - [Replacing ideal and Thevenin voltage sources with band-limited Norton Sources to help start-up](./Initial-conditions-and-starting-up-circuits.htm#Replacing-ideal-and-Thevenin-voltage-sources-with-band-limited-Norton-Sources-to-help-start-up)
    - [Using the 'OFF' option to help start-up](./Initial-conditions-and-starting-up-circuits.htm#Using-the-OFF-option-to-help-start-up)
- [Expressions](./Expressions.htm#Expressions)
    - [Operators](./Expressions.htm#Operators)
    - [Using Expressions to define component values](./Expressions.htm#Using-Expressions-to-define-component-values)
    - [Using Expressions to configure voltage and current sources](./Expressions.htm#Using-Expressions-to-configure-voltage-and-current-sources)
- [Parameters](./Parameters.htm#Parameters)
    - [Using parameters in expressions](./Parameters.htm#Using-parameters-in-expressions)
- [Functions](./Functions.htm#Functions)
    - [Predefined functions](./Functions.htm#Predefined-functions)
        - [Table of functions](./Functions.htm#Table-of-functions)
    - [User defined functions](./Functions.htm#User-defined-functions)
- [B sources spice simulation](./B-sources.htm#B-sources-spice-simulation)
- [Device models](./Device-models.htm#Device-models)
    - [Why are there different models for the same device?](./Device-models.htm#Why-are-there-different-models-for-the-same-device)
    - [.model statements](./Device-models.htm#model-statements)
        - [Ngspice model types](./Device-models.htm#Ngspice-model-types)
    - [.subckt definitions](./Device-models.htm#subckt-definitions)
    - [Behavioural models](./Device-models.htm#Behavioural-models)
    - [What if there is no model available for a device?](./Device-models.htm#What-if-there-is-no-model-available-for-a-device)
    - [The relationship between spice models and device datasheets](./Device-models.htm#The-relationship-between-spice-models-and-device-datasheets)
    - [The relationship between spice models and real world behaviour](./Device-models.htm#The-relationship-between-spice-models-and-real-world-behaviour)
    - [How to change the model attached to a symbol](./Device-models.htm#How-to-change-the-model-attached-to-a-symbol)
- [Schematic symbols: prefixes and pin numbers](./Schematic-symbols-prefixes-and-pin-numbers.htm#Schematic-symbols-prefixes-and-pin-numbers)
    - [PCB and Spice Prefix](./Schematic-symbols-prefixes-and-pin-numbers.htm#PCB-and-Spice-Prefix)
    - [PCB and Spice pin numbers](./Schematic-symbols-prefixes-and-pin-numbers.htm#PCB-and-Spice-pin-numbers)
        - [For .MODEL defined models](./Schematic-symbols-prefixes-and-pin-numbers.htm#For-MODEL-defined-models)
        - [For .SUBCKT defined models](./Schematic-symbols-prefixes-and-pin-numbers.htm#For-SUBCKT-defined-models)
        - [Attaching models to custom symbols](./Schematic-symbols-prefixes-and-pin-numbers.htm#Attaching-models-to-custom-symbols)
- [Custom modelling](./Custom-modelling.htm#Custom-modelling)
- [Making measurements of simulation results](./Making-measurements-of-simulation-results.htm#Making-measurements-of-simulation-results)
        - [Using the WaveForm display cursors](./Making-measurements-of-simulation-results.htm#Using-the-WaveForm-display-cursors)
        - [Using the meas command](./Making-measurements-of-simulation-results.htm#Using-the-meas-command)
    - [The meaning of terms in MEAS commands](./Making-measurements-of-simulation-results.htm#The-meaning-of-terms-in-MEAS-commands)
    - [Examples of the forms and syntaxes of MEAS commands](./Making-measurements-of-simulation-results.htm#Examples-of-the-forms-and-syntaxes-of-MEAS-commands)
        - [Trig Targ](./Making-measurements-of-simulation-results.htm#Trig-Targ)
        - [Find ... When](./Making-measurements-of-simulation-results.htm#Find-When)
        - [AVG | MIN | MAX | PP | RMS | MIN_AT | MAX_AT](./Making-measurements-of-simulation-results.htm#AVG-MIN-MAX-PP-RMS-MIN_AT-MAX_AT)
        - [INTEG](./Making-measurements-of-simulation-results.htm#INTEG)
        - [DERIV](./Making-measurements-of-simulation-results.htm#DERIV)
        - [More measure statements](./Making-measurements-of-simulation-results.htm#More-measure-statements)
