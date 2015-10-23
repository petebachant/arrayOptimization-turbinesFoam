# arrayOptimization-turbinesFoam

Array optimization using the turbinesFoam actuator line model.


## Principles

* Start with a total budget, enough to purchase ~5 turbines
* Use two turbine models--one CFT and one AFT, which have different costs (`cost_cft = 1.5*cost_aft`?)
* Optimize overall power output with given cost and domain by varying
  * Number and types of turbines
  * Turbine locations
  * Turbine tip speed ratios


### Constraints

* Turbines cannot be within one diameter of each other
* Total cost of all turbines
* Domain size


## License

Code licensed under the MIT license. See `LICENSE` for details.
All other materials licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
Creative Commons Attribution 4.0 International License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" />
</a>
