The goal is to predict how many calories were burned during a workout.

The evaluation metric for this competition is Root Mean Squared Logarithmic Error.

\textrm{RMSLE} =   \left( \frac{1}{n} \sum_{i=1}^n \left(\log (1 + \widehat{y}_i) - \log (1 + y_i)\right) \right)^{\frac{1}{2}}
      
