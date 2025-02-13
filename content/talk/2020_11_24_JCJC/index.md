---
title: 'Applying GMRES to Helmholtz boundary integral equations: how does the number of iterations depend on the frequency in the presence of strong trapping?'
event: Rencontres JCJC Ondes
event_url: 'https://jcjc_ondes.pages.math.cnrs.fr'

location: 'Rencontres JCJC Ondes, Online'

abstract: >-
  We are interested in solving scattering problems with strong trapping using the Combined Field Integral Equation (CFIE) and the Generalized Minimal Residual method (GMRes). In this talk, we show a new understanding of how the number of GMRes iterations depends on frequency in this situation.

  The non-normal nature of CFIE makes GMRes the iterative method of choice for solving linear systems stemming from its discretisation. GMRes has the advantage of being able to solve any non-singular linear system, in particular non-normal. But the convergence analysis becomes less straightforward in this case, because it requires more information than just the spectrum. Bounds for GMRes applied to non-normal matrices can be derived using condition number of eigenvalues, numerical range or pseudo-spectrum[^1][^2]

  But in the case of trapping, an additional difficulty comes from the solution operator whose norm grows exponentially through a sequence of frequencies tending to infinity, with the density of these ``bad'' frequencies increasing as the frequency increases. In this case, the spectrum of the associated matrix has the form of a cluster with outliers near the origin. Following[^3] where matrices with similar spectra are studied, we provide a new analysis of the GMRes convergence taking into account this particular distribution. 

  [^1]: S. L. Campbell and I. C. F. Ipsen and C. T. Kelley and C. D. Meyer, GMRES and the minimal polynomial. *Oxford University Computing Laboratory*, 1999.

  [^2]: Mark Embree, How descriptive are GMRES convergence bounds? *BIT Numerical Mathematics*, 1996.

  [^3]: Jörg Liesen and Petr Tichý, Convergence analysis of Krylov subspace methods. *GAMM-Mitteilungen*, 2004.

summary: 'A new approach to study GMRes applied to Helmholtz boundary integral equation in presence of strong trapping.'

date: '2020-11-24T00:00:00'
date_end: ''
all_day: true
publishDate: '2019-02-05T00:00:00'


authors: [Jeffrey Galkowski, admin, Alastair Spence, Euan Spence]
tags:
  - GMRES
  - CFIE
  - Combined-Field operator
  - BEM
  - Boundary integral method
  - Boundary Integral Equation
  - Strong trapping


categories: 
  - conference

featured: true
projects: []
slides: ''

url_pdf: ''
url_slides: 'https://jcjc_ondes.pages.math.cnrs.fr/talk/2020_11_24/pm_1/P-Marchand.pdf'
url_video: ''
url_code: ''
image:
  caption: ''
  focal_point: ''
---