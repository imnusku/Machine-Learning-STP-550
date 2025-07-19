# Machine-Learning-STP-550
Machine Learning Project.

 In this project, we use machine learning to predict wall shear stress (as a measure of drag) from off-wall
 velocity measurements (taken from simulation), drawing inspiration from the opposition control strategy.
 This lays the groundwork for future drag and wall pressure prediction, which is particularly valuable in high
fidelity CFD solvers like Nek5000 that are highly sensitive to wall pressure boundary conditions. Moreover,
 since pressure sensors are often expensive and difficult to deploy in experiments, a robust ML model could
 benefit both simulation and experimental workflows by serving as a virtual pressure sensor.
 
 At this stage, the focus is on evaluating the prediction capability of various learning methods. We assess
 model performance using RMSE values and scatter plots comparing predicted vs. true shear stress values
 (y-pred vs. y-test). While active control or real-time deployment is not implemented in this phase, the
 predictive models will serve as a foundation for future work in pressure estimation and passive control
 integration.

 [📄 Full Project Report (PDF)](./MachineLearning.pdf)
