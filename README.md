

### This code is associated with the paper from Maboudi et al., "Uncovering temporal structure in hippocampal output patterns". eLife, 2018. http://dx.doi.org/10.7554/eLife.34467

# Example-analyses
Example analyses making extensive use of nelpy.

## Examples include:
  * [**LinearTrackDemo**.ipynb](../master/LinearTrackDemo.ipynb)—using position and spike data (CA1) to estimate spatial tuning curves and identify putative place cells from a 15 minute linear track run session.
  *  [**WMazeDemo**.ipynb](../master/WMazeDemo.ipynb)—using position and spike data (CA1) to estimate 2D spatial tuning curves from two 15 minute w-maze sessions.
  * [**BayesianDecoding**.ipynb](../master/BayesianDecoding.ipynb)—simple 1D and 2D Bayesian decoding of position from hippocampal place cells.
  * [**FilteringAndSpectralAnalyses**.ipynb](../master/FilteringAndSpectralAnalyses.ipynb)—basic spectral analyses and filtering to remove 60 Hz noise, or to identify sharp wave ripples.
  * [**HiddenMarkovModels**.ipynb](../master/HiddenMarkovModels.ipynb)—basic hidden Markov model analyses of neural data, including model training, evaluation, and decoding.
  * [**KalmanSmoothing**.ipynb](../master/KalmanSmoothing.ipynb)—smoothing trajectory data using a Kalman smoother for better position and speed estimates.
  * [**WrappedEnvironments**.ipynb](../master/WrappedEnvironments.ipynb)—working with ring-like environments, such as running wheels, treadmills, or circular tracks.
  * [**BasicReplayAnalyses**.ipynb](../master/BasicReplayAnalyses.ipynb)—detecting simple hippocampal replay using Bayesian decoding. **Need nice public data!!!**.
  * [Advanced] [**InertialMeasurementUnits**.ipynb](../master/InertialMeasurementUnits.ipynb)—working with inertial measurement units (IMUs) to obtain position, speed, and other behavioral variables.
  * [Advanced] [**ProbabilityDistributions**.ipynb](../master/ProbabilityDistributions.ipynb)—repurposing `AnalogSignalArrays` into probability distribution functions.
  * more coming soon!
