# الـ toolkit: الـ notebooks والمعطيات

هنا كاينين الـ notebooks اللي كيحسبو كاع الأرقام ديال اللوحة، والملفات اللي كيقراو منها.

## الـ notebooks

| الملف | شنو فيه |
|---|---|
| `Morocco_Elections_KPI_Toolkit.ipynb` | الانتخابات ديال 2011 و2016 و2021، مع الاستطلاع ديال Arab Barometer. منو جات الأرقام ديال اللوحة اللي فالرابط. |
| `Morocco_Elections_KPI_Toolkit_v3.ipynb` | النسخة 3: زادت انتخابات 2002 و2007 والإحصاء ديال 2004، وحيدات الاستطلاع (حيت ما كاينش ل 2002 و2007). |

كل notebook كيكتب النتائج ديالو فملف Excel: `kpi_elections_maroc.xlsx` و`kpi_elections_maroc_v3.xlsx`.

## الملفات ديال المعطيات

| الملف | المصدر |
|---|---|
| `parlement-elections-2002-1-0.xlsx` … `parlement-elections-2021-1-0.xlsx` | نتائج الانتخابات التشريعية، TAFRA (منشورة على openAfrica) |
| `rgph2014_provinces.xlsx` | الإحصاء العام 2014 حسب الإقليم، HCP: http://rgphentableaux.hcp.ma/ |
| `rgph2004_provinces.xlsx` | الإحصاء العام 2004 حسب الإقليم، HCP: https://applications-web.hcp.ma/hpmc/frmmarocenchiffres.aspx |
| `geoBoundaries-MAR-ADM2_simplified.geojson` | حدود الأقاليم، geoBoundaries (OpenStreetMap، رخصة ODbL) |

الجوج ديال الملفات ديال الإحصاء تبناو بالـ notebook من المواقع ديال HCP (الدوال `fetch_hcp_census` و`fetch_hcp_census_2004`). إلا مسحتيهم، الـ notebook كيعاود يجيبهم.

## الملفات ديال Arab Barometer (ما كايناش هنا)

الـ notebook الأول كيحتاج تلاتة ديال الملفات CSV ديال Arab Barometer. ما حطيناهمش فهاد الـ repository: الشروط ديال Arab Barometer ما كتسمحش بنشر المعطيات من جديد، والملف ديال الموجة III كبير بزاف (70 MB). حملهم بيدك (التسجيل فابور) وحطهم فهاد الدوسي بهاد السميات:

| الملف | الموجة | منين تحملو |
|---|---|---|
| `ABIII_English.csv` | III · 2013 | https://www.erfdataportal.com/index.php/catalog/275 |
| `ABIV_English_Updated.csv` | IV · 2016 | https://www.erfdataportal.com/index.php/catalog/271 |
| `AB7_ENG_Release_Version6.csv` | VII · 2022 | https://erfdataportal.com/index.php/catalog/297 |

الـ notebook v3 ما كيحتاجهمش.

## كيفاش تخدم الـ notebook

خاصك Python 3 مع هاد المكتبات:

```bash
pip install pandas numpy openpyxl matplotlib scipy statsmodels requests jupyter
```

من بعد، من داخل هاد الدوسي:

```bash
jupyter nbconvert --to notebook --execute --inplace Morocco_Elections_KPI_Toolkit_v3.ipynb
```

ولا حلو فـ Jupyter وخدم الخلايا وحدة بوحدة.

## المعطيات اللي مدخلة باليد

بعض الأرقام ما كاينة فحتى ملف، ومكتوبة مباشرة فالـ notebook: القواعد الانتخابية ديال كل عام، الحكومات (عدد الأعضاء، الحقائب حسب الحزب، وزارات السيادة)، والمسجلين الوطنيين ديال 2016 و2021. الأرقام ديال 2002 و2007 فيها العلامة «verify»: خصها تتراجع مع مصدر رسمي.
