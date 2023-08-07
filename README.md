# Gaussian_mixture_model
***Paper-Reproduce: (Journal of the American Statistical Association) A Spatio-Temporal Point Process Model for Ambulance Demand***

---

### File Information
1. **"data"** is raw data, containing CanadianPostalCodes202204.csv, population.csv, salary.csv, Toronto.csv*.
2. **"A Spatio-Temporal Point Process Model for Ambulance Demand.pdf"** is the paper I reproduce.
3. **"medic_code.ipynb"** is all the code.

### Methods Description
Ambulance demand estimation at fine time and location scales is critical for fleet management and dynamic deployment. We are motivated by the problem of estimating the spatial distribution of ambulance demand in Toronto, Canada, as it changes over discrete 2 hr intervals. 
This large-scale dataset is sparse at the desired temporal resolutions and exhibits location-specific serial dependence, daily, and weekly seasonality. We address these challenges by introducing a novel characterization of **time-varying Gaussian mixture models**. We fix the mixture component distributions across all time periods to overcome data sparsity and accurately describe Toronto’s spatial structure, while representing the complex spatio-temporal dynamics through time-varying mixture weights. We constrain the mixture weights to capture weekly seasonality, and apply a **conditionally autoregressive prior** on the mixture weights of each component to represent location-specific short-term serial dependence and daily seasonality. While estimation may be performed using a fixed number of mixture components, we also extend to estimate the number of components using **birth-and-death Markov chain Monte Carlo**. The proposed model is shown to give higher statistical predictive accuracy and to reduce the error in predicting emergency medical service operational performance by as much as two-thirds compared to a typical industry practice.

Some visualization of the data.
![1](https://github.com/ArcherCYM/Gaussian_mixture_model/assets/49087999/f35d2e9b-133f-489e-9052-9942a76f11f9)

![ablation1](https://github.com/ArcherCYM/Gaussian_mixture_model/assets/49087999/19797701-9bbf-46ee-b387-c486d89e65e1)


Gaussion mixture model fits results (specify the time):
![2](https://github.com/ArcherCYM/Gaussian_mixture_model/assets/49087999/2019dd75-2415-4213-8de9-7e902387d003)

Possion mixture model fits results (specify the time):
![3](https://github.com/ArcherCYM/Gaussian_mixture_model/assets/49087999/3c092f70-789b-49da-979e-15cfb87b0d67)


---

### Tips
*If you have any problem, you can send an email archercym@gmail.com or make an issue directly. We can discuss together.*
