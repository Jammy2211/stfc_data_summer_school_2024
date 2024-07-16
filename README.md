HowToFit Lectures
=================

Welcome to the HowToFit Jupyter Notebook lectures!

At the core of data science is fitting a model to data. This process extracts meaningful patterns, relationships,
and insights, enabling accurate predictions, decision-making, and understanding of underlying processes.

However, data science can be quite challenging. With a vast array of statistical methods to choose from, it can be
difficult to determine the right one for your problem. Interpreting large volumes of results is complex, and
managing big datasets requires significant computational power and sophisticated statistical methods.

The HowToFit lectures teach you how to perform effective data science analysis. Designed at an undergraduate level,
these lectures assume no prior knowledge of model-fitting, Bayesian statistics, or scientific analysis. They
introduce core concepts without formal statistical equations, aiming to provide an understanding of the
phenomenological methods used in data science. By the end of the lectures, you'll be equipped to perform your own
data analysis.

The lectures use the probabilistic programming language PyAutoFit, an open-source library for model-fitting,
scientific analysis, and big data analysis (https://github.com/rhayes777/PyAutoFit).

For the STFC Summer School, we will cover a subset of the HowToFit lectures from chapters 1:

**Chapter 1: Introduction**: How to fit a model to data, perform statistical inference, and interpret the results
for scientific analysis.

More chapters are currently being written (but are not yet complete), however if you find the workshop useful
reach out to me for information on the full set of lectures.

__Chapter 1: Introduction__

The first chapter of the HowToFit lectures covers the basics of model-fitting, statistical inference, and scientific
interpretation. The chapter includes:

`tutorial_1_models.py`: What probabilistic models are and how to compose them using PyAutoFit.

`tutorial_2_fitting_data.py`: Fitting a model with an input set of parameters to data and quantifying the goodness of fit.

`tutorial_3_non_linear_search.py`: Searching non-linear parameter spaces to find the best-fit model.

`tutorial_4_why_modeling_is_hard.py`: Why modeling becomes difficult and how to over model-fitting problems.

`tutorial_5_results_and_samples.py`: Interpreting model-fit results and using the samples for scientific analysis.

`tutorial_8_astronomy_examples.py`: Applying the techniques to a real-world astronomy problem.

Getting Started
---------------

The lectures can be run via a web server by using the following URL:

https://mybinder.org/v2/gh/Jammy2211/autofit_workspace/HEAD