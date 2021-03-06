# Pengantar Analisis NetCDF  menggunakan ```xarray```

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3669057.svg)](https://doi.org/10.5281/zenodo.3669057)

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![Open Source Love png1](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://osf.io/gvf37/)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)



```xarray``` merupakan pustaka di lingkungan komputasi ilmiah Python yang berguna untuk menangani dataset
multidimensi dengan metode pelabelan seperti pada struktur ```DataFrame```  di pustaka pandas. Hal ini sangatlah menguntungkan bagi kaum <i>awam</i> yang terbiasa
menangani data tabular, untuk mengeksplorasi data multidimensi secara lebih intuitif. Tutorial ini sendiri lebih berfokus pada analisis sederhana data luaran model iklim
berformat NetCDF menggunakan ```xarray```. Diharapkan dengan hadirnya tutorial ini, dapat membantu kesulitan para praktisi dan mahasiswa S-1, utamanya untuk bidang non-geosains dalam mengeksplorasi data berformat NetCDF.


Untuk mereproduksi tutorial ini pastikan kalian telah melakukan hal - hal sebagai berikut:

1. Jalankan: ```git clone git@github.com:sandyherho/tutorial_xarray.git```

2. Unduh dan jalankan [Anaconda versi 3](https://www.anaconda.com/distribution/#download-section).

3. Jalankan perintah berikut ini: ```conda env create -f tutorial_xarray.yml```

4. Unduh data model iklim global yang dijadikan contoh pada folder ```Data``` di situs [ini](https://osf.io/gvf37/).
