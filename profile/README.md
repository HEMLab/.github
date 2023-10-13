# HEMLab
Initiated by Professor [Qiuhua Liang](https://www.lboro.ac.uk/departments/abce/staff/qiuhua-liang/), **[Hydro-Environmental Modelling Labarotory](http://www.hemlab.org)**, is a rsearch team with members from different research organisations, interested in development and application of high-performance modelling and data analytics tools to support natural hazard risk assessment and management.

Working at the forefront of computational and data technologies, we develop new numerical methods and models for simulating flooding and the associated transport processes, including sediment dynamics, hydro-geomorphological change, floating debris and pollutant transport, using the latest high-performance computing technology based on graphics processing units (GPUs).

The high-performance numerical methods and models are adapted and applied to simulate other types of natural hazards, including dam-break floods, tsunamis, storm surges, flow-like landslides and debris flows.

# HiPIMS Tree
The ‘HiPIMS Tree’ illustrates the brief development history of HiPIMS and the integrated modelling components.
![HiPIMS development tree](./profile/img/tree.png)

## References
[1] Solving the full shallow water equations (SWEs) on dynamically adaptive quadtree grids
-	[Liang Q, Borthwick AGL, Stelling G (2004) Simulation of Dam and Dyke-break Hydrodynamics on Dynamically Adaptive Quadtree Grids. International Journal for Numerical Methods in Fluids, 46: 127-162.](https://doi.org/10.1002/fld.748)
-	[Liang Q, Du G, Hall JW, Borthwick AGL (2008) Flood Inundation Modelling with an Adaptive Quadtree Grid Shallow Water Equation Solver. ASCE - Journal of Hydraulic Engineering, 134(11): 1603-1610.](https://doi.org/10.1061/(ASCE)0733-9429(2008)134:11(1603))

[2] Solving the SWEs on a new simplified adaptive grid system
-	[Liang Q (2012) A simplified adaptive Cartesian grid system for solving the 2D shallow water equations. International Journal for Numerical Methods in Fluids, 69(2): 442-458.](https://doi.org/10.1002/fld.2568)

[3] NewChan based on pre-balanced SWEs and new schemes for complex topography & wetting/drying
-	[Liang Q (2008) Simulation of Shallow Flows in Nonuniform Open Channels. ASME – Journal of Fluids Engineering, 130(1): 011205-1-9.](https://doi.org/10.1115/1.2829593)
-	[Liang Q (2010) Flood Simulation Using a Well-Balanced Shallow Flow Model. ASCE - Journal of Hydraulic Engineering, 136(9): 669-675.](https://doi.org/10.1061/(ASCE)HY.1943-7900.0000219)

[4] Rewriting NewChan using OpenCL; high-performance computing on multi-GPUs and multi-nodes
-	[Smith LS, Liang Q (2013) Towards a generalised GPU/CPU shallow-flow modelling tool. Computers & Fluids, 88: 334-343.](https://doi.org/10.1016/j.compfluid.2013.09.018)
-	[Liang Q, Smith LS (2015) A high-performance integrated hydrodynamic modelling system for urban flood simulations. Journal of Hydroinformatics, 17(4): 518-533.](https://doi.org/10.2166/hydro.2015.029) (The name of HiPIMS first publicly adopted).

[5] CUDA implementation for tsunami and flood modelling on a single GPU
-	[Amouzgar R, Liang Q, Clarke PJ, Yasuda T, Mase H (2016) Computationally Efficient Tsunami Modelling on Graphics Processing Units (GPU). International Journal of Offshore and Polar Engineering, 26(2): 154-160.](https://doi.org/10.17736/ijope.2016.ak10)

[6] GPU-Accelerated Shallow water flow & Transport model: Extended to include sediment and pollutant transport
-	Liang Q, Hou J, Smith LS (2015) An efficient hydrodynamic modelling system for predicting flood induced geomorphological processes. The 36th IAHR World Congress, 28 June – 3 July 2015, The Hague, The Netherlands.

[7] CUDA implementation for multi-GPUs computing. New numerical methods for more stable and accurate overland flow modelling
-	[Xia X, Liang Q, Ming X (2019) A full-scale fluvial flood modelling framework based on a high-performance integrated hydrodynamic modelling system (HiPIMS). Advances in Water Resources, 132: 103392.](https://doi.org/10.1016/j.advwatres.2019.103392)
-	[Xia X, Liang Q (2018) A new efficient implicit scheme for discretising the stiff friction terms in the shallow water equations. Advances in Water Resources, 117: 87-97.](https://doi.org/10.1016/j.advwatres.2018.05.004)
-	[Xia X, Liang Q, Ming X, Hou J (2017) An efficient and stable hydrodynamic model with novel source term discretization schemes for overland flow and flood simulations. Water Resources Research, 53: 3730-3759.](https://doi.org/10.1002/2016WR020055)

[8] Hybrid Python and CUDA framework for multi-GPUs & multi-node simulations
-	[Zhao J, Liang Q (2022) Novel variable reconstruction and friction term discretisation schemes for hydrodynamic modelling of overland flow and surface water flooding. Advances in Water Resources, 163: 104187.](https://doi.org/10.1016/j.advwatres.2022.104187)
-	[Tong X, Liang Q, Zhao J (2023) A high-performance integrated hydrodynamic modelling framework for large-scale multi-process simulation. EGU 2023, abstract only.](https://doi.org/10.5194/egusphere-egu23-15113)

[9] New mathematical and coupled modelling framework for flow-like landslide simulations
-	[Xia X, Liang Q (2018) A new depth-averaged model for flow-like landslides over complex terrains with curvatures and steep slopes. Engineering Geology, 234: 174-191.](https://doi.org/10.1016/j.enggeo.2018.01.011)
-	[Su X, Liang Q, Xia X (2022) A new GPU-accelerated coupled discrete element and depth-averaged model for simulation of flow-like landslides. Environmental Modelling & Software, 153: 105412.](https://doi.org/10.1016/j.envsoft.2022.105412)

[10] Coupled model for drainage modelling with CUDA implementation across multi-GPUs
-	[Li Q, Liang Q, Xia X (2020) A novel 1D-2D coupled model for hydrodynamic simulation of flows in drainage networks. Advances in Water Resources, 137: 103519.](https://doi.org/10.1016/j.advwatres.2020.103519)

[11] Modelling interactive flood waves into underground space
-	Li Q (2022) Development of new high-performance simulation approaches for multi-level urban flood modelling. PhD thesis, Loughborough University.

[12] New coupled hydrodynamic-DEM model for floating debris
-	[Xiong Y, Liang Q, Zheng J, Stolle J, Nistor I, Wang G (2022) A fully coupled hydrodynamic-DEM model for simulating debris dynamics and impact forces. Ocean Engineering, 225: 111468.](https://doi.org/10.1016/j.oceaneng.2022.111468)

[13] Modelling flow through hydraulic structures
-	[Cui Y, Liang Q, Wang G, Zhao J, Hu J, Wang Y, Xia X (2019) Simulation of Hydraulic Structures in 2D High-Resolution Urban Flood Modeling. Water, 11: 2139 (12 pages)](https://doi.org/10.3390/w11102139).

[14] Particle-based approach for full-process non-point source (NPS) pollutant modelling
-	[Jiang J, Liang Q, Xia X, Hou J (2021) A coupled hydrodynamic and particle-tracking model for full-process simulation of nonpoint source pollutants. Environmental Modelling & Software, 136: 104951.](https://doi.org/10.1016/j.envsoft.2020.104951)
-	Tong X, Liang Q, Wang G, Lai X (2023) A physically based model for non-point source pollutant wash-off process over impervious road surfaces. (To be published soon)

[15] Novel CHANS modelling framework for interactive human and flooding processes
-	Qin H, Liang Q, Chen H, De-Silva V (2023) Development of a Coupled Human And Natural Systems (CHANS) Modelling Approach for flood risk assessment and reduction. (To be published soon)

[16] Modelling individual measures for Nature-Based Solutions (NBS)
-	Publication to be released soon.
