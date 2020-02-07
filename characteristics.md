Equipment used to evaluate characteristics.

- A tensile testing machine [(Instron Model 3369)](https://www.instron.us/products/testing-systems/universal-testing-systems/electromechanical/3300/3360-dual-column) was employed for cyclic tests.
- The electrical resistance was measured using a digital multimeter [(34465A, Keysight Technologies)](https://www.keysight.com/en/pdx-2891457-pn-34465A/digital-multimeter-6-digit-truevolt-dmm?cc=AU&lc=eng).


Maximum sensing range and cyclic reliability: a strain of 58%

Cyclic tests:
- Cyclic tests are conducted by applying a sinusoidal cyclic load to stretch the sensor at a frequency of 0.08 Hz. 
- cycle_test.png shows the the resistance changes of 1,000 times of cyclic loading and unloading of a maximum strain of 20%.

Sensitivity: 
- Gauge Factor of 103.8
- response_figure.png shows the relationship between resistance changes and loaded strain. The linear fitting coefficients R<sup>2</sup> of 0.974 implies the response of the sensor is almost perfect linear.





This is not the first time piezo-resistive strain sensor is used on the smart garment. 
A tight-fitting smart garment system that used piezo-resistive sensors in the earlier work reported to have a sensitivity of 2 $k\varOmega /mm$~\cite{mattmann2007recognizing}.
With these sensors, they achieved 97\% accuracy in recognizing upper body postures with skin-attached tight-fitting smart garment. Considering their works as the baseline, the proposed novel piezo-resistive sensor is 150 times more sensitive in detecting strain. For our prototype, the initial length of the sensor is approximately 38 mm and the initial resistance is approximately 137 $k\varOmega$. Substituting $L_0$ with 38 mm, $R_0$ with 137 $k\varOmega$ and GF with 103.8 in Eq.(~\ref{for:gauge}) and (~\ref{for:strain}), the sensitivity between the stretched length and corresponding resistance changes can be computed to be 306 $k\varOmega /mm$, which is approximately 150 times more sensitive that the baseline sensor
in~\cite{mattmann2007recognizing}. 

The degree of hysteresis (~ 3\%) shown in Figure~\ref{subfig:hysteresis} can be evaluated by using the ratio of the width of the hysteresis loop to the range during the loading-unloading cycle. The optical transmittance by ultraviolet–visible spectrophotometry is higher than 40\% in the wavelength range of 350 to 850 nm as shown in Figure~\ref{subfig:transparency}. The sensor itself can work in different aqueous conditions. However, the electrical part including copper wires attached to silver pastes, and embedded system for signal processing cannot be laundered.
