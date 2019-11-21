RELEASE_TYPE: patch

This release changes adds some additional heuristics to example generation that biases test cases generated earlier in the process to be smaller.

This fixes a bug introduced in :ref:`Hypothesis 4.42.0 <v4.42.0>` which would cause occasional
:obj:`~hypothesis.HealthCheck.too_slow` failures on some tests.
