# Four Ways to See Iris: Exploring Visualization Design Choices

**A Cognitively-Driven Design Experiment**
| Group 13: Maria Sigmon, Bhargavi Chinni, Katie Sugg, and Kayla Casey

## Deployed Site

View the live visualizations at:
**https://kayla-casey.github.io/comp617-module-four-experiments/index.html**

From the home page, use the navigation links to explore each chart type:
- [Bar Charts](https://kayla-casey.github.io/comp617-module-four-experiments/bar-plots.html)
- [Pie Charts](https://kayla-casey.github.io/comp617-module-four-experiments/pie-charts.html)
- [Scatter Plots](https://kayla-casey.github.io/comp617-module-four-experiments/scatter-plots.html)
- [Spider Plots](https://kayla-casey.github.io/comp617-module-four-experiments/spider-plots.html)

## Dataset

This project uses the [Iris dataset](https://archive.ics.uci.edu/dataset/53/iris), a classic dataset with 150 instances across three flower species (Setosa, Versicolour, and Virginica), each described by four measurements: sepal length, sepal width, petal length, and petal width.

## About This Project

### Motivating Problem

Designing effective data visualizations involves making countless choices. Designers must make calculated decisions on color schemes, label placements, interactivity, and much more to communicate their underlying data effectively. Most of these choices are common, and designers often make them based on personal preferences and convention, rather than empirical evidence.

Our project investigates how design choices help or hurt users' abilities to interpret data, and if their own personal preferences appear to vary or merge with the preferences of their peers. We focus on color scheme and label interactivity as design choices, since these are common features that users often notice first. This matters because small design choices can significantly affect whether a general audience will walk away from a visualization with the intended impression of the designers.

### Chosen Method: Cognitively-Driven Design

We chose the cognitively-driven design method as it is more experiment-focused and allows us to have greater control over the participants' experience during the study. There are two main variables that we control, and this design method allows us to explicitly track which changes in design elicit which responses from the participants.

**Independent variables:** color scheme (rainbow vs. shades of purple) and label interactivity (hover-to-reveal vs. always visible). This produces four variants of each chart type.

**Dependent variables:** accuracy (users' ability to properly explain their reasoning) and similarity (how closely participants' responses align with each other).

### Hypotheses

1. Rainbow colors will work better with pie and bar charts, while ombre colors will work better for scatter and spider plots — on the assumption that distinct categories warrant distinct colors, while similar colors better convey continuous change.
2. Users will prefer interactive, hoverable labels over always-visible labels, as interactivity lets users explore data at their own pace without visual clutter.

### Experiment

Participants view all four variants of each chart type simultaneously, identify their preferred visualization, and provide brief comments explaining their choice. After evaluating all sixteen visualizations, participants explore the raw Iris dataset and discuss what design choices they would have made themselves — encouraging deeper reflection on the relationship between design decisions and data comprehension.
