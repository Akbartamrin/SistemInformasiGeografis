LATAR BELAKANG MASALAH

1. Apa yang dimaksud dengan web service geospatial?
2. Apa yang dimaksud dengan open geospatial consortium?
3. Apa saja tipe-tipe yang terdapat pada web service geospatial?

Pembahasan

Web service geospatial adalah bagian dari OGC(open geospatial consortium) untuk kebutuhan penggunaan data geospatial di pemrograman berbasis GIS.

Open Geospatial Consorium adalah organisasi internasional yang mengatur standar format penggunaan data geospasial.

Tipe-tipe yang terdapat pada web service geospatial:

1. Web Map Service (WMS)
Web Map Service (WMS) memberikan pengguna sarana untuk melayani peta georeferensi yang disediakan database GIS menggunakan jaringan internet. WMS menghasilkan peta dalam format gambar seperti : PNG, JPEG atau GIS dan dapat ditampilkan pada browser.

2. Web Map Tile Service (WMS)
Web Map Tile Service (WMTS) hampir sama dengan Web Map Service (WMS), perbedaannya WMTS mengirimkan tiles (kebanyakan ukurannya 256×256 pixel), sementara WMS mengirimkan satu gambar per permintaan. Keuntungan utama dari tiles adalah bahwa tiles dapat pre-render pada sisi server, dan cache di sisi klien Hal ini akan mengurangi waktu menunggu data dan bandwidth.

3. Web Feature Service (WFS)
Web Feature Service (WFS) adalah antarmuka yang memungkinkan pengguna untuk mengakses dan memanipulasi informasi fitur geospasial dari sumber jaringan terdistribusi. operasi dasarnya termasuk GetCapabilities, DescribeFeatureType dan GetFeature.

4. Web Coverage Service (WCS)
Web Coverage Service (WCS) merupakan raster standar pelayanan OGC yang mengambil informasi geospasial yang berkaitan dengan fenomena multidimensi pada titik-titik dalam ruang yang berbeda-beda di wilayah geografis. Setiap WCS menyediakan akses ke informasi melalui tiga operasi: GetCapabilities, DescribeCoverage, dan GetCoverage.
