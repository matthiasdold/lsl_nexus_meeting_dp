# Post-Hoc Relabeling

### Basic idea

This is use case example of the _Post-Hoc relabeling_ method developed by Castaño-Candamil et al., 2019, in [Post-hoc Labeling of Arbitrary M/EEG Recordings for Data-Efficient Evaluation of Neural Decoding Methods](https://www.frontiersin.org/articles/10.3389/fninf.2019.00055/full). The basic idea as detailed in the paper, builds on the assumption cognitive and motor activity can be decoded from narrow band power of just a few bipolar sources. The method uses existing arbitrary EEG/MEG recordings and derives source space activity from them. This can be done following either:

1. An anatomically constrained mode, where a forward model, e.g. derived from an average head, is used to estimate the sources activity;
1. data driven approach, which uses any blind source separation method, such as e.g. ICA, to derive synthetic sources.
   With these source projections, the user can manipulate source data to synthetically create certain features like signal power or SNR.

## The notebook

Please find the example notebook showcasing how to use post-hoc relabeling to explore the effect of regularization on CSP at [https://github.com/bsdlab/BCIC2023_posthoc](https://github.com/bsdlab/BCIC2023_posthoc)

## The presentation technique: [Slidev](https://github.com/slidevjs/slidev)!

To start the slide show:

- `npm install`
- `npm run dev`
- visit http://localhost:3030

Edit the [slides.md](./slides.md) to see the changes.

Learn more about Slidev on [documentations](https://sli.dev/).
