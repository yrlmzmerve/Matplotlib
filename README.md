# Matplotlib

https://matplotlib.org/3.1.1/index.html

**Veri görselleştirmeye yarayan python kütüphanesidir.**

Veri görselleştirme, karmaşık ve dağınık verileri düzenleyerek kolay anlaşılabilir, yorumlanabilir hale getirmektir.

Kütüphaneyi import etme
```
import matplotlib.pyplot as plt
```

Grafiklerin gözükmesini sağlamak için;
```
%matplotlib inline
```

**Verilerin yüklenmesi
```
data=pd.read_excel("matplot.xlsx")
```

Veri tipinin floata çevrilmesi
```
data['enflasyon'] = data['enflasyon'].astype('float')
data['issizlik'] = data['issizlik'].astype('float')
```

 <a href="http://fvcproductions.com"><img src="https://matplotlib.org/3.1.1/_images/sphx_glr_align_ylabels_0011.png" title="FVCproductions" alt="FVCproductions"></a>
