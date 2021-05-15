# VAE with continuous latent ODE dynamics

### Papers based on
[1] [T. Q. Chen, Y. Rubanova, J. Bettencourt, and D. K. Duvenaud. Neural ordinary differential equations. In _Advances in neural information processing systems_, pages 6571–6583, 2018.](https://papers.nips.cc/paper/2018/hash/69386f6bb1dfed68692a24c8686939b9-Abstract.html)

[2] [Y. Rubanova, T. Q. Chen, and D. K. Duvenaud. Latent ordinary differential equations for irregularly-sampled time series. In _Advances in neural information processing systems_, pages 5321–5331, 2019.](https://papers.nips.cc/paper/2019/hash/42a6845a557bef704ad8ac9cb4461d43-Abstract.html)

[3] [Ç. Yıldız, M. Heinonen, and H. Lähdesmäki. Ode2vae: Deep generative second order odes with bayesian neural networks. In _Advances in neural information processing systems_, pages 13412–13421, 2019.](https://papers.nips.cc/paper/2019/hash/99a401435dcb65c4008d3ad22c8cdad0-Abstract.html)

### Proposal
[Link to proposal](https://drive.google.com/file/d/1wYOQbOV9dqvrUUKVh5L44Rt7pOWwCv8u/view?usp=sharing)

All four proposals were on static data such as single images, which did not match the general theme of the project on modelling raw data with time-dependence structure. The final research direction was modified from Proposal 2 and my new focus will be on comparing time dynamic modelling between neural first order and second order ordinary differential equations.

### Project goals

* Neural ODEs -> implement generative latent model on toy dataset
* ODE2VAE -> implement generative model on toy dataset
* Compare predictive performance of latent ODE model and ODE2VAE on an irregularly-sampled time series dataset (PhysioNet 2012)
