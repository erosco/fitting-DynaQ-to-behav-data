# fitting-DynaQ-to-behav-data

Description of scripts in this repository:
  - replaySimultaneousAnnealing: executes parameter-fitting according to given replay policy, using the output of runDynaQPrediction as       the error to be minimised.  Produces 10 fitted parameter sets
  - runDynaQPrediction: trains DynaQ on behavioural data, predicting actions for every trial
  - plotPredictiveAccuracy: produces a figure showing predictive accuracy over time for each parameter set outputted by                       replaySimultaneousAnnealing
  - plotVariousResults: produces a figure showing various results from runDynaQPrediction, including reward-prediction error and trials       replayed
