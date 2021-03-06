# A Primer on Monte Carlo Methods
## Author: Andrew Garcia

Copyright 2019 Andrew Garcia

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## mc_simple.py
Simple Monte Carlo **mc_simple.py**: Sample inputs from their corresponding random distributions to generate output distribution.

<img src="mc_simple_Figure_1.png" alt="drawing" width="350"/>
<img src="mc_simple_Figure_2.png" alt="drawing" width="350"/>


## monte_hall.py
Simulating Monte Hall problem through conditional selection (Monte Carlo algorithm)

<img src="montehall_Figure_1.png" alt="drawing" width="350"/>
<img src="montehall_Figure_2.png" alt="drawing" width="350"/>

## montemarathon.py
The rejection sampling criterion:


U = [random number from uniform distribution (0,1)]

P(x) = Probability density function (e.g. ~ exp(-x**2))

**if** P(x) > U

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;accept x (label with blue)

**else**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;reject x (label with orange)

<img src="rejs_Figure_1.png" alt="drawing" width="350"/>


can be understood to be based on the premise that sampling "U" values above those of a probability distribution of a certain event do not constitute a part of said event and are thus rejected.

Example: Marathon Race Outcomes under different strategies (run-jog-run/jog)

<img src="montemarathon_Figure_1.png" alt="drawing" width="350"/>
