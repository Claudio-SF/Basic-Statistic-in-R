# Basic-Statistic-in-R
Setup for the first Semester Course which gives 3ECTS
#Overview of all installed packages with a short explanation of their use
#install.packages("tidyverse") - conglomerate of most important tools for data analysis
#install.packages("readxl") - reads excel sheets: data <- read_excel("fish_data.xlsx")
#install.packages("ggplot2") - for data visualization: ggplot(data, aes(x=variable1, y=variable2)) + geom_point()
#install.packages("janitor") - for cleaning data: data <- clean_names(data)
#install.packages("dplyr") - for data manipulation: data <- data %>% filter(variable1 > 10)
#install.packages("here") - for managing project paths
#install.packages("rmarkdown") - for creating dynamic documents
#install.packages("viridis") - for color scales in plots: scale_color_viridis()
#install.packages("patchwork") - for combining multiple plots into one figure: plot1 + plot2 + plot_layout(ncol = 2)
#install.packages("vegan") - for ecological data analysis: diversity(data)
#install.packages("BiodiversityR") - for biodiversity analysis: diversity(data, index = "shannon")
#install.packages("ggpubr") - for publication-ready plots: ggboxplot(data, x = "group", y = "value")
#install.packages("nloptr") - for nonlinear optimization: result <- nloptr(x0 = initial_values, eval_f = objective_function, lb = lower_bounds, ub = upper_bounds)
#install.packages("lme4") - for linear mixed-effects models: model <- lmer(response ~ predictor + (1|random_effect), data = data)
#install.packages("glmmTMB") - for generalized linear mixed models: model <- glmmTMB(response ~ predictor + (1|random_effect), data = data, family = gaussian()))
#install.packages("DHARMa") - for residual diagnostics of mixed models: simulateResiduals(fittedModel = model)
#install.packages("ggeffects") - for visualizing effects of predictors in models: plot(ggpredict(model, terms = "predictor")


