---
title: PAWN
---

PAWN is a global sensitivity analysis (GSA) algorithm [^1]. Unlike variance based GSA approaches, it considers the entire distribution (specifically the CDF) of the model output. The following is an implementation of PAWN in MATLAB and a reproduction of the figures in the paper. 

The code and a working example are available here <https://github.com/sriki18/pawn>. Below is the figure generated by the example in the repo, which resembles Fig. 4 in [^1]:

![Check out the repository!](/assets/PAWN/fig4.png)

## References

[^1]: Pianosi, F., Wagener, T., 2015. A simple and efficient method for global sensitivity analysis based on cumulative distribution functions. Environ. Model. Softw. 67, 1–11. <https://doi.org/10.1016/j.envsoft.2015.01.004>