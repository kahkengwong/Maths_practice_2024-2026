<div align="center">

# Maths practice 2024-2026:<br>algebra, calculus and statistics

[![Applied in](https://img.shields.io/badge/Applied%20in-CEP--IP__maths__notes-4E81BE?logo=github&logoColor=white&style=flat-square)](https://github.com/kahkengwong/CEP-IP_maths_notes)
[![R package](https://img.shields.io/badge/R%20package-cepip-276DC3?logo=r&logoColor=white&style=flat-square)](https://github.com/kahkengwong/cepip)
[![Pages](https://img.shields.io/badge/handwritten%20pages-80-555555?style=flat-square)](#contents)
[![Last commit](https://img.shields.io/github/last-commit/kahkengwong/Maths_practice_2024-2026?style=flat-square)](https://github.com/kahkengwong/Maths_practice_2024-2026/commits/main)

### Author: Kah Keng Wong [![ORCID](https://img.shields.io/badge/ORCID-0000--0001--7359--6202-A6CE39?logo=orcid&logoColor=white&style=flat-square)](https://orcid.org/0000-0001-7359-6202)

</div>

---

- These are photos of my handwritten maths practice from 2024 to 2026, covering algebra, calculus and statistics.
- I am an immunologist by training. I went back to maths in 2024 and worked through textbook sections and exercise sets by hand.
- I later applied this practice to the mathematics behind the CEP-IP framework, in [CEP-IP_maths_notes](https://github.com/kahkengwong/CEP-IP_maths_notes) and the R package [cepip](https://github.com/kahkengwong/cepip).
- Notes are added only for the tricky questions and for my own corrections. Pages with a note are shown on their own.
- Click a page to see it at full size.

---

## Contents

| Folder | Pages | Topics |
|---|---|---|
| [`algebra/`](algebra) | A01 to A06 | Number systems, quadratic functions, radicals, trigonometric identities and matrices |
| [`calculus/`](calculus) | C01 to C70 | Limits and continuity, differentiation and its applications, curve sketching and integration |
| [`statistics/`](statistics) | S01 to S04 | Standard deviation, sums of squares, and Pearson and Spearman correlation |

- The pages are numbered in learning order within each folder, following the textbook sections and question numbers.
- [`page_order.csv`](page_order.csv) lists the original photo for each page.
- Each photo was brightened by 5%, and the two sideways matrix pages (A05 and A06) were rotated to portrait. No other changes were made.

---

## Algebra
### 1. Number systems, radicals and trigonometric identities

The number system hierarchy and the three forms of a quadratic function (A01). Radicals, rational and irrational numbers, and why the repeating decimal 0.777... equals 7/9, shown both by algebra and as the limit of the partial sums 0.7, 0.77, 0.777, and so on (A02).

<img src="algebra/A01_number_systems_and_quadratic_functions.jpg" width="49%"> <img src="algebra/A02_radicals_rational_numbers_and_repeating_decimals.jpg" width="49%">

The trigonometric identities used later for the derivatives of trigonometric functions: reciprocal, Pythagorean, sum and difference, product-to-sum, double angle and half angle (A03).

<p align="center"><img src="algebra/A03_trigonometric_identities.jpg" width="49%"></p>

### 2. Matrices

Matrix order, equal matrices, and addition, subtraction and multiplication (A04, A05).

<img src="algebra/A04_matrices_try_this_2.1_and_2.2.jpg" width="49%"> <img src="algebra/A05_matrices_q3_to_q12.jpg" width="49%">

The inverse of a 2 x 2 matrix (A06). The lower part of the page solves AA<sup>-1</sup> = I for the four unknown entries, which shows where the formula A<sup>-1</sup> = (1 / (ad &minus; bc)) [d &minus;b; &minus;c a] comes from and why it fails when ad &minus; bc = 0.

<p align="center"><img src="algebra/A06_matrices_q13_to_q17_and_2x2_inverse.jpg" width="49%"></p>

---

## Calculus

### 1. Limits and first principles

What a limit is, and the types of limits: one-sided, infinite, at infinity, trigonometric, exponential and oscillating (C01 to C04).

<img src="calculus/C01_limit_and_its_relation_to_differentiation.jpg" width="49%"> <img src="calculus/C02_concept_of_limits.jpg" width="49%">
<img src="calculus/C03_infinite_limits_and_limits_at_infinity.jpg" width="49%"> <img src="calculus/C04_trigonometric_exponential_and_oscillating_limits.jpg" width="49%">

Limits that need algebra, then the first derivative from first principles, where the gradient of a secant line becomes the gradient of the tangent as &delta;x &rarr; 0 (C05 to C08).

<img src="calculus/C05_limits_requiring_algebra_try_this_2.1.jpg" width="49%"> <img src="calculus/C06_first_derivative_by_first_principles.jpg" width="49%">
<img src="calculus/C07_secant_to_tangent_try_this_2.1_q4.jpg" width="49%"> <img src="calculus/C08_first_principles_try_this_2.1_q5.jpg" width="49%">

### 2. First derivative

The power rule, the chain rule, and the product and quotient rules (C09 to C12). C10 starts with two more types of limit, the squeeze theorem and different one-sided limits, before the chain rule.

<img src="calculus/C09_power_rule_try_this_2.2_q1_to_q4.jpg" width="49%"> <img src="calculus/C10_squeeze_theorem_one_sided_limits_and_chain_rule.jpg" width="49%">
<img src="calculus/C11_chain_rule_product_and_quotient_rules.jpg" width="49%"> <img src="calculus/C12_product_rule_try_this_2.2_q11.jpg" width="49%">

### 3. Second and higher derivatives

The second derivative measures how the gradient changes. d<sup>2</sup>y/dx<sup>2</sup> &gt; 0 means the gradient is increasing (concave up), &lt; 0 means it is decreasing (concave down), and = 0 marks a possible inflection point. The page also covers the third derivative, with position, velocity, acceleration and jerk as the example (C13).

<p align="center"><img src="calculus/C13_second_derivative_and_higher_derivatives.jpg" width="49%"></p>

Notation, the trigonometric ratios, perpendicular gradients, and C<sup>k</sup> and C<sup>&infin;</sup> functions (C14, C15).

<img src="calculus/C14_notation_trig_ratios_and_Ck_smoothness.jpg" width="49%"> <img src="calculus/C15_Cinf_functions_and_log_derivatives.jpg" width="49%">

### 4. Applications of differentiation

Tangents and normals (C16 to C18), and the steps for finding and classifying turning points (C19).

<img src="calculus/C16_tangent_and_normal_notes.jpg" width="49%"> <img src="calculus/C17_tangent_and_normal_try_this_2.4_q1_to_q3.jpg" width="49%">
<img src="calculus/C18_tangent_and_normal_q4_q5.jpg" width="49%"> <img src="calculus/C19_turning_points_and_optimisation_steps.jpg" width="49%">

Optimisation (C20, C21) and related rates of change through the chain rule (C22, C23).

<img src="calculus/C20_nature_of_turning_points_q9_to_q11.jpg" width="49%"> <img src="calculus/C21_optimisation_box_volume_q11.jpg" width="49%">
<img src="calculus/C22_related_rates_chain_rule.jpg" width="49%"> <img src="calculus/C23_related_rates_q13_q14.jpg" width="49%">

More related rates (C24), and small changes and approximations with &delta;y &asymp; (dy/dx) &times; &delta;x (C25).

<img src="calculus/C24_related_rates_q15_q16.jpg" width="49%"> <img src="calculus/C25_small_changes_and_approximations.jpg" width="49%">

> Note on C26. Approximation questions depend on assigning x<sub>old</sub> and x<sub>new</sub> correctly, and the note at the top of the page sets out the rule. In an estimation question, x<sub>old</sub> is the convenient value where dy/dx is easy to work out (for example 81 when estimating 1/&radic;80.98), and x<sub>new</sub> is the target value. In a change or measurement question, x<sub>old</sub> is the initial state and x<sub>new</sub> is the final state. In both, dy/dx is evaluated at x<sub>old</sub> and &delta;x = x<sub>new</sub> &minus; x<sub>old</sub>.

<p align="center"><img src="calculus/C26_small_changes_q17_q18.jpg" width="49%"></p>

### 5. Differentiation practice sets

Two sets of mixed questions on sections 1 to 4. The first set is C27 to C30.

<img src="calculus/C27_spm_practice_q1_to_q6.jpg" width="49%"> <img src="calculus/C28_spm_practice_q7_to_q12.jpg" width="49%">

> Note on C29, tangents from an external point. My first attempt is crossed out. The correct solution writes the tangent at a general point (a, 4 + 3a &minus; a<sup>2</sup>) and substitutes the external point (5/2, 11/2), which gives a = 2 or a = 3.
>
> Note on C29, question 13. The critical point at t = 2/9 s is a local minimum, because d<sup>2</sup>s/dt<sup>2</sup> &gt; 0 there. A cubic with a positive leading coefficient has no maximum displacement, so the question should ask for the displacement at the critical point instead.

<p align="center"><img src="calculus/C29_spm_practice_q12_q13_corrected.jpg" width="49%"></p>

The end of the first set (C30) and the start of the second set (C31).

<img src="calculus/C30_spm_practice_q14_to_q17.jpg" width="49%"> <img src="calculus/C31_paper2_q1_q2.jpg" width="49%">

> Note on C33, question 7. My first answer worked out the exact change in H. The question asks for an estimate, so the correct solution uses &delta;H &asymp; (dH/dg) &times; &delta;g.

<img src="calculus/C32_paper2_q3_to_q6.jpg" width="49%"> <img src="calculus/C33_paper2_q6_q7_error_estimate.jpg" width="49%">

<img src="calculus/C34_paper2_q9_q10.jpg" width="49%"> <img src="calculus/C35_paper2_q10_to_q13.jpg" width="49%">

> Note on C36. Here 1/u + 1/v = 1/6, and du/dv can be found in two ways. The product rule method first makes u the subject. The chain rule method differentiates both sides with respect to v. The term 1/v changes directly, the term 1/u changes indirectly because u depends on v, and the constant 1/6 does not change. The notes in the margin explain why each term is treated as it is.

<p align="center"><img src="calculus/C36_paper2_tangent_and_chain_rule.jpg" width="49%"></p>

Differentiating a dependent variable (C37), and the end of the second set (C38).

<img src="calculus/C37_implicit_differentiation_note.jpg" width="49%"> <img src="calculus/C38_paper2_q15_to_q20.jpg" width="49%">

### 6. Limits and continuity

A limit does not exist when the left and right limits differ. The page also lists the properties of limits and how to avoid the indeterminate forms 0/0 and &infin;/&infin; by factorising (C39).

<p align="center"><img src="calculus/C39_limits_and_continuity_notes.jpg" width="49%"></p>

Exercises on limits and limits at infinity (C40 to C43). In C41, question 12, the limit should be x &rarr; &minus;7, which I marked as a typing error in the question.

<img src="calculus/C40_exercise_7.1_q1_to_q8.jpg" width="49%"> <img src="calculus/C41_exercise_7.1_q9_to_q15.jpg" width="49%">
<img src="calculus/C42_exercise_7.1_q16_and_limits_at_infinity.jpg" width="49%"> <img src="calculus/C43_exercise_7.2_limits_at_infinity.jpg" width="49%">

The three conditions for continuity at x = a, checked in turn: f(a) exists, the limit exists, and the limit equals f(a) (C44, C45).

<img src="calculus/C44_exercise_7.2_q5_q6_and_continuity_definition.jpg" width="49%"> <img src="calculus/C45_continuity_steps_2_and_3.jpg" width="49%">

### 7. Curve sketching

A step-by-step method for sketching graphs: the domain, key points and intercepts, behaviour at the edges, the shapes of basic functions, and horizontal, vertical and oblique asymptotes (C46 to C49).

<img src="calculus/C46_continuity_example_and_sketching_steps_1_2.jpg" width="49%"> <img src="calculus/C47_sketching_steps_3_4_and_basic_graphs.jpg" width="49%">
<img src="calculus/C48_asymptotes_and_rational_function_graphs.jpg" width="49%"> <img src="calculus/C49_asymptote_rules_and_oblique_asymptotes.jpg" width="49%">

> Note on C50. The line "for x < 0, f&Prime;(x) > 0" holds on &minus;2 < x < 0 only. For x < &minus;2, f&Prime;(x) < 0. The sign chart on C51 has the correct intervals.

<p align="center"><img src="calculus/C50_rational_function_sketch_three_branches.jpg" width="49%"></p>

> Note on C51. Point 6 reads "if f&Prime;(x) = 0 has solutions, concavity changes". A change of sign is also required. Counterexample: y = x<sup>4</sup> has f&Prime;(0) = 0 but stays concave up.

<p align="center"><img src="calculus/C51_curve_sketching_sign_chart.jpg" width="49%"></p>

### 8. Differentiation of standard functions

The derivative definition, when a derivative exists, the product rule derived from first principles, and derivatives of exponential, logarithmic and trigonometric functions (C52 to C55).

<img src="calculus/C52_derivative_definition_and_standard_functions.jpg" width="49%"> <img src="calculus/C53_product_quotient_and_chain_rules_derived.jpg" width="49%">
<img src="calculus/C54_exercise_8.1_q1_to_q6.jpg" width="49%"> <img src="calculus/C55_exercise_8.1_q7_to_q10_trig.jpg" width="49%">

### 9. Integration

Integration as the inverse of differentiation, and indefinite integrals (C56 to C59).

<img src="calculus/C56_integration_as_inverse_of_differentiation_try_this_3.1.jpg" width="49%"> <img src="calculus/C57_indefinite_integral_try_this_3.2.jpg" width="49%">
<img src="calculus/C58_indefinite_integral_examples.jpg" width="49%"> <img src="calculus/C59_indefinite_integral_try_this_3.2_q5_to_q9.jpg" width="49%">

Finding y from its gradient function, definite integrals and their properties, and the area under a curve (C60 to C63).

<img src="calculus/C60_finding_y_from_gradient_q10_q11.jpg" width="49%"> <img src="calculus/C61_definite_integral_try_this_3.3.jpg" width="49%">
<img src="calculus/C62_definite_integral_properties_and_area_under_curve.jpg" width="49%"> <img src="calculus/C63_area_under_curve_q11_q12.jpg" width="49%">

Areas bounded by the y-axis, and areas above and below an axis, which are integrated separately (C64, C65).

<img src="calculus/C64_area_bounded_by_y_axis_q12_q13.jpg" width="49%"> <img src="calculus/C65_area_above_and_below_axis_q13_q14.jpg" width="49%">

The area between two curves, and the volume of revolution built from thin cylinders of volume &pi;y<sup>2</sup>&delta;x. The page sums five cylinders numerically, then lets &delta;x &rarr; 0 to obtain V = &int; &pi;y<sup>2</sup> dx (C66).

<p align="center"><img src="calculus/C66_area_between_curves_and_riemann_volume.jpg" width="49%"></p>

Volumes of revolution about the x-axis, V = &int; &pi;y<sup>2</sup> dx, and about the y-axis, V = &int; &pi;x<sup>2</sup> dy (C67).

<p align="center"><img src="calculus/C67_volume_of_revolution_q17_to_q19.jpg" width="49%"></p>

> Note on C68. The volume about the y-axis, &int; &pi;x<sup>2</sup> dy, can only be used where the curve bounds the y-values. For y = x<sup>2</sup> + 2, the y-values from 0 to 2 are not bounded by the curve, so the volume has to be found by subtracting from a cylinder.

<p align="center"><img src="calculus/C68_volume_of_revolution_q19_q20.jpg" width="49%"></p>

Applications of integration: rates, velocity and displacement, area, volume, and a boundary condition to find the constant of integration (C69, C70).

<img src="calculus/C69_applications_of_integration_try_this_3.4.jpg" width="49%"> <img src="calculus/C70_integration_with_boundary_conditions.jpg" width="49%">

---

## Statistics

Standard deviation, the empirical rule, sums of squares and the penalized residual sum of squares (PRSS) (S01). Pearson correlation, and why its denominator is the geometric mean of the two sums of squares (S02).

<img src="statistics/S01_standard_deviation_sums_of_squares_and_PRSS.jpg" width="49%"> <img src="statistics/S02_pearson_correlation_and_geometric_mean.jpg" width="49%">

Spearman correlation, with ties and the mean of the ranks (S03), and Spearman's rho written as a sum of rank products, which is Pearson's r computed on the ranks (S04).

<img src="statistics/S03_spearman_rank_correlation_and_ties.jpg" width="49%"> <img src="statistics/S04_spearman_rho_from_rank_products.jpg" width="49%">

---

## License
The pages in this repository are photos of my own notebooks. They are shared for reading. Please ask before reusing them.

---

## Contact
Kah Keng Wong: [kahkeng@usm.my](mailto:kahkeng@usm.my)
