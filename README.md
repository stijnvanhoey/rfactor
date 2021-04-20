R-factor
========

The $R$-factor is a measure used in erosion and (overland) sediment
modelling to quantify the effect of rainfall on soil erosion. It is
typically defined in the context of the RUSLE equation, in which gross
erosion for an agricultural parcel is estimated (see, for example,
[here](https://docs.fluves.net/cnws-pascal//)).

Specifically, the $R$-factor is a measure for the total erosivity of a
number of rainfall events within a defined timeframe (year, month,
number of days). The factor is computed by calculating the erosivity for
every rainfall event in a timeseries, and taking the sum of the
erosivity of all events in one year. These yearly values can be used to
compute an average value, the R-factor, presenting the rainfall
erosivity for a given period. An in-depth explanation of the formula's
is given here \<rfactor\>.

Get started
-----------

This package makes use of `Python` (and a limited number of dependencies
such as Pandas and Numpy) and `Matlab`. The installation (see
here \<installation\>) is managed by making use of `Miniconda`:
<https://docs.conda.io/en/latest/miniconda.html>. Make sure to check out
the installation instructions, and follow the example in the
Get started \<getstarted\> page.

> **note**
>
> A Python version of the Matlab code is being developed, and is expected to
> :   be released in the next version of this code.
>
Rainfall and erosivity data
---------------------------

**TODO**

Contact
-------

We encourage user to submit question, suggestions and bug reports via
the issues platform on GitHub **TO DO**. In case of other questions, one
mail to **TODO**.

License
-------
This project is licensed under the GNU General Public License v3.0.

Powered by
----------

![image](../docs/_static/png/DepartementOmgeving_logo.png)

![image](../docs/_static/png/KULeuven_logo.png)

![image](../docs/_static/png/VMM_logo.png)

![image](../docs/_static/png/fluves_logo.png)

Note
----

This project has been set up using PyScaffold 3.2.3. For details and
usage information on PyScaffold see <https://pyscaffold.org/>.
