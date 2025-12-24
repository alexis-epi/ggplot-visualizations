# ggplot-visualizations
R Scatterplot that shows the relationship between age and lung capacity

Code:
View(lung_cap)
ggplot(data = lung_cap, mapping = aes(x = Age, y = LungCap) +
geom_point() +
geom_smooth(method = "lm")
