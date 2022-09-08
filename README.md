# hands-on-kolkata ---
o2-env> alien_cp alien:///alice/sim/2021/LHC21i3f3/302000/003/AO2D.root file://. ---
o2-env> o2-analysistutorial-histograms --aod-file forAliceO2/AO2D.root | o2-analysis-track-propagation | o2-analysis-timestamp ---
o2-env> root AnalysisResults.root 
