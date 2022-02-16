# CompositePLOTS
## Composite plots: grid.arrange
### I really like composite plots, where there’s a top part that describes a phenomenon and a bottom part with a synthetic time view of the overall process.
### I’ve recently discovered this beautiful representation of educational differentials by gender, by Sara Lopus and Margaret Frye, and the beauty of this dataviz ### is that it tells a story on its own. (https://journals.sagepub.com/doi/pdf/10.1177/2378023118795956 link for the publication)

### I have used a random generated data to reproduce the graph in ggplot and used grid.arrange from gridExtra package to bind grobs, the top and bottom components.


grid.arrange(top, bottom, heights=c(10,5), widths=c(20), padding=0)
### I have saved the map as a .png file png package and used rasterGrob from package grid to create a raster image graphical object.
