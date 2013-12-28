---
layout: page
title: About
comments: false 
sharing: true
footer: true
author: Ranjit Jhala
---

LiquidHaskell is a static verifier for Haskell, based on **Liquid Types**

Code
----

You can get LiquidHaskell [here](http://github.com/ucsd-progsys/liquidhaskell)
See the [README](https://github.com/ucsd-progsys/liquidhaskell/blob/master/README.md)
for installation instructions. LiquidHaskell is an active research project that is
still rough around the edges. In particular

- A modest subset of the language is currently supported (monads recently
  included!...)

- Error reporting is *rather* primitive

Constructive Feedback, or better yet, patches, additions and pull requests 
are *extremely* welcome.

Mailing List
------------

If you have questions or comments, please send mail to the [users mailing list](https://groups.google.com/forum/#!forum/liquidhaskell)


Papers
------

To learn about the theory behind Liquid Types, I recommend reading first the 
PLDI 2008 paper and then the ESOP 2013 paper. Alternatively, one lazy weekend, 
you could curl up with [Pat Rondon's Ph.D Dissertation](http://goto.ucsd.edu/~pmr/papers/rondon-liquid-types.pdf)

#### ML

- [Liquid Types, PLDI 2008](http://goto.ucsd.edu/~rjhala/liquid/liquid_types.pdf)
- [Type-based Data Structure Verification, PLDI 2009](http://goto.ucsd.edu/~rjhala/papers/type-based_data_structure_verification.pdf)
- [Dsolve: Safety Verification via Liquid Types, CAV 2010](http://goto.ucsd.edu/~rjhala/papers/safety_verification_with_liquid_types.pdf)
- [HMC: Verifying Functional Programs with Abstract Interpreters, CAV 2011](http://goto.ucsd.edu/~rjhala/papers/hmc.pdf)

#### Haskell

- [Abstract Refinement Types, ESOP 2013](http://goto.ucsd.edu/~rjhala/liquid/abstract_refinement_types.pdf)

#### C

- [Low-level Liquid Types, POPL 2010](http://goto.ucsd.edu/~rjhala/liquid/low_level_liquid_types.pdf)
- [Deterministic Parallelism With Liquid Effects, PLDI 2012](http://goto.ucsd.edu/~rjhala/papers/deterministic_parallelism_via_liquid_effects.pdf)
- [Verifying C With Liquid Types, CAV 2012](http://goto.ucsd.edu/~rjhala/papers/csolve_verifying_c_with_liquid_types.pdf)


Talks
-----

The following talks are good tutorial introductions to the techniques.

- [Tutorial on LiquidHaskell](http://goto.ucsd.edu/~nvazou/liquidtutorial/index.html)
- [Tutorial at VMCAI](http://goto.ucsd.edu/~rjhala/talks/liquid_types_VMCAI.pptx)
- [Tutorial at CAV](http://goto.ucsd.edu/~rjhala/talks/liquid_types_CAV2011.pptx)

People
------

Liquid Types have been developed in the UCSD Programming Systems group by

- [Alexander Bakst](http://cseweb.ucsd.edu/~abakst)
- [Ranjit Jhala](http://cseweb.ucsd.edu/~rjhala)
- [Ming Kawaguchi](http://cseweb.ucsd.edu/~mwookawa)
- [Patrick Rondon](http://cseweb.ucsd.edu/~prondon)
- [Niki Vazou](http://cseweb.ucsd.edu/~nvazou)

Thanks
------

This work is funded by NSF grants CCF-0644361, CNS-0720802, CCF-0702603, and generous gifts from Microsoft Research.




