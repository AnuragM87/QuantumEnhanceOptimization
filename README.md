

Quantum-AI Enhanced Ocean Clean-up System



The project tackles ocean Micro plastic pollution by optimising routes for clean-up systems.

NCEI Marine Microplastics product provides access to aggregated global data on microplastics in marine settings. 


https://www.ncei.noaa.gov/products/microplastics 

MAP :https://experience.arcgis.com/experience/b296879cc1984fda833a8acc93e31476/page/Page/?views=Display-Filters%2CMap-Viewer#data_s=id%3AdataSource_1-18cf9a85fdd-layer-4%3A10466

Here the image of a map
points => the location of microplastic in the ocean.



Sample data extracted from above map


OBJECTID
Latitude
Longitude
Microplastics Measurement (density)
Density Class Range
Concentration Class
8854
43.1094
3.1144
0.002
0.0005-0.005
Low
11091
43.0966
5.9917
0.78917
0.005-1
Medium
11092
43.1132
5.9279
1.95013
1-10
High
11093
43.077
5.9792
0.97608
0.005-1
Medium
11123
43.0951
5.9821
0.638818
0.005-1
Medium
11124
43.0779
6.1997
0.171411
0.005-1
Medium
11210
43.2842
5.2766
0.676127
0.005-1
Medium
11211
43.0879
5.7908
0.352637
0.005-1
Medium
11212
43.0941
5.98
0.525459
0.005-1
Medium
11213
43.0726
6.2372
4.75602
1-10
High


Below are few haversine distances measured between points  

Distance between location 1 and 2: 233.59 km
Distance between location 1 and 3: 228.38 km

Note:
Haversine Distance:
Geolocation services: Calculating distances between GPS coordinates.
Navigation: Finding the shortest distance between two points on Earth's surface.
Logistics: Optimizing delivery routes or calculating travel costs.



Microplastic location in ocean based on Latitude and Longitude


Based on the Cleaning system initial location ( can be decided by the cleaning organization) 
We will optimize the cleaning system route with help of Quantum computer , using QAOA 


Using AI model we can predict and pri-inform the cleaning system about weather, ocean current 
Related information.



Q&A 

What is QAOA ?
The Quantum Approximate Optimization Algorithm (QAOA) is a hybrid quantum-classical algorithm designed to solve combinatorial optimization problems. It works by:
Mapping the problem to a cost function (Hamiltonian), where the optimal solution corresponds to the lowest energy state (ground state).
Alternating between two quantum operations:
Cost Hamiltonian evolution (captures the problem constraints).
Mixing Hamiltonian evolution (explores the solution space).
Using a classical optimizer to fine-tune the parameters (γ,β\gamma, \beta) of the quantum circuit to minimize the cost function.
QAOA is particularly well-suited for problems like routing, scheduling, and resource allocation, and it is designed for near-term quantum devices due to its shallow circuit depth and robustness to noise.

Why are we using QAOA ?


Problem Type: Routing is a combinatorial optimization problem, perfectly suited for QAOA.
Efficiency: Finds the shortest, most energy-efficient routes while handling constraints.
Scalability: Adapts to both small and large-scale clean-up operations.

