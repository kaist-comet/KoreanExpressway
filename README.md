# KoreanExpressway

This repository contains the Korean Expressway network data used in

- Chung, S. H. and C. Kwon (2015), [“Multi-Period Planning for Electric-Car Charging Station Locations: a Case of Korean Expressways”](http://dx.doi.org/10.1016/j.ejor.2014.10.029), *European Journal of Operational Research*. 242(2), 677–687.
- Chung, B.D., S. Park, C. Kwon (2018), [“Equitable Distribution of Recharging Stations for Electric Vehicles”](https://doi.org/10.1016/j.seps.2017.06.002), *Socio-Economic Planning Science*, 63, 1-11.

If you use this data, please cite:
```
@article{chung2015multi,
  title={Multi-period planning for electric car charging station locations: A case of Korean Expressways},
  author={Chung, Sung Hoon and Kwon, Changhyun},
  journal={European Journal of Operational Research},
  volume={242},
  number={2},
  pages={677--687},
  year={2015},
  publisher={Elsevier}
}
```

![Map Image](https://github.com/chkwon/KoreanExpressway/blob/master/map.jpg)

The `2011` directory includes `.csv` files that are identical to the tabs in the `2011data.xlsx`.

The road network data and the traffic volume (termed 'demand') data were obtained from http://www.ex.co.kr in 2011. The location of each node and the length of each arc are *estimated* from the GIS information available in http://openapi.nsdi.go.kr.


Note that the 2011 data is outdated. The road network in 2017 looks:

![Map Image](https://github.com/chkwon/KoreanExpressway/blob/master/current_map.jpg)


See also [the dataset for the DC-NY-BOS network](https://github.com/STOM-Group/DC-NY-BOS-Network-Data).
