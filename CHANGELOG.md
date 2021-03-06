#### May 2020

- [dfd0aac](https://github.com/uma-pi1/kge/commit/dfd0aace1a77d6b7f04f414bdc8ea748a9d0d2f2): Added squared error loss (thanks Nzteb)

#### Apr 2020

- Improved shared negative sampling (WOR sampling, exclude positive triples from negative sample)
- PR [#86](https://github.com/uma-pi1/kge/pull/86): Support (s,?,o) queries for KvsAll training (thanks vonVogelstein)

#### Mar 2020

- [cf64dd2](https://github.com/uma-pi1/kge/commit/cf64dd2fcc4c5961bda2d9142ea1b08d41c16ba2): Fast dataset/index loading via cached pickle files
- [4bc86b1](https://github.com/uma-pi1/kge/commit/4bc86b18e5cfe0a4a596dd25fbdc8dde59dcafe9): Add support for chunking a batch when training with negative sampling
- [14dc926](https://github.com/uma-pi1/kge/commit/14dc9268b2e24f7db36dc95ae47e5e975016955b): Add ability to dump configs in various ways
- PR [#64](https://github.com/uma-pi1/kge/pull/64): Initial support for frequency-based negative sampling (thanks AdrianKS)
- PR [#77](https://github.com/uma-pi1/kge/pull/77): Simpler use of command-line interface (thanks cthoyt)
- [76a0077](https://github.com/uma-pi1/kge/commit/76a007731d98e00331f2f6ccb90b91cc8cf265dd): Added RotatE
- [7235e99](https://github.com/uma-pi1/kge/commit/7235e99784e056b6d0e162ce84f0c5e1eb410895): Added option to add a constant offset before computing BCE loss
- [67de6c5](https://github.com/uma-pi1/kge/commit/67de6c5c422c2adcefcc56f7738e04d0893c51ba): Added CP
- [a5ee441](https://github.com/uma-pi1/kge/commit/a5ee4417b92559b3624e3f737939793da810c211): Added SimplE

#### Feb 2020
- PR [#71](https://github.com/uma-pi1/kge/pull/71): Faster and more memory-efficient training with negative sampling (thanks AdrianKS)
- Initial release
