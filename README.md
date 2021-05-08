# lssvmigwo
Our Load Forecasting using LSSVM tuned by IGWO. Paper coming soon

Most of this files includes LSSVM toolbox (which is modified only on removing Local Search on tunelssvm.m RBF kernel tuning mechanism) and additional metaheuristic algorithms. Each metaheuristic algorithm comes in 2 files, its abbreviation.m and tunelssvm(abbreviation).m

RegressExample.m perform load forecasting by LSSVM tuned by metaheuristic algorithm.

PengambilData.m performing RegressExample.m multiple times for each algorithms and case studies, and is the only file you have to run via MATLAB editor

Hasil Simulasi files provides our 'raw' simulation result on each case studies, where the rng generator are set following structRNG2.mat

Untitled.m perform non-parametric statistical analyses.

Rangkuman Simulasi files are outputs of Untitled.m on MAE, MAPE, MASE, and R2.

Indonesia(1) and (2) pdfs are calendars. 
