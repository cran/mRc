# mRc 0.1.1

* Optimized `closedCI()` using vectorized matrix operations for significantly faster performance.
* Added correction to remove excess decimal value from adjusted Schumacher-Eschmeyer estimator.
* Applied clamping logic to estimates and confidence bounds to prevent impossible values in low-sample scenarios.
* Refactored code to follow R best practices (spacing, assignment operators, and `stats` namespace imports).
