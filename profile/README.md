## r-lidar

`r-lidar` is developing free and open-source airborne laser processing software primarily designed for the R programming language. Our two main products are the `lidR` and `lasR` packages, each targeting different usages.

- `lidR` is tailored for research and development, originally developed at Laval University. It allows handy manipulation of lidar data within the R programming language. It has been widely used for 10 years by universities globally and has been cited in more than 1,000 scientific articles.

- `lasR` is tailored for highly efficient airborne lidar data processing. It has comparable tools to `lidR` but was designed to be much more powerful and efficient. However, it does not allow for easy manipulation within the R language. `lasR` allows creating complex processing pipelines and applying them to terabytes of data efficiently.

Our software are free. You can support the development by [sponsoring us](https://github.com/sponsors/Jean-Romain)

| | lidR | lasR |
|-------|----------|----------|
| | <img src="https://raw.githubusercontent.com/r-lidar/lidR/master/man/figures/logo200x231.png"/>  | <img src="https://raw.githubusercontent.com/r-lidar/lasR/main/man/figures/lasR200x231.png" align="right"/>  |
| Speciality | Versatile | Fast |
| Target usages | R&D | Production |
| Target users | Universities | Companies |

We are also maintaing other open source projets for airborne lidar data processsing in R :

- [`rlas`](https://github.com/r-lidar/rlas) : R package to read and write las and laz files used to store LiDAR data
- [`RMCC`](https://github.com/r-lidar/RMCC) : Airborne LiDAR filtering method based on Multiscale Curvature Classification
- [`RCSF`](https://github.com/r-lidar/RCSF) : Airborne LiDAR filtering method based on Cloth Simulation 
