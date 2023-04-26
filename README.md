# L-TAGE branch predictor
L-TAGE is a high-performance branch predictor that uses multiple tables to predict the outcome of conditional branches in computer programs. It combines the advantages of an previous predictors TAGE with that of a LOOP predictor, to achieve better accuracy in branch prediction. L-TAGE has been shown to outperform other state-of-the-art branch predictors in many benchmarks.

We have implemented the L-TAGE predictor and improved it for better prediction in tasks involving graph analytics. Our implementation is designed for the champsim simulator. The file `ltage.bpred` contains the code for the implementation. We also compared its accuracy against the `hashed perceptron` predictor. The results of running these two predictors on different traces are present in the `results` folder.

# References
1. [The L-TAGE paper](https://www.irisa.fr/caps/people/seznec/L-TAGE.pdf).
2. The author's submission in CBP2. The code can be found [here](https://team.inria.fr/pacap/members/andre-seznec/branch-prediction-research/).
3. A champsim implementation that can be found [here](https://github.com/KanPard005/RISCY_V_TAGE/blob/master/branch/ltage.bpred).
