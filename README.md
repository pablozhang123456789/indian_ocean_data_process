# indian_ocean_data_process
share some codes
* `data_cutting`:根据研究区域截取mat数据, nc数据和HDF5数据并保存为nc格式
* `mean&clim&detrended_data`:得到表层，100m层的S,U,V,T数据的平均态，气候态和去除气候态的异常值，保存为nc格式
* `plot_mean&clim_state`:绘制表层，100m层S,U,V,T,E-P(表层)平均态和气候态
* `SUVTEP_EOF`:对表层，100m层的S,T,E-P进行EOF分解, 对U, V进行complex EOF分解
* `apply_EEMD&complex_EEMD` 对数据进行EEMD分解和复EEMD分解
