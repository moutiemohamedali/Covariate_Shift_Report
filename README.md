# Regression under Covariate Shift: From ERM to Importance Weighting

**Moutie Mohamed Ali, Bleich Duncan, Olszewska Urszula**  
*Statistical Machine Learning Project, EPFL*

## Abstract
When training and test inputs follow different distributions, empirical risk minimization (ERM) estimates the wrong risk and can yield poor test performance. Under covariate shift, the conditional distribution p(y|x) is unchanged but the marginal p(x) differs. We explain why this breaks ERM, how importance sampling yields a corrected objective, and how importance-weighted ERM (IWERM) implements this correction in practice. Since the required importance weights are unknown, we use density ratio estimation (DRE) via probabilistic classification. Finally, we show that model selection must also be shift-aware: standard cross-validation tunes hyperparameters for the training distribution, whereas importance-weighted cross-validation (IWCV) better targets the test risk. A controlled 1D experiment illustrates these effects.

## Report
[📄 Download PDF](./BLEICH_OLSZEWSKA_MOUTIE_Report.pdf)
