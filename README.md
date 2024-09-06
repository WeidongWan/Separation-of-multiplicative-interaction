# Separation-of-multiplicative-interaction
open-source code of the manuscript submitted to IEEE

MATLAB Files :

Script Files :

BER_of_different_beamforming_strategies.m - Compare the performance of CGM, UNFEQ and random beamforming for SMI scheme.

BER_traditional_RIS_aided.m - Simulate the BER-\rho scaling law of traditional RIS aided systems without symbiosis paradigm.

complexity.m - Compare the complexity of ML detector, SMC detector and 3 linear detectors.

ML_theoBER_primarysig.m - Theoretical BER-\rho scaling law for SMI with UNFEQ and ML detection when only 1 antenna is deployed at the receiver. (Primary signals only)

MLdetector_theoreticalupperbound.m - Theoretical BER upper bound for SMI with UNFEQ and ML detection. (Including primary and secondary signals)

RIS_Segmented_BER_N1.m - Simulate the BER-N1 scaling law of RIS-segmented PSK scheme.

RIS_Segmented_BER_rho.m - Simulate the BER-\rho scaling law of RIS-segmented PSK scheme.

simu_trans_Linear.m - Simulate the BER-\rho scaling law of SMI with UNFEQ and linear detectors.

simu_trans_ML.m - Simulate the BER-\rho scaling law of SMI with UNFEQ and ML detector.

simu_trans_SMC.m - Simulate the BER-\rho scaling law of SMI with UNFEQ and SMC detector.

SMI_ML_CGM.m - Find the numerical values of BER for SMI with CGM and ML detector.

SMI_ML_CGM_par.m - Find the numerical values of BER for SMI with CGM and ML detector. (Parallel computing)

dnc_ML.m - Simulate the signal transmission and ML detection of the SMI-based SR systems in the scenario where both direct and cascaded links exist.

dnc_SMC.m - Simulate the signal transmission and SMC detection of the SMI-based SR systems in the scenario where both direct and cascaded links exist.

dnc_iteML.m - Simulate the signal transmission and traditional iterative ML detection of the SMI-based SR systems in the scenario where both direct and cascaded links exist.

dnc_iteLinear.m - Simulate the signal transmission and traditional iterative linear detection of the SMI-based SR systems in the scenario where both direct and cascaded links exist.

dnc_SMIbasedLinear.m - Simulate the signal transmission and SMI-based linear detection of SMISR in the scenario where both direct and cascaded links exist.



Function Files :

CGM.m - CGM beamforming strategy.

generate_the_sets_of_Xp_and_Xs.m - Generate the sets of primary signals and secondary signals with their bit sequences one-to-one correspondingly. (Including SMI and traditional PSK schemes)

randomly_generate_Xp_and_Xs.m - Randomly generate the primary signal and secondary signal with their bit sequences to simulate signal transmission. (Including SMI and traditional PSK schemes)



The parameters requiring frequent modification have been positioned at the start of the codes. Please adjust them as needed.
