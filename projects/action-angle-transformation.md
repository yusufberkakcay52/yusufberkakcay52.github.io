<script>
window.MathJax = {
  tex: {
    inlineMath: [['\\(','\\)'], ['$', '$']],
    displayMath: [['\\[','\\]'], ['$$','$$']]
  }
};
</script>

<script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

This code constructs the action–angle variables \((J,\theta)\) for the one-dimensional
harmonic oscillator and verifies that the transformation
\[
(q,p) \mapsto (J,\theta)
\]
is canonical.

To check this, we compute the Poisson bracket \(\{\theta, J\}\).
As expected, the result is
\[
\{\theta, J\} = 1,
\]
confirming that \((J,\theta)\) form a canonical pair.

- [action_angle_transformation.nb](../projects/code/action_angle_transformation.nb)
