# en-az-parallel-corpus

Bu qovluq İngiliscə - Azərbaycanca və Azərbaycanca - İngiliscə tərcümə məsələsinə əsasən hazırlanmış paralel toplu haqqında məlumatdan ibarətdir. Proyektin əsas məqsədi mühəndislərə və proqramçılara Azərbaycan dili üçün universal dil modeli yaratmaqda dəstək olmaqdır.

*Digər dillər: [English](README.md), [Azerbaijan](README.az.md)*

Öyrənmə datasını təsdiqləmə və test datası ilə birlikdə aşağıdakı keçidi istifadə edərək yükləyin:

```
$ curl https://s3.us-east-2.amazonaws.com/derintelligence/dataset/data.tar.gz | tar xzvf -
```
Toplunun statistikası
-----------------

| Fayl           | #cümlələr |  #sözlər | #lüğət |
|:---------------|-----------:|--------:|------------:|
| train.en       |     68,201 | 1,205,183 |       42,315 |
| train.az       |     68,201 | 928,474 |       88,002 |
| dev.en         |        500 |   9,015 |         2,867 |
| dev.az         |        500 |   6,852 |         3,832 |
| test.en        |        500 |   9,032 |         2,941 |
| test.az        |        500 |   6,905 |         3,815 |
